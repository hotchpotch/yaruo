```aa
　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　…ブランチで何か変更を加えてみる
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |
```
```
$ git checkout mybranch
Switched to branch "mybranch"
$ echo "Work, work, work" >>hello
$ git commit -m "Some work." -i hello
Created commit 171aa01: Some work.
 1 files changed, 1 insertions(+), 0 deletions(-)
```
```aa
　 　 　　　＿＿＿_
　 　　　／ノ 　 ヽ､_＼
　　　／（ ○）}liil{（○）＼　　
　 ／　　　 （__人__）　　　＼　せっかく使い方を覚えたのに vi が起動しなかったお！！
　 |　　　ヽ　|!!il|!|!l|　/　　　|
　 ＼　　　　|ｪｪｪｪ| 　 　 ／


　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　-m オプションでコミットメッセージを指定できるのさっ
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　あと -i はインデックスに hello を追加してコミットするよっ
　 |i　|　从 ● 　 　 ●ｌ小N　　　
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´



　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　master に戻ってみて…
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |
```
```
$ git checkout master
Switched to branch "master"
```
```aa
　 　　　　 　ﾉ Ｌ＿＿＿_
　　　　　　　⌒　＼　／ ＼
　　　　　　／　（○）　（○）＼　　hello の中身が元に戻ってしまったお！
　　　　 ／　　　 （__人__）　　 ＼　　謝罪と賠償を請求するお！！
　　　 　|　 　 　　　|::::::|　　　　　|
　　　　 ＼ 　 　 　 l;;;;;;l　　 　／l!| ! 



　　　　　　　　　　 　 -‐ '´￣￣｀ヽ､
　　 　 　 　 　 　 ／　／" ｀ヽ ヽ　　＼
　　　　　　　　　//, '/　　　　 ヽﾊ 　､　ヽ　ファイルの中身はオブジェクトとしてどこかに保存されているんだよっ！
　　　　　　　　 〃 {_{＼　　　 ／ﾘ| ｌ │ i|　いちいち騒ぐんじゃないよっ！
　　　　　　　　 ﾚ!小ｌ●　　　 ● 从　|、i|
　　　　　　　 　 ヽ|l⊃　､_,､_,　⊂⊃　|ﾉ│　　master でもファイルを変更するにょろ！
　 　 　 　 /⌒ヽ__|ﾍ　　 ゝ._）　 　j /⌒i !
　　　　　　＼ /:::::|　l＞,､ __,　イァ/　 /│
.　　　　　 　 /:::::/|　|　ヾ:::|三/::{ﾍ､__∧ |
　　　　　　　｀ヽ< |　|　　ヾ∨:::/ヾ:::彡'　|


　 　 　　　＿＿＿_
　 　　　／　　 　 　＼
　　　／　─　 　 ─　＼　　　ならいいんだお…
　 ／ 　 （●） 　（●） 　 ＼　すまなかったお
　 |　 　 　 （__人__）　　　　|　
　 ＼　　 　 ｀ ⌒´ 　 　 ／

```
```
$ echo "Play, play, play" >>hello
$ echo "Lots of fun" >>example
$ git commit -m "Some fun." -i hello example
Created commit cf8002d: Some fun.
 2 files changed, 2 insertions(+), 0 deletions(-)
```
```aa
　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　ここで gitk --all すると今の状況がわかる
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 gitk が使えないなら git log --graph --all でもいい
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |



　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　--graph オプションは最近のじゃないとないらしいから
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　やる夫くんのためにまたまた貼っちゃうよ！
　 |i　|　从 ● 　 　 ●ｌ小N　　　
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´
```
```
$ git log --graph --all
* commit cf8002d81efe72e74ddaa6308984b41586a70cf3
| Author: yaruo <yaruo@example.com>
| Date:   Sat Jul 26 22:26:28 2008 +0900
|
|     Some fun.
|
| * commit 171aa013ad9b7f3ef0d1d1623bff88fe90c62f77
|/  Author: yaruo <yaruo@example.com>
|   Date:   Sat Jul 26 22:14:22 2008 +0900
|
|       Some work.
|
* commit bb8322210e30931a1d916b0d7d4dd24036ab6bbf
| Author: yaruo <yaruo@example.com>
| Date:   Sat Jul 26 15:24:24 2008 +0900
|
|     ⊂二二二（ ＾ω＾）二⊃
|
* commit 71e583b286465e8ec7b92d4b642dc77fee53562e
  Author: yaruo <yaruo@example.com>
  Date:   Sat Jul 26 13:02:42 2008 +0900

      Initial commit
```
```aa
　　　　　　＿＿＿
　　　　／ ⌒　　⌒＼
　　 ／　（⌒）　 （⌒） ＼　　　
　／ 　 ///（__人__）/// ＼　　
  |　　 u. 　 `Y⌒y'´　　　 |　　　なんだかかっこいいお！
