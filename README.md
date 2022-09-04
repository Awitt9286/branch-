# branch-<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Arvia Chat</title>
    <script type="text/javascript" src="https://arvia.chat/js/arvia.chat.js" ></script>
  </head>
  <body>
    <button id="startButton" style="height: 32px">Start Arvia Chat</button><br />
    <div id="arvia.chat"></div>
    <script type="text/javascript">

      document.getElementById('startButton').addEventListener('click',
        
        function() {
          var arviaChat = new ArviaChat();
          arviaChat.setTestUser(true);
          arviaChat.setRoomName("test-room-1");
          arviaChat.init("arvia.chat");
          arviaChat.connect();
        }

      );

    </script>
  </body>
</html>
