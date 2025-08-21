# 方位角・距離計算ツール (タブ化 + 自動位置取得対応)

このプロジェクトは、指定した地点（A～D）や現在地を基点として、  
任意の方位角・距離から目的地を計算し、Google マップリンクを自動生成するツールです。  
Apple の Human Interface Guideline を参考に、タブ化 UI を採用しています。

## 主な機能
- **地点入力 (A〜D)**  
  緯度・経度を入力して基準点を設定
- **現在地自動取得**  
  Geolocation API を用いてワンクリックで A 点に現在地を反映
- **任意角度・距離追加**  
  A 点から任意の方位角・距離で新しいリンクを生成
- **結果表示**  
  計算結果や Google マップへのリンクを一覧表示
- **方位・距離可視化**  
  SVG による真北基準の矢印表示
- **共有 URL**  
  入力データを共有できる URL を自動生成

## 使用方法
1. `index.html`（または `自動位置取得(タブ化).html`）をブラウザで開く  
2. 「入力」タブで A〜D の緯度・経度を入力  
3. 「現在地をA点にセット」ボタンで自動入力も可能  
4. 「任意リンク」タブで角度・距離を指定し追加  
5. 「結果・マップ」タブで計算結果とリンクを確認

## 技術仕様
- HTML / CSS / JavaScript（純粋フロントエンド）
- Geolocation API 使用
- Apple HIG を参考にしたタブ UI 実装
- ローカル環境または HTTPS サーバで動作確認推奨

---

# Bearing & Distance Calculation Tool (Tabbed + Auto Geolocation)

This project provides a simple browser-based tool to calculate destination points  
from a reference location (A–D or current location) given a bearing and distance.  
It also auto-generates shareable Google Maps links.

## Features
- **Point Input (A–D)**  
  Enter latitude/longitude to define a base point
- **Auto Geolocation**  
  Use the Geolocation API to set your current location as Point A
- **Custom Bearing & Distance**  
  Add arbitrary points by specifying angle and distance from Point A
- **Results View**  
  Displays calculated coordinates and direct Google Maps links
- **Visualization**  
  SVG diagram with true north reference
- **Shareable URL**  
  Generate and copy a link containing your input data

## How to Use
1. Open `index.html` (or `自動位置取得(タブ化).html`) in a browser  
2. In the **Input** tab, enter coordinates for Points A–D  
3. Optionally click **Set current location as Point A**  
4. In the **Custom** tab, enter a bearing and distance to add a new link  
5. In the **Results** tab, view calculated data and open Google Maps

## Tech Stack
- Pure HTML / CSS / JavaScript  
- Uses Geolocation API  
- Tabbed UI based on Apple Human Interface Guidelines  
- Works best over HTTPS or localhost
