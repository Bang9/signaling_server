## Signaling server
app.js -> signaling server

```
npm install -g forever
npm install
forever start app.js
```
#### *서버는 broadCaster와 viewer의 sdp/candidate를 교환하는 구조로 이루어져 있습니다.
#### *1:N 방식을 구축하기 위해서는 broadcaster 클라이언트 파일을 참고하시기 바랍니다.

## Test Client files

broadcaster.html -> broadcaster client<br/>
viewer.html      -> viewer client<br/>
resources/socket.io.js -> client socket

#### *Client signaling socket url을 서버 url로 변경해야합니다.




