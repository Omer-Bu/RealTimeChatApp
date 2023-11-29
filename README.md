# RealTimeChatApp

This Java chat application is designed to showcase the implementation of core Design Patterns.

## Requirements:

- Java Development Kit (JDK): Ensure that you have JDK installed on your system. You can download it from [Oracle's official website](https://www.oracle.com/java/technologies/javase-downloads.html) or use a package manager on Linux.

## How to Run the Project:

1. **Compile the Files:**
   - Open a terminal and navigate to the project directory.
   - Compile the server and client files using the 'javac' command:
     ```bash
     javac Server.java
     javac Client.java
     ```
   - After compilation, you will have the respective 'Server.class' and 'Client.class' files.

2. **Run the Server:**
   - Open a new terminal (shell).
   - Execute the server class using the 'java' command:
     ```bash
     java Server
     ```

3. **Run Multiple Clients:**
   - Open multiple terminals (shells) to simulate different clients.
   - Execute the client class in each terminal:
     ```bash
     java Client
     ```
   - You can repeat this step for the desired number of clients.

4. **Broadcast Messages:**
   - In the client terminals, type a message and press enter to broadcast it to all connected clients.

5. **Private Messages:**
   - Send private messages using the following command format:
     ```bash
     /private <client name> Hello
     ```
     Replace `<client name>` with the name of the target client.

Feel free to explore the RealTimeChatApp and experiment with different functionalities. If you encounter any issues or have questions, refer to the documentation or contact the project maintainers.
