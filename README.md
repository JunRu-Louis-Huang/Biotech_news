# 目的任務
    為即時掌握產業脈動，使用爬蟲程式技術蒐集「國家生技醫療產業策進會（生策會）」網頁新聞

# 套件
    需另外安裝 Python 套件: Requests 及 PyQuery

# 結果
	○ 爬蟲程式輸入：使用者輸入自訂想取得的新聞天數參數，例如:使用者近4天，則輸入4
	○ 爬蟲程式輸出：
		- 輸出格式: CSV檔
		- 檔名客製化:抓取日期與新聞天數，例如：2021-03-21_4天內_生技醫療新聞.csv
		- 欄位內容：新聞日期、標題、媒體來源、新聞內容


# 補充

生技醫藥領域的中文新聞種類廣泛，有給一般民眾閱讀淺顯易懂的保健、衛教資訊，深如專業外文期刊發表或是研討會的彙整資訊等等。\
本案以中文資訊，做生技醫藥領域新聞的簡單爬蟲為主。\

如有需要，可參考其他相關生技醫藥領域的中文網站：
基因線上、各大學術電子專刊、、生醫觀點、科技新報、環球生技月刊、華人健康網、康健雜誌、鉅亨網、DIGITIMES......等

此程式以整合後的生策會新聞中獲取綜合性的新聞。\

每天都有大量資訊產出，太舊的消息可能不是我們想要知道的，因此簡單以一個可讓使用者輸入特定天數的新聞，並轉出存成CSV檔，以利後續編輯利用。

### 測試時間
	2021-03-21
