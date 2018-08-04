# SimpleWebVR_Unity
MozillaのWebVRAseet(https://assetstore.unity.com/packages/templates/systems/webvr-assets-109152)を解析する

・新規プロジェクト作成

・WebVRAssetをImport

・WebVRシーンを開く

・重いのでDesertEnvironment無効化

・床が欲しいのでPlane追加

・AddScene,Switch Platform

・Build!!出来ない……

# 一回出来たのはなぜか

スクリプトで言えば、

WebVRManager,WebVRCamera,FreeFlightController

の3つ

後は、UnityEditor上の表のインスペクタを弄ったくらいしかしていない記憶

DefaultHeightとか、TrackingSpaceとかは触った（けどそこまで効果は無い模様）

# 実験
MainCameraを無効化してみると、VR化した時にOculusGo上で固まる

何故かまた出来た…、OculusGoをPCと接続した状態か否かが関係ある…？
