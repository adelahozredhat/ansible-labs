https://github.com/automationiberia/aap_configuration_extended/blob/62833d328c91d3067c4d8f9c542122a7fd16abae/roles/filetree_create/README.md


ansible-playbook -i localhost, casc_ctrl_config.yml -e '{controller_validate_certs: false, controller_hostname: awx-demo-awx.apps-crc.testing:443, controller_username: admin, controller_password: admin, controller_configuration_filetree_read_secure_logging: true}'