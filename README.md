# Bank-Bot
Banking chatbot which can guide a person with any banking queries. Bank Bot provide 24/7 client support, so existing and potential customers can try and solve their banking problems after work hours and on weekends.

### requirements
ChatterBot-0.8.4  
simple-websocket-server  

### How to run
1) Once you downloaded this project , Make sure you install the python packages mentioned in requirement.txt.  
2) Go to Chatbot_Project directory and run python server.py.  
3) Above step will open the server. Now right click the index.html page and open with brower. You will be able to see the chat window where you can start the conversation and test.

### Working
1. Chatbot_train.py file trains the data available in the data folder. Once it is trained , the result will be stored as db.sqlite.  
2. Chatbot.py uses this db.sqlite to generate responses for user queries.  
3. server.py sends back message to the client.  



#### Enjoy the application ...........!
