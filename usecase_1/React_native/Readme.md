# Run test

## Android

0.  安装依赖 `npm install`
1.  将 Devace 连接到计算机（建议关闭互联网）
2.  执行命令 `./gradlew assembleRelease` з `android`
3.  开启客户端服务 `npm run start:appium`
4.  运行 e2e 测试 `npm run test:e2e:android`

## iOS

0. становити залежності `npm install`
1. 将 Devace 连接到计算机（建议关闭互联网）
2. 执行命令 `react-native run-ios --configuration Release`
3. 开启客户端服务 `npm run start:appium`
4. 运行 e2e 测试 `npm run test:e2e:ios`
