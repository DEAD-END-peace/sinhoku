# Azimuth & Distance Calculation Tool  
# 方位角・距離計算ツール

A lightweight **browser-based tool** to calculate **azimuth (bearing)** and **distance** between geographic points.  
Set a base point (Point A), then calculate distance and direction to Points B, C, D, or generate a new point by specifying **bearing and distance**.  
Open locations directly in **Google Maps** or **Apple Maps**, and share results via URL.

ブラウザで動作する簡易的な **方位角・距離計算ツール** です。  
基準点（A点）を設定し、B, C, D までの **方位角（真北基準）** と **距離(km)** を計算できます。  
さらに、A点から **任意の角度・距離** を指定して新しい地点を算出し、GoogleマップやAppleマップで開けます。  
結果は **共有URL** としてコピー可能です。

---

## Features / 主な機能

- **Input Mode Switch / 入力モード切替**  
  - Decimal Degrees (e.g., `33.25032, 130.49475`)  
  - Degrees, Minutes, Seconds (DMS, e.g., `33°15′25″`)  

- **Point Calculation / 地点計算**  
  - Supports Points A, B, C, D  
  - Calculates **bearing & distance** from A to each  

- **Map Links / マップリンク生成**  
  - Open in Google Maps or Apple Maps  
  - Optimized for iOS, Android, and PC  

- **Shareable URL / 共有URL生成**  
  - Generates a link containing all input data  
  - Share with others to reproduce the same setup  

- **Custom Point from Bearing & Distance / 任意の角度・距離で地点追加**  
  - Enter angle (°) and distance (km/m) from Point A  
  - Automatically adds a clickable map link  
  - Clear button resets inputs & custom links  

- **Visualization (SVG) / 可視化 (SVG)**  
  - Displays direction and distance vectors from Point A  

---

## Usage / 使い方

1. Enter coordinates for Point A  
   A点の座標を入力  
2. Optionally enter Points B, C, D  
   必要に応じて B, C, D の座標を入力  
3. Click **Calculate** to see results  
   「計算」ボタンで結果を表示  
4. Use **Map Links** to open locations  
   マップリンクから地図アプリを開く  
5. Click **Generate Share URL** to copy a link  
   「共有URL生成」でリンクをコピー  
6. Enter custom **bearing & distance** to add a new point  
   任意の角度・距離を入力し、地点を追加可能  

---

## Environment / 動作環境

- Works on PC & Smartphone browsers  
  (Chrome, Safari, Edge, etc.)  
- Tested on **iOS** & **Android**

PC・スマートフォンブラウザで動作  
(iOS / Android 含む)

---

## License / ライセンス

MIT License
