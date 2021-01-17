# final-exam-106370725
get_string_features:提取檔案的字做病毒特徵訓練
scan_file:掃描文件，判斷是良性還是惡性
如果是惡性,train_detector:利用隨機樹RandomForest訓練detetor。cv_evaluate：以scores和test_y分辨為善意或惡意檔案畫出ROC curves圖
驗證評估模型最後產生的圖

靈敏度設定越高得到的假陽性（誤為惡意程式）越多，但會提高檢測率 ，當靈敏度設定越低，檢測的準確率會越高

[心得](#心得

第一次修外系的課程，學習起來有點吃力
所以詢問了一些相關科系的朋友讓自己更了解一些資訊



謝謝老師用心教導
祝新年快樂事事順心
