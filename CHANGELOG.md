# 版本紀錄

## [0.1.0-alpha.3](https://github.com/SamChengYo/desktop-pet-releases/releases/tag/v0.1.0-alpha.3) · 2026-10-06

- 修復首次下載生成 runtime 的 Windows ZIP 占用問題；已完成公開 runtime 下載、驗證、權重下載、CPU 生成與匯出。
- 新增明確標示的原圖外觀（2D），保留輸入圖片外觀與封閉白色區域。
- 重新設計設定與聊天介面、統一控件樣式、即時角色縮圖。
- 3D 生成修正座標、三角形朝向與材質；可保留原圖正面色彩，側面與背面仍可能失真。
- 實測公開 CI 安裝檔、啟動新版提示、繼續舊版、簽章新版升級與舊版回復。

## [0.1.0-alpha.2](https://github.com/SamChengYo/desktop-pet-releases/releases/tag/v0.1.0-alpha.2) · 2026-10-06

專用 GitHub App 完成跨 repo 的 Windows CI 建置、測試、簽章與自動發布。此版本的首次 runtime 下載問題已在 alpha.3 修復，請使用後續版本。

## [0.1.0-alpha.1](https://github.com/SamChengYo/desktop-pet-releases/releases/tag/v0.1.0-alpha.1) · 2026-10-05

首次功能 prerelease：透明 3D 桌寵、三類角色與骨架、近似綁骨與匯出、動作、LiteLLM 串流、多步 Agent、原生授權、緊急停止、DPAPI、安裝與簽章更新，以及可選 CPU／LiteLLM runtimes。

目前仍有未完成或未驗收項目，見 [功能狀態](FEATURE-STATUS.md)。
