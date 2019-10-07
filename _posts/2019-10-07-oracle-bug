### Oracle DB 連線會有兩個seesion(Port 1521 & Random)

- Oracle DB會在TCP 1521 listen由client端送過來的request, 然後Oracle DB會再Random assign一個port回傳資料到client端, 所以這個應該是Oracle DB的特性,但是可以經由設定檔來強迫直接用TCP 1521回傳, 不要再隨機assign port.
(要改registry跟環境變數)
這三篇看一下:

1. http://forums.oracle.com/forums/thread.jspa?messageID=1145106

1. http://forums.oracle.com/forums/thread.jspa?messageID=3642909

1. http://www.orafaq.com/maillist/oracle-l/2000/07/21/0173.htm
