##Drawingbat 人臉辨識

 * 短期目標  
1. 辨識人臉在圖中位置  
2. 取得外圍輪廓   
3. 取得臉部輪廓   

###Face_focus
>參考 http://gogoprivateryan.blogspot.tw/2015/09/opencv-3-opencv-python-face-recognition.html   

利用 "haarcascade_frontalface_default.xml" 臉部辨識函式庫追蹤臉部  
已經成功可以追蹤臉部，有以下幾項問題等待修正
* 範圍需加大，方便DrawingBat取圖
* 有時候會誤判(影響不大)