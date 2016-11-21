# cap_conf

## app_conf - capistrano config files in rails app
### Replace
{APPLICATION_NAME}, {GIT_REPO_URL}, {USER_NAME}, {APPLICATION_PATH}
### config/deploy/production.rb
puma_conf: 设置puma.rb的路径, 默认 shared/ 下, 如果文件不存在, 会uploading [erb模板](https://github.com/seuros/capistrano-puma/blob/master/lib/capistrano/templates/puma.rb.erb)

## cap_shared - capistrano shared files in server system
### Replace
{DATABASE_USERNAME}, {DATABASE_PASSWORD}, {DATABASE_SOCK_PATH}, {SECRET_KEY_BASE}