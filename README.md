# AlphaCamp_Data & AI - RecSys
## Session1: Rule-based Recommendation Algorithm Implementation
* Reference: AC-Collegaues - Ana(yuchiahung) [Link](https://github.com/yuchiahung/data-course-sample/blob/main/hw1_Ana.ipynb)
* What is Rule-based Recommendation Algorithm

* How it works
* Results
## Session2: Content-based Recommendation Algorithm Implementation
* What is Content-based Recommendation Algorithm
Content-based Recommendation is the model that recommend users new products based on its preference or historical purchasements.
* How it works
1. 藉由語意分析套件(`nltk`)先將產品分析出關鍵字, 並濾除無意義字 (縮小後續矩陣記憶體的使用)
2. 將各產品關鍵字轉換為TF-IDF矩陣並以壓縮矩陣方式儲存(節省記憶體)
3. 量化指標為:cosine_similarity，可藉此分析產品近似程度。
* Results
1. AMZON All_beauty 使用者購買資料不足，並無顯見的進步。
## Session3: Collaborative-based Recommendation Algorithm Implementation
* What is Collaborative-based Recommendation Algorithm
* How it works
* Results
