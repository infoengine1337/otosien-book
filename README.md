# otosien-book

音MAD製作において便利な機能をつめこんだノートブックです  

現行バージョンはv1.1です。  

具体的には
 - 最高画質&fpsダウンロード (Youtube/ニコニコ/Twitter等に対応)
 - 互換性の高い動画形式に変換 (H.264 + AAC 大抵のソフトなら読み込める)
 - 動画から音声を抜き出し(mp3/wavに対応)
 - BGMのみ抽出・声の抽出・ドラム抽出・カラオケ作成
 - 音声ファイルのMIDI変換
 - 動画の高画質/高解像度化
 - 透過素材作成

があります。

利用しているプロジェクトおよび技術は、
 - 動画ダウンロード...[yt-dlp](https://github.com/yt-dlp/yt-dlp)
 - 動画形式変換, mp3/wav形式への変換...[ffmpeg](https://github.com/FFmpeg/FFmpeg)
 - BGM除去・声の抽出...[Demucs v3](https://github.com/facebookresearch/demucs) と[spleeter](https://github.com/deezer/spleeter)
 - MIDI変換...[basic-pitch](https://github.com/spotify/basic-pitch)
 - 動画の高画質/高解像度化...[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
 - 透過素材作成...[anime-segmentation](https://github.com/SkyTNT/anime-segmentation)

 です。

 使い方動画の方も合わせてご利用ください。  
 [使い方講座動画](https://www.nicovideo.jp/watch/sm41054978)  

 近いうちにブログ記事を公開します。
 ノイズ除去機能も追加しようと思っているのですが、どの技術を選定するかがまだ決まっていません。  

多少UIが使いづらいため、ご要望があればもう少し改良します。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/infoengine1337/otosien-book/blob/master/otosien_book.ipynb)