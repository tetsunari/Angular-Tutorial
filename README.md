# Angular-Tutorial

### 環境構築
1. docker compose build
2. docker compose up -d
3. docker compose exec angular-tutorial bash
4. npm i
5. ~~ng serve --host 0.0.0.0 (https://github.com/angular/angular-cli/issues/2375)~~
6. npm run start (package.jsonを変更したため)

### 2024-1-30 に立ち上げ方法を変更
1. docker-compose -f docker-compose-dev.yml build
2. docker-compose -f docker-compose-dev.yml up -d
3. docker-compose -f docker-compose-dev.yml exec angular-tutorial bash
4. （初回のみ）yarn init
5. yarn @angular/cli

http://localhost:4242/ にアクセス (dockerfileでportを変更しているため)


[tutorial-1](https://angular.jp/tutorial/first-app)https://angular.jp/tutorial/first-app
