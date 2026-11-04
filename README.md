# Carve Line Lab

アルペンスノーボードのカービングターンと「走り」を、仮説を一つずつ足しながら 1D / 2D / 3D で見比べるシミュレーターです。
An alpine-snowboard carving simulator for taking apart “hashiri” (the board running out of the turn), hypothesis by hypothesis, in 1D / 2D / 3D.

- 日本語版 / Japanese: `index.html`
- English: `en/index.html`

サーバー不要の 1 ファイル構成です。物理モデルは各ファイル内の `simulate()` 関数にまとまっています。
Each page is a single self-contained HTML file; the physics lives in the `simulate()` function.

数値は実測値ではなく、仮説の強さを比べるための相対比較にのみ使ってください。
The numbers are relative comparisons for organising a rider's feel, not measurements.

Includes three.js r128 (MIT License, https://threejs.org).
