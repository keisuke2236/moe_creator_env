# MoeCreator開発環境構築

Use the itamae is a recipe to make a rails environment.

## Usage

```
cd ~/work/moe_creator_env/
git clone git@github.com:keisuke2236/moe_creator_env.git
cd moe_creator_env
cp Vagrantfile.sample ~/work/Vagrantfile

cd ~/work/
vagrant up

cd ~/work/moe_creator_env
bundle install --path vendor/bundler
bundle exec itamae ssh --user vagrant --host 192.168.33.250 -y node/rails/development.yml rails.rb
```