　 ＼ 　 　 　 ﾞー ′　　,／　　　cf8002 と 171aa01 が同じ bb83222 を親としているということかお！
 　 /⌒ヽ　 　ー‐ 　 　ｨヽ　　　　
　 / rｰ'ゝ　　　　　　　〆ヽ
　/,ﾉヾ　,>　　　　　　ヾ_ノ,|
　|　ヽ〆　　　　　　　　|´　|



　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　…その通り
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 git-merge でブランチをマージできる
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　mybranch を今いる master ブランチにマージするにはこうする
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |
```
```
$ git merge -m "Merge work in mybranch" mybranch
Auto-merged hello
CONFLICT (content): Merge conflict in hello
Automatic merge failed; fix conflicts and then commit the result.
```
```aa
　 　 　　　＿＿＿_
　 　　　／ノ 　 ヽ､_＼
　　　／（ ○）}liil{（○）＼　　
　 ／　　　 （__人__）　　　＼　コンフリクトとか大文字で言われたお！
　 |　　　ヽ　|!!il|!|!l|　/　　　|　やる夫が何か悪いことしたのかお！？
　 ＼　　　　|ｪｪｪｪ| 　 　 ／



　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　…落ち着いて
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 今のはわざとコンフリクトするようにしただけ…
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　mybranch を今いる master ブランチにマージするにはこうする
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |


　 　 　　　＿＿＿_
　 　　　／ノ 　 ヽ､_＼
　　　／（ ○）}liil{（○）＼
　 ／　　　 （__人__）　　　＼　有希ちゃんはやる夫に恨みでもあるのかお！
　 |　　　ヽ　|!!il|!|!l|　/　　　|　…とりあえず手で修正すればいいお？
　 ＼　　　　|ｪｪｪｪ| 　 　 ／
```
```
$ cat hello
Hello World
It's a new day for git
Play, play, play
Work, work, work
```
```aa
　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　手で修正が終わったら
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 git-commit でマージを完了させる
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |
```
```
$ git commit -i hello
Merge work in mybranch

Merge branch 'mybranch'

Conflicts:

        hello
#
# It looks like you may be committing a MERGE.
# If this is not correct, please remove the file
#       .git/MERGE_HEAD
# and try again.
#

# Please enter the commit message for your changes.
# (Comment lines starting with '#' will not be included)
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#       modified:   hello
#
```
```aa
　　　　　 　　　＿＿＿_
　　　　 　／::::::─三三─＼
　　　　／:::::::: （ ○）三（○）＼　　　　なんかエディタの中身がいつもと違うお！
　　　　|::::::::::::::::::::（__人__）:::: 　|　＿＿＿＿＿＿＿＿＿
　 　　 ＼:::::::::　 　|r┬-| 　 ,／　| 　　|　　　　　　　　　　|
　　　　ノ::::::::::::　　`ー'´　　　＼ | 　　|　　　　　　　　　　|



　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　…気にしないで
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 手動マージの時はいつもそう
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　そのまま保存すればいい
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |


　 　 　　　＿＿＿_
　 　　　／　　 　 　＼
　　　／　 _ノ 　ヽ､_　 ＼
　 ／ 　oﾟ⌒　　　⌒ﾟo　 ＼ 　　　　なんだか有希ちゃんが信用できなくなってきたお…
　 |　　　　 （__人__）　　　　|　　　　でも言うとおりにするお
　 ＼　　 　 ｀ ⌒´ 　 　 ／ 



　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　手動マージが無事終わったみたいだね！
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　もう一度 git-log --graph を見てみるよ！
　 |i　|　从 ● 　 　 ●ｌ小N　　　(ちなみに、HEAD の親に mybranch が入ってるから --all は要らないのさっ！)
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´
```
```
$ git log --graph
*   commit ff47b11b42ebfc9095d8c212dd5a0b1c27518535
|\  Merge: cf8002d... 171aa01...
| | Author: yaruo <yaruo@example.com>
| | Date:   Sat Jul 26 22:39:55 2008 +0900
| |
| |     Merge work in mybranch
| |
| |     Merge branch 'mybranch'
| |
| |     Conflicts:
| |
| |             hello
| |
| * commit 171aa013ad9b7f3ef0d1d1623bff88fe90c62f77
| | Author: yaruo <yaruo@example.com>
| | Date:   Sat Jul 26 22:14:22 2008 +0900
| |
| |     Some work.
| |
* | commit cf8002d81efe72e74ddaa6308984b41586a70cf3
|/  Author: yaruo <yaruo@example.com>
|   Date:   Sat Jul 26 22:26:28 2008 +0900
|
|       Some fun.
|
* commit bb8322210e30931a1d916b0d7d4dd24036ab6bbf
| Author: yaruo <yaruo@example.com>
| Date:   Sat Jul 26 15:24:24 2008 +0900
|
|     ⊂二二二（ ＾ω＾）二⊃
|
* commit 71e583b286465e8ec7b92d4b642dc77fee53562e
  Author: yaruo <yaruo@example.com>
  Date:   Sat Jul 26 13:02:42 2008 +0900

      Initial commit
```
```aa
　 　　　＿＿＿_　　
　　　／　　 　 　＼
　 ／　　─　 　 ─＼　　なるほど…
／ 　　 （●） 　（●） ＼　確かにグラフで見ればマージ以外の何者でもないお
|　 　　 　 （__人__）　 　 |　　コミットメッセージを見れば
/　　　　 ∩ノ ⊃　　／　　　　どのファイルを手動マージしたか分かるということかお
(　 ＼　／ ＿ノ　|　 |
.＼　“　　／＿＿|　 | 　
　　＼ ／＿＿＿ ／ 　 



　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　原文では git-show-branch をしてるけど
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　正直見づらいからあまり出番はないと思うよ！
　 |i　|　从 ● 　 　 ●ｌ小N　　　一応解説しておくよ！
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´


　　　　　　　_________
　　　　　 ／　　　　 ＼
　　　　／　　 ―　　―＼
　　 ／　　 （ ●） 　（●）＼　　　やる夫は興味ないから
　　 i 　　　⌒ （__人__） ⌒ i 　　　ウコン茶でも飲んでるお
　　　ヽ、　　　 `⌒ '　　 ／　　　　　　
　　　 　/　　　　　┌─┐
　　　 　i　　 丶　ヽ{ .茶 }ヽ
　　　 　ｒ 　 　 ヽ、__)一(_丿
　　　 　ヽ、___　　　ヽ　ヽ　
　　　　 と_＿＿_＿ノ＿ノ
```
```
$ git show-branch --topo-order --more=1 master mybranch
* [master] Merge work in mybranch
 ! [mybranch] Some work.
--
-  [master] Merge work in mybranch
*+ [mybranch] Some work.
*  [master^] Some fun.
```
```aa
　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　最初の2行は注目しているブランチだよ！
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　"*" がついてる master が今の HEAD だねっ
　 |i　|　从 ● 　 　 ●ｌ小N　　　
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　4行目からは親のコミットを表示しているよ！
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　1列目に印があるのは master に含まれるコミット
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 2列目に印があるのは mybranch に含まれるコミットなのさっ！
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´


　　　　　　　　　　　,..　--- ..
　　　　　　 ,..-.:.￣.:..:..:.. : : : : ｀丶、
　　　 　 ／:..:..:.　..: : : : : : : : : : : : :＼
　　　　/:ﾍ=､､:.＿: : : : ＿＿:ヽ:_:　-^,.ﾄ､
　　　ノ:..:..:./:.. ￣: :７´:―― : :|‐: :´､: ヽヽ
　　ｰ-/:..:.i:../:. : : ,/:..:.:ｲ:.ﾊ:.. : j:.. :}:.､ヽ:. ﾄヽ
　　　 !:..:..:|:.{/:..ィ_jz≦ﾉ '　}:.／_}_ｲ:. } |:.｜||
　　　 Vl:.:.|:. Vl´｢＿　､｀　ﾉ′ ＿ﾉ:ｿ:ｲ: ﾘ ﾉ
.　 　 　 }:ハ: : l f7｢::｀ﾊ　　　/:::7}7ｲ:/}/
　　　　 ﾉﾍｰl､: :!VZﾂ　　 　 ﾋ:ﾉ/:.//　
　　　 　 　 ｀ｨﾍ:ﾄ､ _　　　_ 　 ノ:ｲ/　　… "-" の印はマージを表す
　　　　　 rく､＼｀ ヽ二コ:千:|K、′　　　普通のコミットは "*" HEAD でないブランチの親は "+"
　　　　　 |:..:ヽヽ＼: :Yﾆ|: :!:/j!:.l　　　　
　　　　　 ﾄ:..:..:.＼ヽ＼!r|┴＝ミ!r ァ７ master^ というのは master の親コミットのこと
　　　　　｜!::.:..:.ヽ＼ヽ|!　　　 /７　/　詳しくは git-rev-parse(1) を見て
　　　　　 j::.l::..:..:.⌒ｰｧ⌒} 　 / / /^}
　　　　　 |::.:.＼::..::.::.::>ｰ'―-L∠_¨´
　　　　　 l::.::.:..:.￣￣ト ､, --､―弋i
　　　　 　 ヽ::.:..:..:.::..∧/　　　 ヽ　 i _ ..　-―
　　　　　　 ｀｀ｰニ´／ー-､　　 |　_|
　　　　　　　_.　-―　￣　 ト―.:｢:.:l
　　　　　　　　　　 　 　 　 ヽ:..__:L_|
　　　　　　　　　　　　　　　　ヽ.__)ﾉ


