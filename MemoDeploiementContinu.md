## launch docker

sudo docker run -d --name gitlab-runner-khadija --restart always -e CI_SERVER_URL="https://gitlab.com/" -e REGISTRATION_TOKEN="GR1348941sZux8WSGHbb6ELGCTytW" -v /var/run/docker.sock:/var/run/docker.sock  gitlab/gitlab-runner:latest


avec runner-nom
et registration_token : chercher le token sur runners sur gitlab

sudo docker exec -it gitlab-runner-khadija /bin/bash

gitlab-runner register

avec ok ok ok et puis docker et puis openjdk:19

ou gitlab-runner start
GitLab
Sign in · GitLab
GitLab.com
Image
