# AlphaCamp_Data & AI - RecSys

## Session1: Rule-based Recommendation Algorithm Implementation
* Reference: AC-Collegaues - Ana(yuchiahung) [Link](https://github.com/yuchiahung/data-course-sample/blob/main/hw1_Ana.ipynb)
* [Link](https://github.com/phwangktw/data-course-sample/blob/main/Session1_Rule-based_Recommendation_Algorithm.ipynb)
* What is Rule-based Recommendation Algorithm

Content-based Recommendation is the model that recommend users new products based on hard-coding rules
* How it works
1. 以熱門產品為優先推送的產品，而熱門的定義可為「高評論數」、「高評價」。
2. 因美妝商品去高度流行性，熱門商品的選擇尚須考慮不同時間區間。
* Results
1. 最終預測分數約為0.09

## Session2: Content-based Recommendation Algorithm Implementation
* [Link](https://github.com/phwangktw/data-course-sample/blob/main/Session2_Content_based_Recommendation_Algorithm_ipynb.ipynb)
* What is Content-based Recommendation Algorithm

Content-based Recommendation is the model that recommend users new products based on its preference or historical purchasements.
* How it works
1. 藉由語意分析套件(`nltk`)先將產品分析出關鍵字, 並濾除無意義字 (縮小後續矩陣記憶體的使用)
2. 將各產品關鍵字轉換為TF-IDF矩陣並以壓縮矩陣方式儲存(節省記憶體)
3. 量化指標為:cosine_similarity，可藉此分析產品近似程度。
* Results
1. AMZON All_beauty 使用者購買資料不足，並無顯見的進步。

## Session3: Collaborative-based Recommendation Algorithm Implementation
* Links:
 1. [Link:User-based](https://github.com/phwangktw/data-course-sample/blob/main/Session3_Collaborative-based(user-based)_Recommendation_Algorithm.ipynb)
 2.  [Link:Item-based](https://github.com/phwangktw/data-course-sample/blob/main/Session3_Collaborative-based(item-based)_Recommendation_Algorithm.ipynb)
 3.  [Link:Surprise package](https://github.com/phwangktw/data-course-sample/blob/main/Session3_Collaborative-based(surprise_package)_Recommendation_Algorithm.ipynb)
* What is Collaborative-based Recommendation Algorithm
* How it works
* Results
<br>

| Method | Score | Improvement |
| ----------- | ----------- |----------- |
| Rule-based | 0.0983 |  base case|
| User-based  | 0.0983 | 0% |
| Item-based    | 0.0983        |    0%         |
| Surprise      | 0.1000        |    1.7%       |
