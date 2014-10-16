anyTVProjects
=============

Javascript Chat Plugin
Installation:

app.js
gchat.js

- Deploy file on Node Server.


On frontend/client:

1. Make sure that you have also included the latest jquery.js or just add the following script:
   <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>

2. Add the following script to your frontend source:
   <script src="/socket.io/socket.io.js"></script>
   <script type="text/javascript" src="[path-to-js-file]/gchat.js"></script>

3. Add the following scripts on your frontend/client code:
   
   For : Prompt input of Channel and Username

   <scripts type="text/javascript">
	$(function(){
            $('#chatholder').initChatBox(prompt('Keyin Channel'),prompt('Keyin User'),'%%@&&#%$*%%');
        });
   </script>

   
   For : Passing parameters to plugin

   <scripts type="text/javascript">
	$(function(){
            $('#chatholder').initChatBox([Channel-to-join],[Username],[Token]);
        });
   </script>
