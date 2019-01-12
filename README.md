# ARKitとは？
AppleのAR(Augmented Reality) のアプリ作成用フレームワーク。  
VIO(Visual-Inertial Odometry)：カメラやセンサから環境マッピング、自己位置推定を行う。  
[AppleのARKitサイト](https://developer.apple.com/jp/arkit/)  

- ARKit 1.0：水平面の認識
- ARKit 1.5：垂直面、画像の認識
- ARKit 2.0：AR空間の永続化、ARの共有、3Dオブジェクトの検出、画像トラッキング

動作環境：iOS11以降のA9プロセッサ以上のプロセッサを搭載したiPhone/iPad  
ここではARKit2.0を対象とし、iOS12以上のiPhone/iPad、Xcode10.0以上を搭載したMacを使用。

# デモ集
## [DetectHPlane](detect_hplane.md)
水平面を認識し、球を配置する。
