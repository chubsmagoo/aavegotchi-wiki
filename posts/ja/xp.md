---
author: Unintelligent Nerd
date: '2020-04-23T07:00:00.000Z'
title: 'Aavegotchi XP'
description: 'Aavegotchi XPについてはここで学びます。'
contributors:
  - "unintelligent-nerd"
---

ゴッチがXPを稼ぐとレベルアップします。 では、レベルアップをするにはどれだけのXPが必要なのでしょうか。 データアナリストが、計算するためのいくつかの方法を示しています。

<div class="contentsBox">

**内容**

<ol>
<li><a href=#gaining-xp>XPを獲得</a></li>
<li><a href=#formula>数式</a></li>
<li><a href=#experience-table>XPテーブル</a></li>
<li><a href=#tracking-xp-received>受信されたXPを追跡する</a></li>
<li><a href=#xp-requirements-for-joining-guilds>XP Requirements for joining Guilds</a></li>
</ol>

</div>

## XPを獲得する方法
AavegotchisはXPを獲得する方法いくつかあります：
* [AavegotchiDAO](/dao)で投票
* Aavegotchi Discordでイベントを参加する。(GotchiでXPを受け取るため、イベント中に入力するタイプフォームをリリースします)
* [ミニゲーム](/minigames) をプレイする (Discordで発表された一定期間のみ)

## 数式
XPをレベルアップを決定するに、次の式を使用しています。

(現在のレベル^2)÷定数, ここで定数=0.02

## XPテーブル

以下の表は、各レベルに必要なXPを示しています。 データを調べる前に、以下に使用されるキーワードの用な定義を示します。

* 現在のレベル：あなたのゴッチの現在のレベル
* 次のレベル：ゴッチの次のレベル
* XP: **次のレベル** の列で指定されている到達するためのXPの必要な数値
* 違い：前の行の同じ列と比較した, **次のレベル** 列のレベルに到達するために必要なXPの違い
* 定数：次のレベルの数式に必要なXPの計算に使用される固定値

Aavegotchiが最大達成出来るレベルは99です。 最大レベルへの変更は, [AavegotchiDAO](/dao) の投票で出来ます。

*注意: ゴッチはレベル1から始まります。 XPの計算がどのように機能するかを観察するために、「レベル0」がテーブルに含まれています。*

table_XP

## 受信されたXPを追跡する方法

我々のフレンリーな [aarchitect](/aarchitect) フランクは、Gotchiが受け取ったXPを追跡するためのアプリケーションを作成してくれました。

彼が作成したアプリはこちらから [](https://aavegotchi-xp-dashboard.vercel.app) にアクセスできます。 Gotchi IDは、 [Gotchi Profile Page](/aavegotchi-profile)のURLの末尾にある数字です。

## XP Requirements for joining Guilds

Gotchis are social creatures who love to hang with their frens, but much like starry-eyed college freshmen trying to attend every campus club activity, they get burned out with too much social activity.

As they gain more experience and become more worldly, their work-life balance improves, allowing them to take on more [Guild](/guild) responsibilities.

Thus, how many Guilds a Gotchi can join depends on its XP Level.

table_xpRequirementForGuilds