https://console.redhat.com/ansible/automation-hub/repo/validated/infra/aap_configuration/content/role/dispatch/

ansible-playbook -i localhost, casc_ctrl_config.yml -e '{aap_validate_certs: false, aap_hostname: example-ansible-automation-platform.apps-crc.testing:443, aap_username: admin, aap_password: admin, aap_configuration_filetree_read_secure_logging: true}'
