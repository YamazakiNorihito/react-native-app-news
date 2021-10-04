- create app

```bash
$ expo init news-app
? Choose a template: › - Use arrow-keys. Return to submit.
    ----- Managed workflow -----
❯   blank               a minimal app as clean as an empty canvas    # ←chooise
    blank (TypeScript)  same as blank but with TypeScript configuration
    tabs (TypeScript)   several example screens and tabs using react-navigation and TypeScript
    ----- Bare workflow -----
    minimal             bare and minimal, just the essentials to get you started

```

- expo login

```bash
$ expo login

```

- start
  https://docs.expo.dev/workflow/expo-cli/#expo-start

```bash
$ expo start -w   # ブラウザ
$ expo start -i   # iphone
$ expo start -a   # android
$ expo start -c   # キャッシュクリア

```

- 実機で動かす場合、Expo Go を Install 必須(https://expo.dev/client)
- Expo を使ったプロジェクトから Expo を使わないプロジェクトにする場合、"eject" で変換する（逆はできない


### publish

#### 社内用
```bash
expo publish
```

#### ios
https://www.e-agency.co.jp/column/sm_app_20190905.html