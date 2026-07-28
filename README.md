gasBaseUrl 正式版與開發版切換機制：
預設指向 /exec 正式發布版網址。
支援透過 URL 參數 ?env=dev 或 ?dev=1 自動切換至 /dev 開發版網址，同時會記憶至 localStorage。
若要切換回正式版，亦可使用 ?env=exec。
