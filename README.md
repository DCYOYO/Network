# Cisco Packet Tracer 繁體中文語言包安裝說明

本資料夾提供的 `Traditional Chinese_cht.ptl` 是 Cisco Packet Tracer 的繁體中文介面語言包。

## Windows 安裝步驟

1. 關閉 Cisco Packet Tracer。
2. 開啟 Packet Tracer 的安裝資料夾；常見位置如下：

   ```text
   C:\Program Files\Cisco Packet Tracer 版本號\languages
   ```

   例如：

   ```text
   C:\Program Files\Cisco Packet Tracer 9.0.0\languages
   ```

3. 將 `Traditional Chinese_cht.ptl` 複製到 `languages` 資料夾。
   - 若 Windows 要求系統管理員權限，請選擇「繼續」。
4. 啟動 Cisco Packet Tracer。
5. 依序選擇：`Options` → `Preferences` → `Interface`。
6. 在 **Select Language**（或 **Language**）下拉選單中選取 `Traditional Chinese_cht.ptl`。
7. 按下 **Change Language**，確認提示訊息後重新啟動 Packet Tracer。

重新開啟後，介面即會顯示為繁體中文。

## 還原英文介面

在 Packet Tracer 的 `Options` → `Preferences` → `Interface` 中，將語言改回 `default.ptl`，按下 **Change Language** 後重新啟動即可。

## 常見問題

### 下拉選單沒有出現語言包

- 確認檔名仍是 `Traditional Chinese_cht.ptl`，而不是 `Traditional Chinese_cht.ptl.ptl` 或 `.qm`。
- 確認檔案放在 Packet Tracer 安裝資料夾中的 `languages` 資料夾，而非使用者文件資料夾。
- 完全關閉並重新開啟 Packet Tracer 後再查看一次。

### 安裝後介面沒有改變

選取語言後必須按 **Change Language**，並重新啟動程式才會生效。

