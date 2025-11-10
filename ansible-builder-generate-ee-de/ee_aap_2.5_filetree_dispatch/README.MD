ansible-builder build -t quay.io/adelahoz/ee_aap_2.5_filetree_dispatch:latest --build-arg AH_TOKEN="<YOUR_SECRET_TOKEN_HERE>"
podman push quay.io/adelahoz/ee_aap_2.5_filetree_dispatch:latest