　 　 　　　＿＿＿_
　 　　　／⌒　　⌒＼ ﾎｼﾞﾎｼﾞ
　　　／（ ●） 　（●）＼
　 ／::::::⌒（__人__）⌒::::: ＼ 　終わったかお？
　 |　　　 ｍj |ー'´　　　　　 | 　
　 ＼　 〈＿_ﾉ　　　　　 　／
　　　　ノ　　ﾉ



　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ     今度は mybranch で作業していたつもりになって…
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　mybranch が master にマージされたという変更を
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 git-merge で mybranch に取り込む
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |


　 　 　　　＿＿＿_
　 　　　／　　 　 　＼
　　　／　 _ノ 　ヽ､_　 ＼
　 ／ 　oﾟ⌒　　　⌒ﾟo　 ＼ 　　　　またコンフリクトしないか心配だお…
　 |　　　　 （__人__）　　　　|　　　　
　 ＼　　 　 ｀ ⌒´ 　 　 ／ 
```
```
$ git checkout mybranch
Switched to branch "mybranch"
$ git merge -m "Merge upstream changes." master
Updating 171aa01..ff47b11
Fast forward (no commit created; -m option ignored)
 example |    1 +
 hello   |    1 +
 2 files changed, 2 insertions(+), 0 deletions(-)
