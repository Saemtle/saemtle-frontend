## 샘틀-에어플 시스템 프론트엔드 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Price](https://img.shields.io/badge/price-FREE-0098f7.svg)](https://github.com/codedthemes/mantis-free-react-admin-template/blob/main/LICENSE)
[![GitHub package version](https://img.shields.io/github/package-json/v/codedthemes/mantis-free-react-admin-template)](https://github.com/codedthemes/mantis-free-react-admin-template/)

## 설치

1. Clone from Github

```
git clone https://github.com/codedthemes/mantis-free-react-admin-template.git
```

2. Install packages
   
```
sudo apt update
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```
```
source ~/.bashrc
```
```
nvm install 16
```
```
npm install -g yarn
```
```
yarn
```

3. Run project (개발환경 Windows/MacOS 등 로컬에서 테스트할 때)

```
yarn start
```

3. 배포 (서버에 배포할 때)
```
npm run build
```
/build 안에 빌드된 정적파일이 생성됨. 이것을 서버로 배포하면 됨.

실제 배포 시, 웹서버 사용해야하나, npm 모듈인 Serve 로 테스트하면 됨

Serve 로 테스트
```
npm intall -g serve
```
```
serve -s build
```

데몬으로 실행 (백그라운드에서 계속 실행됨)
```
npm install pm2 -g
```
```
pm2 start serve --name my-app -- -s build -l 8000
```


## Documentation

[Mantis documentation](https://codedthemes.gitbook.io/mantis/)

## Technology stack

- [Material UI V5](https://mui.com/core/)
- Built with React Hooks API.
- Redux & React context API for state management.
- Redux toolkit.
- React Router for navigation routing.
- Support for react-script.
- Code splitting.
- CSS-in-JS.


## License

- Licensed under [MIT](https://github.com/codedthemes/datta-able-bootstrap-dashboard/blob/master/LICENSE)
