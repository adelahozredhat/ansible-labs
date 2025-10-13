ansible-builder build -t example-ansible-automation-platform.apps-crc.testing/ee_minimal_aap_25_export_import:latest -v=3 --build-arg ANSIBLE_GALAXY_SERVER_AUTOMATION_HUB_CERTIFIED_TOKEN=xxxx


ansible-builder build -t aap-aap.apps.cluster-fjnql-1.dynamic.redhatworkshops.io/ee_minimal_aap_25_export_import:latest -v=3 --build-arg ANSIBLE_GALAXY_SERVER_AUTOMATION_HUB_CERTIFIED_TOKEN=xxxx

[galaxy]
server_list = rh-certified

[galaxy_server.rh-certified]
url=https://example-ansible-automation-platform.apps-crc.testing/api/galaxy/content/rh-certified/
token=<put your token here>

podman login --tls-verify=true example-ansible-automation-platform.apps-crc.testing
podman image tag example example-ansible-automation-platform.apps-crc.testing/example:latest
podman push --tls-verify=true example-ansible-automation-platform.apps-crc.testing/example:latest


https://catalog.redhat.com/en/search?searchType=Containers&build_categories_list=Automation+execution+environment