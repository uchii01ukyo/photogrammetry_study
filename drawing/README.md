# Contents
+ `convert_parameter.py`
    + 入力した静止画に対して、明るさとコントラストを変更した静止画を出力する
    + (明るさとコントラスの設定値はコード内で設定します)
    + 入力：../capture/captureにあるJPG/PNGファイル
    + 出力：./outputにJPG形式で出力
    + 注意：photogrammetryにおいて画像の明暗やコントラストの変化は大した効果を与えません
+ `convert_movie_picture.py`
    + 入力した動画を静止画に変換して出力（指定した時間分）
    + (変換する時間はコード内で指定します)
    + 入力：../capture/captureにあるMP4ファイル
    + 出力：./pictureにJPG形式で出力
+ `convert_movie_picture_bara.py`
    + 入力した動画を静止画に変換して出力（指定したフレームの前後１０フレーム分）
    + (フレームの指定は動画ごとにコード内でします)
    + 入力：../capture/captureにあるMP4ファイル
    + 出力：./pictureにJPG形式で出力

# Author
Uchii Ukyo(https://github.com/uchii01ukyo)