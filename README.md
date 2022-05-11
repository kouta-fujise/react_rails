# README

# Features

reactとrailsをAPIで連携した構築

The construction of react and Ruby on rails API mode.

# DEMO

/front/app/pages/index.tsxでrailsのAPIを取得しています。

React gets datas from rails API in /front/app/pages/index.tsx.

# Requirement

* ruby 2.7.6
* rails 6.0.4.8
* react 18.1.0
* mysql 5.7

# Usage

docker-compose up -d
で起動

To up with
docker-compose up -d

# Note

db:mysql
ポート 4306:3306
port 4306:3306

api:rails
ポート 4000:3000
port 4000:3000

front:next.js
ポート 8000:3000
port 8000:3000

# Author

* 藤瀬功大
* kouta fujise
* sketchbooks2490@gmail.com

