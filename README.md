- Checkout code in any Java IDE
- Run Starter.java in IDE (right click and Run as application)
- Check the code in HttpClient.java - we are making a remote server call and idle timeout is 3 seconds. 
- Remote server will return delayed response in 5 seconds. HTTP Client is failing with error "Connection closed"
- Connection shouldn't be closed because of 3 seconds idle timeout on HTTP Client. I wonder why idle timeout affects the active HTTP connections.