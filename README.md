# CS_NOTE
第二周
區分英文字元的大小寫，基本以小寫為主
檔名長度至多256個字元，可包刮字母、數字、"."(點)、"_"(下劃線)和"-"(連字元)
檔名不可使用的："?"(問號),"*"(星號), " "(空格), "$"(貨幣符), "&", 擴號, "/" (斜線)，"." , ".."!"
絕對路徑：路徑的寫法一定由根目錄寫起。
相對路徑：路徑的寫法『不是由 / 寫起』，例如由 /usr/share/doc 要到 /usr/share/man 底下時，寫成： 『cd ../man』，相對路徑意指『相對於目前工作目錄的路徑！
cd 	變換目錄
pwd	顯示目前的目錄
mkdir 建立一個新目錄
rmdir 刪除一個裡面是空的空目錄
cp 複製
mv 移動
ls 顯示目錄下的所有內容
cat 查看檔案內容
nano:編輯文檔
:W 將編輯的資料寫入硬碟檔案中
:W!若檔案只為唯讀時，強制寫入該檔案(!為強制的意思)
:q 離開
:q 強制離開不儲存檔案
:wq 儲存後離開
:wq! 強制持存後離開
┬第三周
為什麼要壓縮檔案呢？
備份資料的時候，方便整理。
將檔案變小，節省電腦硬碟的空間。(但圖片、音訊、視訊等多媒體檔案壓縮率低，並不能有效節省空間)
將無數個散亂的檔案打包成一個較小的檔案，亦方便資訊在網路上流通。
壓縮檔案時，可以視情況進行加密。
使用的電腦系統是使用bytes單位計量的，但事實上電腦最小的計量單位應該是 bits (1 byte = 8 bits)。因此將許多閒置的空間釋出，即可將檔案占用的空間減少。
將重複的資料進行統計記錄。EXAMPLE：如果資料為『111....』共有100個1時， 那麼壓縮技術會記錄『100個1』而不是真的有100個1的位元存在。
需要在記憶體很小的機器（如小於 128MB）上解壓縮時，則選擇 gzip 格式。
需要在很簡單、沒有什麼工具可用的機器解壓縮時，則選擇 gzip 格式。
需要節省網路頻寬、縮短下載所需要的時間時，則選擇 xz 格式。
需要有最好的壓縮率時，則選擇 tar.xz  格式。
cat  從第一行顯示檔案內容、形成新檔案
cat -n file1 > file2→把file1的檔案內容加上行號後輸入file2檔案
-n→由1開始對所有輸出的行數編號
>→將多個文件覆蓋到目標文件中
>>→將多個文件追加到目標文件中
tac  從最後一行開始顯示
tac -r -s 'x\|[^x]' test.log→一個接著一個字符的反轉一個文件
-r→將分隔符作為基礎正規表達是處理
-s→使用String作為分隔符代替默認的換行符







