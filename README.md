# MoeCreator開発環境構築

## 使い方

```
cd ~/work/
git clone git@github.com:keisuke2236/moe_creator_env.git

cp moe_creator_env/Vagrantfile.sample ./Vagrantfile

vagrant up

cd ~/work/moe_creator_env

bundle install --path vendor/bundler
bundle exec itamae ssh --user vagrant --host 192.168.33.250 -y node/rails/development.yml rails.rb

password?: vagrant
```


参考
https://github.com/zaru/itamae-rails