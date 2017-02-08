
# これは何ですか？

これは[Blender]（http：//www.blender.org）のカメラと[ビデオプロジェクタ校正]（https://github.com/stuffmatic/blam/wiki/Video-Projector-Calibration）ツールキットです。 Pythonで書かれたアドオンの形式。写真に基づいたモデリングを容易にします。

開発の進捗状況のアップデートを入手するには、定期的にここでチェックしてください。または[Twitterで私に従ってください]（http://www.twitter.com/stuffmatic）。

バグは[こちら]（https://github.com/stuffmatic/blam/issues）で報告することができます。

# 入門

1. [最新のリリースをダウンロード]（http://stuffmatic.github.com/）（または最新のgitリビジョンを入手する）（https://github.com/stuffmatic/blam/blob/master/src/blam。 py））。
2. [インストール]（http://wiki.blender.org/index.php/Doc:2.6/Manual/Extensions/Python/Add-Ons）
3. [紹介ビデオ]（https://vimeo.com/35153437）、[このチュートリアルビデオ]（https://vimeo.com/35421849）、[ユーザーガイドを読む]（https：// github .com / stuffmatic / blam / wiki / User％27s-ガイド）。

# 参加する

関与する最も簡単な方法は、アドオンのテストと[バグレポートの提供]（https://github.com/stuffmatic/blam/issues）です。 [このblenderartistsスレッド]（http://blenderartists.org/forum/showthread.php?243370-Addon-Camera-matching-add-on-for-modeling-based-on-photographs&highlight=blam+camera）は良い場所です機能の提案など、他の種類の入力を提供する

コーディング面でのサポートに興味がある場合は、教えてください。

# 取得する

*焦点距離とカメラ方位の推定は、[単一画像からのカメラキャリブレーションと粗い3D再構成のためのバニッシングポイントの使用]（http://www.irisa.fr/prive/kadi/Reconstruction/paper.ps.gz）に基づいています。 E. Guillou、D. Meneveaux、E. Maisel、K. Bouatouch。
*矩形ベースのジオメトリの3次元再構成のアルゴリズムは、[矩形の遠近法を使用して内在および外在カメラパラメータを復元する]（http://www.bmva.org/bmvc/1995/bmvc- 95-017.pdf）、TN Tan、GD SullivanおよびKD Baker。
* BLAMは、純粋なPythonの線形代数ルーチン（ここではhttp://users.rcn.com/python/download/python.htm）を使用して、線形方程式のシステムの最小二乗解を実行し、次のような外部パッケージには依存しません。サイフィ。

ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー

ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーーー
# What is this?

This is BLAM, a camera and [video projector calibration](https://github.com/stuffmatic/blam/wiki/Video-Projector-Calibration) toolkit for [Blender](http://www.blender.org) in the form of an add-on, written in python, that facilitates modeling based on photographs.

To get development progress updates, either check back here regularly or [follow me on Twitter](http://www.twitter.com/stuffmatic).

Bugs can be reported [here](https://github.com/stuffmatic/blam/issues). 

# Getting started 

1. [Download the latest release](http://stuffmatic.github.com/) (or [get the latest git revision](https://github.com/stuffmatic/blam/blob/master/src/blam.py)).
2. [Install](http://wiki.blender.org/index.php/Doc:2.6/Manual/Extensions/Python/Add-Ons)
3. Check out the [introduction video](https://vimeo.com/35153437), [this tutorial video](https://vimeo.com/35421849) and [read the user's guide](https://github.com/stuffmatic/blam/wiki/User%27s-guide).

# Getting involved

The easiest way to get involved is testing the add-on and [providing bug reports](https://github.com/stuffmatic/blam/issues). [This blenderartists thread](http://blenderartists.org/forum/showthread.php?243370-Addon-Camera-matching-add-on-for-modeling-based-on-photographs&highlight=blam+camera) is a good place to provide other kinds of input, like feature suggestions

If you're interested in helping out on the coding side, let me know. 

# Getting nerdy

* The focal length and camera orientation estimation is based on [Using Vanishing Points for Camera Calibration and Coarse 3D Reconstruction from a Single Image](http://www.irisa.fr/prive/kadi/Reconstruction/paper.ps.gz) by E. Guillou, D. Meneveaux, E. Maisel, K. Bouatouch. 
* The algorithm for 3D reconstruction of rectangle based geometry is an extension of the AC algorithm described in [Recovery of Intrinsic and Extrinsic Camera Parameters Using Perspective Views of Rectangles](http://www.bmva.org/bmvc/1995/bmvc-95-017.pdf) by T. N. Tan, G. D. Sullivan and K. D. Baker. 
* BLAM does least squares solution of systems of linear equations using the pure python linear algebra routines available [here](http://users.rcn.com/python/download/python.htm) and does not depend on external packages such as scipy. 
