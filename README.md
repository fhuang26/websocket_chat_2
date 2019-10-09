## websocket_chat_2
* This begins to work. I used a debug field in chat.html to trace object flow on client to fix a few bugs.

* On Java side, I turned on Run > Edit Config > Maven > 'Show console when a message is printed to standard output stream' to trace object flow on server to fix a few bugs.

* We can do "localhost:8080/?username=joe" or "http://localhost:8080/chat?username=joe" on a browser.

* A user can type a message, click SEND, and the message will be sent to all online users.

* Both message container and onlineCount seem to work.

* In chat.html, I couldn't get username from "http://localhost:8080/chat?username=joe" yet.
* A screenshot "msg container onlineCount" is uploaded.
* Please advice on items to improve further. Thank you!
