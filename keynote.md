---
marp: true
theme: custom
footer: "MoveOnHackathon2 ハンズオン! Github講座"
---

# **ハンズオン! Github 講座**

MoveOnHackathon2 by がっしー

---

<!--
_class: body
-->

# 対象

- MoveOnHackathon2 の参加者
- Git・Github に触れたことがない初心者

---

<!--
_class: body
-->

# 目次

- Git ってなんだ?

---

<!--
_class: body
-->

# Git ってなんだ?

Git の公式 HP を見てみると、

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
> https://git-scm.com/

と書いてある。

---

<!--
_class: body
-->

# Git = 分散型バージョン管理システム

**バージョン管理システム...**
過去のファイルを残しておき、変更を管理するためのシステム

<div class="split">
<h3>
  🙅 無い場合
  <img src="img/version_control_system_disable.svg" width="70%">
<h3>
  🙆 ある場合
  <img src="img/version_control_system_enable.svg" width="70%">
</div>

---

<!--
_class: body
-->

# 差分とは?

バージョン管理システムは，コードなどの**変更を管理**
そのため、変更前と変更後の**差分**という考え方でデータを保管!

![diff.svg](img/diff.svg)

---

<!--
_class: body
-->

# 差分とは?

追加された・変更された・削除された部分を保存することで、
どのような**更新**をおこなったか知れる！

> この差分を保存するときに使うのがコミット！！

---

<!--
_class: body
-->

# コミットってなんだ？

差分を記録するための操作 = コミット

![](img/commit.svg)

---

<!--
_class: body
-->

# コミットが集まると..!?

<div class="split">
<div>
  コミットは、
  <ul>
    <li>ハッシュ
    <li>コミットの作成者
    <li>コミット日時
    <li>コミットメッセージ
  </ul>
  が保存される。<br><br>

つまり、これを続けるといい感じに情報が**時系列**でつながる

</div>
<img src="img/version_control_system_enable.svg">
</div>

---

<!--
_class: body
-->

# コンフリクトとは

---

<!--
_class: body
-->

# Git と Github の違い

---

# 実際に使ってみよう！

---
