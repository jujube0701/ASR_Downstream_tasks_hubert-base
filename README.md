# 聲音特徵提取與分類專案

本專案包含多個常見聲音資料集的特徵提取與分類腳本，適用於呼吸聲、環境聲、語者辨識、關鍵詞辨識等任務。

## 資料夾說明
- `esc50_feature_fc`：ESC-50 環境聲分類特徵提取與分類腳本
- `icbhi_feature_fc`：ICBHI 呼吸聲資料集特徵提取與分類腳本
- `key_word_spotting`：關鍵詞辨識特徵提取腳本
- `nsynth_feature_fc`：NSynth 樂器聲資料集特徵提取腳本
- `speaker_recognition`：語者辨識特徵提取腳本
- `urbansound8k_feature_fc`：UrbanSound8K 環境聲資料集特徵提取腳本

## 注意事項
- 本專案**不包含任何 .pt 檔案**（模型或特徵檔），僅包含原始程式碼。
- 若需訓練或測試，請自行運行腳本產生所需的 .pt 檔案。

## 使用方式
1. 安裝相依套件（建議使用 requirements.txt 或根據腳本需求安裝）
2. 依照各資料夾內說明運行特徵提取或分類腳本

---
如有問題歡迎提 issue！ 