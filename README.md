# スプリントの見通し確認ガイド

## 概要

 * スプリント開始時とデイリースクラムにおいて、スプリントの見通しを確認・手助けするためのガイドです。
 * [スプリントあたりのチーム開発時間算出シート](./docs/スプリントあたりのチーム開発時間算出シート.xlsx?raw=true)を用いてチームの開発時間を算出します。
 * 算出した時間をもとに、スプリントの作業量の妥当性と日々の見通しを確認します。
 * チームが以下の[背景](#背景とねらい)を抱えているときに有用かつ効果的です。

## 背景とねらい

 * スプリントを開始する際、自分たちのチームがどのくらいの開発時間をもっているのか正確に把握したい。
 * 休暇や研修・勉強会など、あらかじめ分かっている予定は組み込んだ上で、開発時間を出したい。
   * そうすることで、休暇が取得しやすくなり、学習時間も確保できる。
 * 当該スプリントの開発時間を事前に把握しておき、バックログの予定工数と比較することで、オーバーワークを避けたい。
   * 当該スプリントに収まらないものを次スプリントに回す際の判断材料となる。
   * 逆に開発時間に余裕がある場合は、次スプリントのバックログを先行して着手可能となる。
 * チームが自信を持ってスプリントを開始・完了できることを工数レベルで確認したい。

## 利用方法

 1. [スプリントあたりのチーム開発時間算出シート](./docs/スプリントあたりのチーム開発時間算出シート.xlsx?raw=true)を開いてください。
 1. 開発チームのメンバー名を記載します。（列が足りない場合は追加してください。SMの入力は任意です）
 1. 1日の開発時間を設定します。（デフォルト5.0h）
 1. 定期イベント／打合せ欄を記載し、予定時間も入力します。（**時間はマイナスで入力してください**）
 1. 各メンバーのマイナス作業時間を上段に入力します。（**時間はマイナスで入力してください**）
 1. 未出社の日は下段にハイフンを入力します。
 1. 上記入力完了後、合計開発時間と日毎の残開発時間を確認します。

## 利用シーン

 * スプリントプランニング第二部（タスクばらし）完了後
   * 当該スプリントの予定工数とチームの合計開発時間を比較して、作業量が妥当かどうか判断します。
 * デイリースクラム
   * 当該スプリントの残タスク（残り時間の合計）とチームの残開発時間を比較して見通しを把握します。（達成可能なペースかどうか確認する）
   * バーンダウンチャートと併用すると効果大

## ライセンス

この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。
<br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a>
