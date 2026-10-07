# プライバシーポリシー / Privacy Policy

**SunPosWeather**
最終更新日 / Last updated: 2026-10-07

---

## 日本語

### 収集しない情報

SunPosWeather はアカウント登録を必要とせず、利用者を識別する情報（氏名・メールアドレス・
端末 ID・広告 ID）を一切収集しません。解析ツールや広告 SDK は組み込んでいません。
利用者の行動を追跡することはなく、他社と共有するデータもありません。

### 端末内に保存される情報

登録した撮影地点（名前・緯度経度・被写体の方位・カメラの向き・ジャンル・稜線の仰角）と、
取得した天気予報は、**利用者の端末の中だけに**保存されます。開発者はこれらを閲覧できません。
アプリを削除すると、これらのデータも一緒に削除されます。

### 外部に送信される情報

天気と地形を調べるために、**撮影地点の緯度経度**が次のサービスへ送られます。送られるのは
座標と日時だけで、利用者を識別する情報は含まれません。

| 送信先 | 送る内容 | 目的 |
|---|---|---|
| Apple（WeatherKit） | 地点の緯度経度 | その地点の天気予報の取得 |
| Apple（MapKit の逆ジオコーディング） | 地点の緯度経度 | 地点の現地タイムゾーンの判定 |
| Open Topo Data（第三者が運営する公開 API） | 地点周辺の緯度経度 | 周辺地形の標高から稜線の高さを推定 |

Apple が受け取った情報の扱いは Apple のプライバシーポリシー
（https://www.apple.com/legal/privacy/）に従います。Open Topo Data への送信は、
稜線の高さがまだ設定されていない地点の詳細画面を開いたとき、または利用者が
「周辺の地形から自動推定」を実行したときに発生します。

### 位置情報の利用

現在地は、地図の表示と「稜線」タブ（カメラに太陽の軌道を重ねる機能）でのみ使用します。
利用中のみの許可で動作し、バックグラウンドでは取得しません。現在地を端末外へ保存することは
ありません。

### カメラの利用

「稜線」タブでカメラ映像に太陽の軌道を重ねます。映像は画面に表示するだけで、
**保存も送信もしません**。

### 子どものプライバシー

本アプリは特に子どもを対象としたものではなく、子どもから個人情報を収集することもありません。

### ポリシーの変更

内容を変更した場合は、このページを更新し、最終更新日を改めます。

### お問い合わせ

連絡先: akagisrapid@gmail.com

---

## English

### Information we do not collect

SunPosWeather requires no account and collects no information that identifies you (name,
email address, device identifier, or advertising identifier). It contains no analytics or
advertising SDKs. It does not track you, and no data is shared with third parties for
their own purposes.

### Information stored on your device

The shooting spots you create (name, coordinates, subject heading, camera heading, genre,
ridge elevation) and the weather forecasts fetched for them are stored **only on your
device**. The developer cannot see them. Deleting the app deletes this data with it.

### Information sent to external services

To look up weather and terrain, the **coordinates of a spot** are sent to the services
below. Only coordinates and dates are sent; nothing that identifies you is included.

| Recipient | What is sent | Purpose |
|---|---|---|
| Apple (WeatherKit) | Spot coordinates | Fetching the weather forecast for that spot |
| Apple (MapKit reverse geocoding) | Spot coordinates | Determining the spot's local time zone |
| Open Topo Data (a third-party public API) | Coordinates around the spot | Estimating ridge elevation from surrounding terrain |

Information received by Apple is handled under Apple's privacy policy
(https://www.apple.com/legal/privacy/). Requests to Open Topo Data are made when you open
the detail screen of a spot whose ridge elevation has not been set yet, or when you tap
"Estimate from surrounding terrain".

### Use of location

Your location is used only to show the map and for the Ridge tab, which overlays the sun's
path on the camera view. The app uses while-in-use access and never collects location in
the background. Your location is never stored off your device.

### Use of the camera

The Ridge tab overlays the sun's path on the camera view. The video is only displayed on
screen — it is **never saved or transmitted**.

### Children's privacy

This app is not directed at children and does not knowingly collect personal information
from them.

### Changes to this policy

If this policy changes, this page will be updated and the "Last updated" date revised.

### Contact

Contact: akagisrapid@gmail.com
