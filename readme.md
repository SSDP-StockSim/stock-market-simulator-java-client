# Stock Market Simulator Java Client

The **Stock Market Simulator Java Client** is a versatile and user-friendly application built entirely in Java Swing. It serves as the ideal companion to the Stock Market Simulator Server Manager, providing students with the tools they need to engage in simulated stock market activities and gain valuable financial knowledge. This client library seamlessly interfaces with the server library from the server manager repository, ensuring a smooth and cohesive user experience.

**Note**: the graphical interface is still work in progress.

For more information on the custom SSDP/server client library see: [Stock market simulator server manager](https://github.com/Stock-market-simulator-rsodhi-hbenipal/stock-market-simulator-server-manager)

## Key Features

The Java client boasts a range of features that empower students to interact with the stock market simulator effortlessly. Here are the main pages and functionalities within the client:

### 1. Server Discovery Page

The Server Discovery Page utilizes SSDP (Simple Service Discovery Protocol) to scan the local network and identify all available stock market servers. This allows students to locate and connect to the appropriate server corresponding to their classroom. It simplifies the setup process and ensures students are directed to the correct simulation environment. For more information on the custom SSDP/server client library see: [Stock market simulator server manager](https://github.com/Stock-market-simulator-rsodhi-hbenipal/stock-market-simulator-server-manager)

![Server Discovery Page](https://i.imgur.com/ecNp2tM.png)

### 2. Login/Signup Page

Upon selecting the relevant server, students are directed to the Login/Signup Page. Here, they have the option to either create a new user account or log in with their existing credentials, including a username and password. This step is essential for tracking individual performance and maintaining a personalized learning experience. Client-side validation is implemented to ensure that user inputs are accurate, follow formatting rules, and are free from errors. This step helps prevent unnecessary database requests for invalid data.

![Login/Signup Page](https://i.imgur.com/TNnv7J8.png)

### 3. Dashboard Page

The Dashboard Page provides students with an at-a-glance view of their stock market performance. It displays essential information, including the original balance, current balance, and net profit. Additionally, it introduces the market simulator, offering students a practical and risk-free environment for trading and honing their investment skills. 

![Dashboard Page](https://i.imgur.com/EC3ZVgJ.png)

### 4.  Trade Stocks Page

**Stock Trading (Trade stocks):** Execute buy and sell orders for stocks in the S&P 500, giving students hands-on experience in trading.
   
![Trade stocks](https://i.imgur.com/djOkxCJ.png)
    
### 5.  Portfolio Page

**Portfolio Overview (See portfolio):** Review their stock portfolio, showing the stocks they currently own alongside the book value, and their performance.
   
![See portfolio](https://i.imgur.com/3SL5PKo.png)
    
### 6.  Stocks Search Page 

**Price Information (See stocks):** Obtain real-time price information for specific stocks in the S&P 500, facilitating informed decision-making.
   
![See stocks 1](https://i.imgur.com/OgbD4S6.png)
    
**Visualization of stocks:** Visualize real-time and historic (up to 30 years) price information for specific stocks in the S&P 500, facilitating informed decision-making.

![See stocks 2](https://i.imgur.com/mx6GyY2.png)

### 7.  **Logout:** 

Allows students to safely log out of their accounts when they have finished their stock market activities. It ensures data privacy and security for each user.

## Getting Started

For detailed instructions on how to set up and use the Stock Market Simulator Java Client, please refer to the README files in the client folder. These guides provide step-by-step instructions to help students effectively and efficiently utilize the client for a rich educational experience.

### Prerequisites 
Before running the Stock Market Simulator Frontend, make sure you have the following prerequisites:

**Java(TM) SE Runtime Environment 17.0.5**: You can use newer versions as well.
 
### Steps
1. **Server Setup**: Open stockMarketServer.exe and allow full firewall permissions if prompted. Download the server from this Google Drive link: https://drive.google.com/drive/folders/1aW3-vAzrrse72EbDhDheMdZMD77nBdsf?usp=sharing.
 Ignore any warnings about the file being dangerous for your computer. Start the server from the GUI menu. This will automatically create the user_data and stock_data database files in the directory. If they get deleted, you can relaunch the server to recreate them.

3. **Frontend Setup**: Open finalStockMarket.jar.

4. **Connect to a Server:** Select the server you want to connect to. You can use multiple servers on different devices, and the frontend will display all of them for you to choose.
  
5. **Account Creation**: Create an account. Your login credentials, stocks, and balance will be stored in the database for future use. Even if the server and frontend are closed, you can restart the server, connect to it, and log in with the same details.
## Contact

If you have questions, feedback, or require assistance, please reach out to harguntas.benipal@mail.utoronto.ca
