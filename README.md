# go-remote-debug
This is a remote debug for the Go programming language.

### コンテナの起動
```bash
docker-compose up
```

### GolandからDebug起動

```
Run > Debug
```

<img width="350" alt="ScreenShot 2022-01-01 16 43 35" src="https://user-images.githubusercontent.com/49631805/147846396-9681fcf1-3016-4606-bbdf-4eab8dcc76ed.png">

`Edit Configurations...`をクリック

<img width="350" alt="ScreenShot 2022-01-01 16 43 43" src="https://user-images.githubusercontent.com/49631805/147846410-351ad531-60f1-4a86-86e4-5edc28a633a9.png">

### Go Remoteの追加

<img width="350" alt="ScreenShot 2022-01-01 16 44 01" src="https://user-images.githubusercontent.com/49631805/147846423-1e6c531b-95c6-47f6-b92f-f54293f5c452.png">


<img width="700" alt="ScreenShot 2022-01-01 16 44 16" src="https://user-images.githubusercontent.com/49631805/147846430-6044783b-2d5a-4a6a-b3b1-1c770cbf7aa7.png">

### 挙動チェック

ブレークポイントを貼って、エンドポイントへアクセス

```bash
curl 'http://localhost:8080'
```

<img width="700" alt="ScreenShot 2022-01-01 16 46 41" src="https://user-images.githubusercontent.com/49631805/147846431-20222b98-ca6b-48cf-9f63-1122802ac6b5.png">
