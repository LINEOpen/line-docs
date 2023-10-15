---
title: Square API
updated: 2023-10-15
---
# Square API
ここでは、`square-api.line.me`およびそれに関連するスキームではないURLについて解説します。

## `https://square-api.line.me/smw/v2/static/sm/html/`
オープンチャットメイン画面を表示します。

## `https://square-api.line.me/smw/v2/static/sm/html/#/squareCover/{emid: string}`
指定したオープンチャットのメイン画面を表示します。
- Param: `emid` string
オープンチャットの[emid](../../words/emid)を指定します。

## `https://square-recently-left.landpress.line.me/?squareEmid={emid: string}`
指定したOCの最近退会したメンバーを表示します。

- Param: emid: string
オープンチャットの[emid](../../words/emid)を指定します。

他にも chatIdやcid,tid等のクエリが存在します。