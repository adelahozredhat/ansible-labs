https://github.com/automationiberia/infra.controller_configuration/tree/devel/roles/filetree_create


ansible-playbook -i localhost, playbook.yaml -e '{controller_validate_certs: false, controller_hostname: awx-demo-awx.apps-crc.testing:443, controller_username: admin, controller_password: admin, flatten_output: true}'