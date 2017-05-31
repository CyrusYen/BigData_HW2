# Homework_2

## Xgboost
### 調整步驟
(1) 確定學習速率和理想的決策樹數量

(2) 調整 max_depth 和 min_weight 參數

(3) 調整 gamma 參數和 n_estimators

### 最佳參數組合
    
    max_depth = 5
    min_child_weight = 1
    gamma = 0.0
    n_estimators = 120
    
    
## GradientBoost
### 調整步驟
(1) 確定學習速率和理想的決策樹數量

(2) 調整 max_depth 和 min_samples_split 參數

(3) 調整 min_samples_leaf 參數和 n_estimators

### 最佳參數組合

    max_depth = 9
    min_samples_split = 200
    n_estimators = 200
    min_samples_leaf = 20