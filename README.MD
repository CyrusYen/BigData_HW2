# Homework_2

### 參數調整步驟
(1) 確定學習速率和理想的決策樹數量
(2) 調整 max_depth 和 min_weight 參數
(3) 調整 gamma 參數
(4) 調整 subsample 和 colsample_bytree
(5) regularization 參數調整
(6) 嘗試降低學習速率

### 得出最佳參數組合
參數組合如下:

     learning_rate =0.01,
     n_estimators=5000,
     max_depth=4,
     min_child_weight=6,
     gamma=0,
     subsample=0.8,
     colsample_bytree=0.8,
     reg_alpha=0.005,
     objective= 'binary:logistic',
     nthread=4,
     scale_pos_weight=1,
     seed=27