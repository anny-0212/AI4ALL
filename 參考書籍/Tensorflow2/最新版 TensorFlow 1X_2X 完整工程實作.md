#
```
極詳細 + 超深入：最新版 TensorFlow 1.x/2.x 完整工程實作
李金洪 深智數位 2020-01-20
https://www.tenlong.com.tw/products/9789865501136?list_name=srh
```

```
► 75個工業及商用專案的完整實作
►在Windows/Linux下安裝Anaconda及GPU、CUDNN的完整介紹
►大量Transfer Learning的預載入模型說明
►Tensorflow的專屬資料集格式
►TF-Hub retrain或是fine-tune完整的預載入模型
►利用tf.estimator及tf.keras訓練模型的完整過程
►用Tensorflow做離散及連續資料的特徵工程
►不再只是單純的CNN，用膠囊網路做更準確的圖形辨識
►不只RNN，還有GRU及Attention機制、SRU、QRNN及Transformer機制
►自己動手做YOLOV3 Darknet
►最完整的Normalization說明，包括Batch Norm、Switchable Norm
►GAN大全，包括DeblurGAN及AttGAN
►CS612照片加工的AI基礎
►製作Tensorflow的模型完整說明
►在樹莓派、iPhone、Android上佈署Tensorflow的模型
```
```
第一篇　準備
01 學習準備
1.1 TensorFlow 能做什麼 
1.2 學習TensorFlow 的必備知識
1.3 學習技巧：跟讀程式
1.4 如何研讀本書 
02 架設開發環境
2.1 準備硬體環境
2.2 下載及安裝Anaconda 
2.3 安裝TensorFlow 
2.4 GPU 版本的安裝方法
2.5 測試顯示卡的常用指令
2.6 TensorFlow 1.x 版本與2.x 版本共存的解決方案
03 實例1：用AI 模型識別影像是桌子、貓、狗，還是其他
3.1 準備程式環境並預訓練模型
3.2 程式實現：初始化環境變數，並載入ImgNet 標籤 
3.3 程式實現：定義網路結構 
3.4 程式實現：載入模型進行識別 
3.5 擴充：用更多預訓練模型完成圖片分類工作
第二篇　基礎
04 用TensorFlow 製作自己的資料集
4.1 快速導讀
4.2 實例2：將模擬資料製作成記憶體物件資料集
4.3 實例3：將圖片製作成記憶體物件資料集
4.4 實例4：將Excel 檔案製作成記憶體物件資料集
4.5 實例5：將圖片檔案製作成TFRecord 資料集
4.6 實例6：將記憶體物件製作成Dataset 資料集
4.7 實例7：將圖片檔案製作成Dataset 資料集
4.8 實例8：將TFRecord 檔案製作成Dataset 資料集 
4.9 實例9：在動態圖中讀取Dataset 資料集
4.10 實例11：在不同場景中使用資料集
4.11 tf.data.Dataset 介面的更多應用
05 10 分鐘快速訓練自己的圖片分類模型
5.1 快速導讀函數庫
5.2 實例12：透過微調模型分辨男女
5.3 擴充：透過攝影機即分時辨男女
5.4 TF-slim 介面中的更多成熟模型
5.5 實例13：用TF-Hub 函數庫微調模型以評估人物的年齡
5.6 歸納 
5.7 練習題
06 用TensorFlow 撰寫訓練模型的程式
6.1 快速導讀
6.2 實例14：用靜態圖訓練一個具有儲存檢查點功能的回歸模型 
6.3 實例15：用動態圖（eager）訓練一個具有儲存檢查點功能的
回歸模型
6.4 實例18：用估算器架構訓練一個回歸模型
6.5 實例20：將估算器程式改寫成靜態圖程式
6.6 實例21：用tf.layers API 在動態圖上識別手寫數字 
6.7 實例22：用tf.keras API 訓練一個回歸模型 
6.8 實例25：用tf.js 介面後方訓練一個回歸模型 
6.9 實例26：用估算器架構實現分散式部署訓練 
6.10 實例27：在分散式估算器架構中用tf.keras 介面訓練ResNet
模型，識別圖片中是橘子還是蘋果
6.11 實例28：在T2T 架構中用tf.layers 介面實現MNIST 資料
集分類 
6.12 實例29：在T2T 架構中，用自訂資料集訓練中英文翻譯模型 
6.13 實例30：將TensorFlow 1.x 中的程式升級為可用於2.x 版本的
程式 
第三篇　進階
07 特徵工程-- 會說話的資料
7.1 快速導讀
7.2 實例31：用wide_deep 模型預測人口收入
7.3 實例32：用弱學習器中的梯度提升樹演算法預測人口收入
7.4 實例33：用feature_column 模組轉換特徵列
7.5 實例34：用sequence_feature_column 介面完成自然語言處理
工作的資料前置處理工作 
7.6 實例35：用factorization 模組的kmeans 介面分群COCO資料集
中的標記框
7.7 實例36：用加權矩陣分解模型實現以電影評分為基礎的推薦系統
7.8 實例37：用Lattice 模組預測人口收入 
7.9 實例38：結合知識圖譜實現以電影為基礎的推薦系統 
7.10 可解釋性演算法的意義
08 卷積神經網路（CNN）-- 在影像處理中應用最廣泛的模型
8.1 快速導讀 
8.2 實例39：用膠囊網路識別黑白圖中服裝的圖案
8.3 實例41：用TextCNN 模型分析評論者是否滿意 
8.4 實例42：用帶注意力機制的模型分析評論者是否滿意
8.5 實例43：架設YOLO V3 模型，識別圖片中的酒杯、水果
等物體
8.6 實例44：用YOLO V3 模型識別門牌號 
8.7 實例45：用Mask R-CNN 模型定位物體的像素點
8.8 實例46：訓練Mask R-CNN 模型，進行形狀的識別
09 循環神經網路（RNN）--處理序列樣本的神經網路
9.1 快速導讀 
9.2 實例47：架設RNN 模型，為女孩產生英文名字
9.3 實例48：用帶注意力機制的Seq2Seq 模型為圖片增加內容描述
9.4 實例49：用IndRNN 與IndyLSTM 單元製作聊天機器人
9.5 實例50：預測飛機引擎的剩餘使用壽命
9.6 實例51：將動態路由用於RNN模型，對路透社新聞進行分類 
9.7 實例52：用TFTS 架構預測某地區每天的出生人數
9.8 實例53：用Tacotron 模型合成中文語音（TTS）
第四篇　進階
10 產生式模型--能夠輸出內容的模型
10.1 快速導讀 
10.2 實例54：建置DeblurGAN 模型，將模糊相片變清晰
10.3 實例55：建置AttGAN 模型，對照片進行加鬍子、加頭簾、
加眼鏡、變年輕等修改
10.4 實例57：用RNN.WGAN 模型模擬產生惡意請求 
11 模型的攻與防-- 看似智慧的AI 也有脆弱的一面
11.1 快速導讀
11.2 實例58：用FGSM 方法產生樣本，並攻擊PNASNet 模型，讓
其將「狗」識別成「碟子」
11.3 實例59：擊破資料增強防護，製作抗旋轉對抗樣本
11.4 實例60：以黑箱方式攻擊未知模型 
第五篇　實戰--深度學習實際應用
12 TensorFlow 模型製作--一種功能，多種身份
12.1 快速導讀模組
12.2 實例61：在原始程式與檢查點檔案分離的情況下，對模型進
行二次訓練
12.3 實例62：匯出/ 匯入凍結圖檔案
12.4 實例63：逆向分析凍結圖檔案
12.5 實例64：用saved_model 模組
匯出與匯入模型檔案
12.6 實例65：用saved_model_cli工具檢視及使用saved_model模型 
12.7 實例66：用TF-Hub 函數庫匯入、匯出詞嵌入模型檔案
13 部署TensorFlow 模型--模型與專案的深度結合
13.1 快速導讀
13.2 實例67：用TF_Serving 部署模型並進行遠端使用
13.3 實例68：在Android 手機上識別男女
13.4 實例69：在iPhone 手機上識別男女並進行活體檢測
13.5 實例70：在樹莓派上架設一個目標檢測器 
14 商業實例--科技源於生活，用於生活
14.1 實例71：將特徵比對技術應用在商標識別領域
14.2 實例72：用RNN 抓取蠕蟲病毒
14.3 實例73：迎賓機器人的技術重點—體驗優先 
14.4 實例74：以攝影機為基礎的路邊停車場專案
14.5 實例75：智慧冰箱產品—硬體成本之痛
```
