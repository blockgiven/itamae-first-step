# Itamae first step

itamaeをvagrantで試す方法です。

## 手順

1. Vagrantをインストールする
2. vagrant init <box>
3. vagrant up
4. Gemfileに`gem 'itamae'`を追加
5. `bundle install`
6. `recipe.rb`にお好きなレシピを書く
7. `itamae -h default --vagrant recipe.rb`
