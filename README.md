# Chatbox PHP + MySQL

       
                            Provide a tool allowing multiple people to communicate remotely.

1. NO JAVASCRIPT :

To keep the conversation up to date, we will use a file to display the conversation (conversion.php). It will be displayed in an *iFrame* tag (tag that will be in an index.php file). The conversion.php file will use an HTML meta tag that will reload every 10 seconds (google "HTML auto-refresh").

2. Messages stored in MySql table : 

Define the colones necessary to carry out the experiment described in the prototype.

3. Functionnality :

*-Register:* 
Creates a user account of the chat (a form allowing to specify his email and his password).
No validation when registering by mail.

*-login/logout:* 
Log in to his account (email + password) and logout using *PHP sessions*

*-Message:*

Be able to publish messages in the conversation.

If we are connected, we can just read the messages, but not publish them. 
Instead of the message form, displays an invitation to log in or register.
Each form processing will be sanitized and validated beforehand.
Try to implement emojis, have an image as a portrait for each user, heal the UX.

