# Dynamic Web TWAIN with ZK Framework

The sample demonstrates how to make [DWT][0] work with ZK framework.

## Download & Installation
-----------------------
* [Dynamic Web TWAIN 11.2][1]
* [ZK Framework][2]

## Getting Started
-----------
1. Import the project to **Eclipse**.
2. Copy the **Resources** folder from **< Dynamic Web TWAIN >\Resources** to **webapp**.
    
   ![zk project structure](http://www.codepool.biz/wp-content/uploads/2016/02/zk_project_structure.png)
3. Edit dynamsoft.webtwain.config.js:
     
   ```
   Dynamsoft.WebTwainEnv.AutoLoad = false;
   ```
4. Run app: **Run As > Maven Build…**
5. Visit **http://localhost:8080/dwt/index.zul**.

## Blog
[How to Use Dynamic Web TWAIN with ZK Framework][3]

[0]:http://www.dynamsoft.com/Products/WebTWAIN_Overview.aspx
[1]:http://www.dynamsoft.com/Downloads/WebTWAIN_Download.aspx
[2]:https://www.zkoss.org/download/zk
[3]:http://www.codepool.biz/dynamic-web-twain-zk-framework.html
