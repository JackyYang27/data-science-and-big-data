# data-science-and-big-data

Big_Data_Project.ipynb 
本檔案主要是在比較書卷獎的學生與非書卷獎學生選課的差異。


chi-test(no use).ipynb (不太重要的東西)
本檔案主要在比較書卷獎學生與5%-25%、26%-50%、51%-75%...等不同layer的學生之差異。
然而經過調查後發現此差異時數不顯著(P值都很大)。

compare_between_required_and_elective.ipynb
本檔案為計算選修課和必修課對於卷哥所造成之影響。
經過調查後發現，有54.3%的書卷獎得主，選修、通識課的平均成績較必修課之成績高。

(1) departments = ['資訊管理學系', '文學院學士班', '中國文學系', '英美語文學系', '法國語文學系',
    '理學院學士班', '物理學系', '數學系', '化學學系', '光電科學與工程學系',
    '工學院學士班', '化學工程與材料工程學系', '土木工程學系', '機械工程學系']
=> 在12個學期中，departments前5%的學生人數為2342個，其中，選修、通識課的平均成績較必修課之成績高的學生人數為1050個。

(2)  departments = ['企業管理學系', '財務金融學系', '經濟學系',
    '資訊電機學院學士班', '電機工程學系', '資訊工程學系', '通訊工程學系',
    '地球科學學院學士班', '地球科學學系', '大氣科學學系', '太空科學與工程學系',
    '客家語文暨社會科學學系', '生命科學系', '生醫科學與工程學系']
=> 在12個學期中，departments前5%的學生人數為2023個，其中，必修課分數大於選修和通識課的學生人數人數為945個。

(3)=>在12個學期中，全校前5%的學生人數為4365個，其中，必修課分數大於選修和通識課的學生人數人數為1995個。
必修課分數大於選修和通識課的學生人數占比45.7%，反之，
選修、通識課的平均成績較必修課之成績高的學生占比54.3%。

favor_or_not.ipynb
本檔案主要在比較書卷獎得主比較喜歡那些課、前5%與隨機抽取學生選課比例之比較。
最後運用文字雲圖進行書卷獎得主最喜歡之課程以及最不喜歡之課程的展示。

grade_distribution.ipynb
本檔案在分析成績分布與選課的關係。
其中我們展示出了該堂課期末平均成績的分佈區間
![image](https://github.com/JackyYang27/data-science-and-big-data/assets/134624274/456e2913-8b01-45b6-a7b8-3dfb858a3f89)


top_5__class_taking_all_year.ipynb
本檔案分析了全校大學部選修課的分數分布，與卷哥所修之大學部選修課分布之比較。

(1)使用grade_distribution，我們展示了大學部選修課期末平均成績的分佈區間，接著我們取得全校前5%卷哥的學號，取得它們所修的選修課之班級平均成績，以兩分為一個區間，將卷哥修課的班級平均成績，做成長條圖取得其分布。

(2)最終結果為，卷哥所修的選修課的平均分數，比全校選修課平均分數還低，而且長條圖視覺上展示出，卷哥得到好成績，與他們的選課策略無明顯關聯性。
