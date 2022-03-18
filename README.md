# PoseRecorder
    1.動作記錄完之後，Data會存在 /ModSomatosensory_Data/StreamingAssets/MovementData/(動作名稱)，此時Data還很肥
    2.再將Data自行拉至各專案的 /StreamingAssets/Posture/(動作名稱) 底下
    3.切換到PoseViewerScene並將場景跑起來
    4.Game視窗中的兩個下拉式選單只是用來切換Data的，實際觀看還是在Scene視窗裡  (因為有些動作的位置不一樣，而且在Scene視窗比較好喬角度)
    5.Data修改在PoseViewerMain.cs 裡的98行 EditDataTest(...)
    6.承(5)，這邊比較不方便的是每一次調整都要把場景重新Run
    7.調整完之後，按下儲存按鈕，檔案會存在 "<Unity專案名稱>/MyPostureTemp/<動作名稱>/<日期>/<剛剛錄的Data>"。
    8.再將(7)的Data放回(2)提到的資料夾底下
