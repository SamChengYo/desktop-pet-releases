Desktop Pet Agent 0.1.0-alpha.1 — Windows 11 x64 prerelease

可使用功能：透明 3D 桌寵、三類原創角色與骨架、拖曳與縮放、系統匣、設定、360° 預覽、近似自動綁骨與 GLB 匯出、動作播放、LiteLLM 串流與 C# 多步 Agent、原生權限檢查、暫停與恢復、緊急停止、任務紀錄、DPAPI 金鑰保護、可選 CPU 生成 runtime。

每次啟動自動檢查更新；使用者可選擇安裝新版或繼續目前版本。更新資訊由 RSA 簽章驗證，下載檔案由 SHA-256 驗證。

已在 Windows 11 26200 實测透明渲染與原生 UIA 授權／撤銷／緊急停止。TripoSR CPU 已完成簡化物件、人形與四足測試。角色背面與綁骨品質需要使用者預覽與調整。

限制：GPU 生成（含 2／3 GB 顯存）、Windows 10、臉部動畫、一般第三方動畫重定向與乾淨 Windows VM 更新回復尚未驗收。遠端生成介面使用自訂 multipart→GLB 協議，需服務端提供相容 endpoint。AI 對話需自行設定 LiteLLM gateway 或 provider 憑證。

此版本沒有 Windows Authenticode 簽章；請保留作業系統防護。這是功能 prerelease，並非全部需求已驗收的正式版。
