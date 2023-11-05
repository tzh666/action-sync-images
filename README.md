# action-sync-images


同步国外镜像


1、修改 config.yaml
将 push_images: false 中的 false 修改为true，例如 push_images: true
将想要上传的镜写在这个列表下

  images:
    - docker.io/nginx:latest
    - docker.io/redis:latest

注意：写全域名
