# iaas-custom-image-ubuntu-focal
ubuntu 20.04 custom image for ibm cloud
- removed unattended upgrades
- installed docker & docker-compose

## how to test (create a custom image in us-south region)
```
export IBMCLOUD_API_KEY=<YOUR IBMCLOUD API KEY>
docker-compose run packer-ubuntu-focal  ./build_image.sh
```
