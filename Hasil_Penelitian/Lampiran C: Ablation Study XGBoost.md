# Ablation Study XGBoost

| Model yang Diuji | RMSE (Data Uji) | MAE (Data Uji) | Perubahan Performa (vs. Model Lengkap) \| RMSE | Perubahan Performa (vs. Model Lengkap) \| MAE |
| :--- | :--- | :--- | :--- | :--- |
| Model Lengkap (Semua Fitur) | 4.9877 | 4.0772 | - (Baseline) | - (Baseline) |
| Model tanpa Prevalensi Stunting_lag1 | 4.6558 | 3.4521 | (-) 0.3319 | (-) 0.6251 |
| Model tanpa IPM_lag1 | 4.8197 | 3.9303 | (-) 0.168 | (-) 0.1469 |
| Model tanpa Wasting_lag1 | 4.9333 | 3.9825 | (-) 0.5444 | (-) 0.0947 |
| Model tanpa kepadatanpenduduk_lag1 | 5.0736 | 4.0256 | (+) 0.0859 | (-) 0.0516 |
| Model tanpa ditolongMedis_lag1 | 4.7977 | 3.8956 | (-) 0.19 | (-) 0.1816 |