```
```aa
　 　　　　＿＿＿_
　 　　　／⌒　　⌒＼
　　　／（ ●） 　（●）＼
　 ／::::::⌒（__人__）⌒::::: ＼　なんだかすんなり行ったお！いつもこうならいいのにお！
　 |　　　　　|r┬-|　　　　　|　　けど Fast forward って何だお？
　 ＼ 　　 　 `ー'´ 　 　 ／


　　　　　　　　　　　／.:.:.　　　　　　　　 ＼
　 　 　 　 　 　 　 /:,:.:.:　 ／　　　ヽ　　　　＼
　　　　　　　　　 /.:.l:.:.:/:/　　　:/ 　',　:l　　 ヾ`ｰ
　 　 　 　 　 　 /!:.:.|:.: l/　 〃 /　j　}　:|　 　 ﾊ     mybranch には master にマージされたもの以外入っていないから…
　　　　　　　　/ｲ:.:.i|:.:.jL∠/_/ | /l.ﾑ_/|　l 　ｌ }　　実際には mybranch のトップを master のそれにしただけ
　　　　　　　　　N:.ﾊ:.:.:lｨfｱﾄ/　ﾚ　ｨ=ﾄ | /| ∧j　　 　　 これを fast foward merge と呼ぶ
　　　　　　　　　　ヽﾑ:.} ii;_j　　　　ii;ﾘ ﾙ iﾚヽ.　　　
　 　 　 　 　 　 　 　 `ﾍ:ゝ　　　_ 　 　 小/　　　　　
　 　 　 　 　 　 　 　 　 ヾ:{＞､ _　ｨ＜}/|/　　　　　
　　　　　　　　　　 _, ｨr'´ヽ｛ __＿`}　ヽ､_　　　
　　　　　　　　　／| l:|　　　| =＝=|　　 |:lﾞヽ　　　
　　　　　 　 　 /　 | l:ｌ　　　l 　 　 l　　 l::ｌ　l
　　 　 　 　 　 l　　ヽﾊ　 　 l　 　 l　　//　 |


