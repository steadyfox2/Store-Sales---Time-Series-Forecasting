# 🏪 Store-Sales
## Kaggle data Store Sales - Time Series Forecasting Analysis

In this competition, you will predict sales for the thousands of product families sold at Favorita stores located in Ecuador. The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models.
# EDA

## Oil Price

![newplot](https://user-images.githubusercontent.com/114843451/228499762-5860d291-4584-4701-8808-a0d835bdf1ae.png)

우선, Oil가격이다. 에콰도르는 유가가 경제에 미치는 영향이 높기 때문에, 유가 가격이 매우 중요하다. 본 그래프의 데이터는 WTI 텍사스산 원유 가격 그래프이다.
일반적으로 유가가 오르면 소비재 가격이 오르는데, 에콰도르는 산유국이기 때문에 유가가 내려가면 국가 재정이 부족해진다. 경제 분석이라서 그런지 분석이 쉽진 않다.
일단, 유가가 가격이 오르면 소비재 가격이 내려간다고 가정한다.

## Transaction

![newplot](https://user-images.githubusercontent.com/114843451/228500993-290421de-c0b9-4e97-ac38-b2392d0cb68a.png)

거래량은 12월이 가장 많은 것으로 보인다. 아무래도 12월에 사람들이 소비를 많이 하는 것으로 예상이 된다. 두 번재는 5월인데 5월에는 소폭 상승하는데 그쳤다.

