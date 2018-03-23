# Gitlab-Runner

~~~ shell
docker run -d --name gitlab-runner -v <path to config>:/etc/gitlab-runner -v /var/run/docker.sock:/var/run/docker.sock shakapark/gitlab-runner:1.1
~~~