　 　　　＿＿＿_　　
　　　／　　 　 　＼
　 ／　　─　 　 ─＼　　
／ 　　 （●） 　（●） ＼　確かに .git/refs/heads/{master,mybranch} は内容が一緒になってるお…
|　 　　 　 （__人__）　 　 |　　くっついたり離れたり急がしい奴等だお
/　　　　 ∩ノ ⊃　　／　　　　
(　 ＼　／ ＿ノ　|　 |
.＼　“　　／＿＿|　 | 　
　　＼ ／＿＿＿ ／ 　 


　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　git-show-branch の結果はこんな風になってるよ！
　 |i　|　从 ● 　 　 ●ｌ小N　　　　master も mybranch も、マージコミットを共通の親として持ってるんだねっ！
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´
```
```
$ git show-branch master mybranch
! [master] Merge work in mybranch
 * [mybranch] Merge work in mybranch
--
-- [master] Merge work in mybranch
```
```aa
　　 　 ,　'´￣￣｀ ｰ-､　　　　　
　　 ／　　 〃" ｀ヽ､　＼　　　　
　 /　/　 ﾊ/　　　　 ＼ﾊﾍ　　　
　 |i │ ｌ |ﾘノ　　　 ｀ヽ}_}ハ.　　
　 |i　|　从 ● 　 　 ●ｌ小N　　　　次は他人の変更をマージする方法だよ！
　 |i （|　⊂⊃ ､_,､_,　⊂lｉ|ノ　　 　
　 | i⌒ヽ j　　（_.ノ 　　ﾉi|__／⌒)　
　 | ヽ 　ヽx＞､ __,　イｌ　|::::ヽ／.　 
　 |　∧__,ﾍ}::ﾍ三|:::::/ｌ|　|',:::::ﾊ　　
　 |　ヾ_:::ッﾘ :::∨:／　|　| >'''´
```

