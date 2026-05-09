## 概要
Raspberry Pi Zero 2 WをIntel Edisonサイズに収めるプロジェクトです。  
Raspberry Pi Zero 2 Wから部品をすべて移植することで作成できます。  
かなり適当な設計なので参考程度にしてください。
## 回路説明
USBでPCに接続する瞬間にJP2をオープンにすることでeMMCの電源を切断できるので、USBBOOTでeMMCへ書き込めるようになります。  
## 参考
部品名はこちらのリポジトリと同じにしています。↓  
https://github.com/iocapa/reverse-raspberrypi-zero-2w-schematic  
また、シンボルなどはこちらのリポジトリのものをKicad用に変換して使用しています。↓  
https://github.com/jonny12375/rp3a0
