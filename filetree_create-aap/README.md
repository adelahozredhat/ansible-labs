https://github.com/automationiberia/aap_configuration_extended/blob/62833d328c91d3067c4d8f9c542122a7fd16abae/roles/filetree_create/README.md


ansible-playbook -i localhost, playbook.yaml -e '{aap_validate_certs: false, aap_hostname: example-ansible-automation-platform.apps-crc.testing:443, aap_username: admin, aap_password: admin, flatten_output: true}'