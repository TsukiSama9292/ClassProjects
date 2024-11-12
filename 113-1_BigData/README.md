# 紀錄
## 當下情境
1. 113-1學年度(大三上)
2. 大數據分析與智慧運算期中專案
3. 題目:決策樹_全類別型條件_類別型目標屬性(老師給予題目,可選)
4. 課程教學皆是sklearn(機器學習) , 但本人刻意使用深度學習撰寫分析模型
## 程式碼簡單介紹
- [決策樹_全類別型條件_類別型目標屬性](./ANNs/Colab.ipynb) , 深度學習框架為 Pytorch , 有`軟決策樹模型`, `測試模型(單層)`, `自注意力模型` 三種深度學習模型 , 後面兩個模型架構 詹朝成 同學有參與
## 使用 Docker
```bash
cd 113-1_BigData
docker builder prune -a
docker build --pull -f dockerfile -t bigdata .
docker-compose up -d
cd ..
```