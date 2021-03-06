## Vim


---


### Vimの基本操作

---


### ファイル操作

___

| key | 内容 |
|:-------------|-------------:|
| ZZ | 上書き保存し終了 | 
| :w | 保存 | 
| :q! | 保存せずに終了 |



---


### モード

___

| key | 内容 |
|:-------------|-------------:|
| i | 挿入モード(insert) | 
| o | 新しい行を追加、挿入モード | 
| R | 上書きモード(overwrite) |
| v | ヴィジュアルモード(visual) |
| Ctrl+v | 矩形選択のビジュアルモード |
| esc | コマンドモードに戻る |
| Ctrl+\[ | コマンドモードに戻る |
| Ctrl+z | vim を一時停止 |

---

### カーソル移動

___

| key | 内容 |
|:-------------|-------------:|
| w | 次の単語 (word) |
| b | 前の単語 (before)|
| f{} | カーソルがある行の文字に移動 (find) |
| F{} | カーソルがある行の文字に移動 (逆向き) |
| 0 | 行頭 |
| ^ | 行頭 |
| $ | 行末 |
| % | 対応する括弧に移動 |
| Ctrl+u | 半画面上 (up) |
| Ctrl+d | 半画面下 (down) |
| zz | カーソルが画面中央になるようにスクロール |
| Ctrl+o | 古いカーソル位置に戻る。 (old) |
| Ctrl+i | 新しいカーソル位置に進む。 |


---

### 行移動

___

| key | 内容 |
|:-------------|-------------:|
| gg | 最初の行 |
| {}G | {}行目 |
| G | 最終行 |
| H | 画面上の最初の行 (Home) |
| M | 画面上の中央の行 (Middle) |
| L | 画面上の最後の行 (Last) |

---

### 検索と置換

___

| key | 内容 |
|:-------------|-------------:|
| * | カーソル下の単語を検索 |
| # | カーソル下の単語を検索 (上方向に検索) |
| :%s/{1}/{2}/g | 単語の置換({1}を{2}へ置換). |

`%` はファイル全体を表す。

---

### 編集

___

| key | 内容 |
|:-------------|-------------:|
| . | 直前の変更を繰り返す |
| u | Undo |
| Ctrl + r | Redo |

---

### コピー&ペースト

___

| key | 内容 |
|:-------------|-------------:|
| yy | 今いる行をコピー (yank) |
| p | カーソルの場所に、ペースト |
| yy{}p | 現在の行をコピーし、下に{}行追加する |
| gv | 直前の選択範囲を再選択 |

---

### 特殊文字

___

| key | 内容 |
|:-------------|-------------:|
| Ctrl-v return | 改行文字の入力 |
| Ctrl-v tab | Tab 文字の入力 |


