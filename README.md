# OS Dind

Build the dind images for RancherOS, it is used to create multiple user dockers on RancherOS.

## Build image

## Run the dind-container

`docker run --privileged -d --publish=2222:22 image_id`

## ssh dind-container

`ssh -p 2222 root@IP`
