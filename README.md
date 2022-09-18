初回実行コマンド
1) docker-compose build
2) docker-compose run --rm front sh -c 'yarn create react-app . --template typescript'
3) docker-compose run --rm front sh -c 'yarn add eslint --dev'
4) docker-compose run --rm front sh -c 'yarn run eslint --init'
5) docker-compose run --rm front sh -c 'yarn add @typescript-eslint/eslint-plugin @typescript-eslint/parser'
6) docker-compose run --rm front sh -c 'yarn add prettier eslint-config-prettier eslint-plugin-prettier pretty-quick'
7) docker-compose up

https://logical-studio.com/develop/development/docker/20211217-docker-react-formatter/
https://www.tam-tam.co.jp/tipsnote/javascript/post17695.html
https://zenn.dev/manycicadas/books/b6f2d99b5208e9/viewer/c70a5d
