# ykh_vci
[製作中]YOKOHA Vorbis Comment Inspector from MinatsukiTone -FLACファイルのVCからメタデータをパースします-  
## How to use  
Fileとしてロードさせると、認識子からFLACかどうか判定します。  
データが取れると配列で返されます。取れないときはnaというキーが入った仮の配列が戻されます。  
エラーが起きても、throwはしません。コンソールメッセージでエラーの内容は確認可能です。  
## Origin  
https://github.com/yokonoha/MinatsukiTone  
### SAMPLE  
```
{
    "TRACKNUMBER": [
        "1"
    ],
    "TITLE": [
        "Cumulative Hallucinations -累積的幻覚-"
    ],
    "ALBUMARTIST": [
        "YOKORERA"
    ],
    "ARTIST": [
        "YOKORERA"
    ],
    "COMPOSER": [
        "住保栖樹"
    ],
    "DATE": [
        "2021-12-23"
    ],
    "ALBUM": [
        "Your Decision"
    ],
    "GENRE": [
        "J-Pop"
    ],
    "ALBUMSORT": [
        "Y O U R  D E C I T I O N"
    ],
    "TOTALTRACKS": [
        "12"
    ],
    "DISCTOTAL": [
        "1"
    ],
    "DISCNUMBER": [
        "1"
    ],
    "ALBUMARTISTSORT": [
        "Y O K O R E R A"
    ],
    "TITLESORT": [
        "C U M U L A T I V E  H A L L U C I N A T I O N S - ル イ セ キ テ キ  ゲ ン カ ク -"
    ],
    "ARTISTSORT": [
        "ヨ コ レ ラ"
    ],
    "LYRICS": [
        "深い霧に包まれて 呑まれてしまいそうな\n晩秋夜 彷徨う私\n黒の行く先へ ただ突き進む\nあれからどれ程たっただろう\n何もかもが 想像の斜め下\nうまくいかない私だけど\n濃霧の裏は きっと希望にあふれてる\nSo Let's DIVE into the Fog!\n些細な事でも Alright!\n怖がってないで ほら私の手を握って\n今突き抜けるよ Fly through the fog\n...."
    ]
}
```
## License  
Apache 2.0  
   Copyright 2026 横茶横葉/Y.Yokoha  

   Licensed under the Apache License, Version 2.0 (the "License");  
   you may not use this file except in compliance with the License.  
   You may obtain a copy of the License at  
  
       http://www.apache.org/licenses/LICENSE-2.0  
  
   Unless required by applicable law or agreed to in writing, software  
   distributed under the License is distributed on an "AS IS" BASIS,  
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  
   See the License for the specific language governing permissions and  
   limitations under the License.  
