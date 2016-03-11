.. 翻訳者:Jun Okazaki

===========================
入門
===========================
このドキュメンテーションはKivyのGetting Started » A first Appを日本語訳したものです。  
https://kivy.org/docs/gettingstarted/framework.html


ウィジェトでない要素
==========================
.. csv-table:: 
  
	"Animationは、ウィジェットのプロパティ（サイズ/座標/中心等）を時間内に目標値に変更するために使用されます。様々なtransition機能が提供されています。ウィジェットをアニメーション化し、非常にスムーズなUIビヘイビアーを構築するためにそれらは使用することができます。",".. image:: https://kivy.org/docs/_images/gs-animation.gif"
	"Atlasは、すなわち、1枚の画像に複数のテクスチャをパッキング、テクスチャマップを管理するためのクラスです。これは、ロードされたイメージの数を減らすため、アプリケーションの起動を高速化することができます。
",".. image:: https://kivy.org/docs/_images/gs-atlas.png"
	"Clockは設定された時間間隔でジョブをスケジュールするために便利な方法を提供します。またkivyイベントループをブロックするsleep()、より好ましいです。これらの間隔のbeforeまたはafterに、OpenGLの描画命令に対して設定できますClockはまた、一緒にグループ化され、次フレームの前に、一度だけ呼ばれるtriggered eventsを作成する方法を提供します。","schedule_once() schedule_interval() unschedule() create_trigger()"
	"URLRequestは、コールバックとの結果と進捗状況を管理するイベントループをブロックする非同期リクエストに有用です。",""
 
