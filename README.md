# otosien-book

音製作において便利な機能をつめこんだノートブックです  

現行バージョンはv1.1です。  

具体的には
 - Youtubeより最高画質&フレームレートでダウンロード
 - 他サイトと互換性のある動画形式(H264 + AAC)に変換
 - mp3,wav(PCM 24bit)形式に変換
 - 音源分離によるBGM除去・声の抽出(Demucs v3, spleeterの二種類を利用)
 - 動画高解像度化(Real-ESRGANを利用、デフォルトで二倍の解像度)
 - 対象抽出による透過素材作成(anime-segmentationを利用)

があります。
多少UIが使いづらいため、ご要望があればもう少し改良します。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/infoengine1337/otosien-book/blob/master/otosien_book.ipynb)