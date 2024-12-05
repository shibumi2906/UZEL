# UZEL
 # Telegram Bot for Concrete Orders Management using FastAPI  This repository contains a Telegram bot designed to streamline the management of concrete delivery orders for dispatchers. Built using **FastAPI**, the bot leverages modern asynchronous capabilities to handle customer interactions, process orders, and communicate with dispatchers in real-time.  ## Key Features  - **Customer Interaction**:   - Accepts orders via Telegram with essential details (name, phone, delivery address, concrete volume, brand, etc.).   - Checks if the customer is registered in the database and creates a profile for new customers.  - **Order Processing**:   - Automatically assigns orders to the most suitable Ready-Mix Concrete Plants (RBU) based on proximity and workload.   - Transfers orders between dispatchers if the assigned RBU is overloaded.  - **Dispatcher Communication**:   - Sends orders to the appropriate dispatcher's chat for confirmation and processing.   - Logs all order updates, ensuring transparency and traceability.  - **Repeat Orders**:   - Enables customers to quickly reorder using their order history.   - Allows modification of previous order parameters.  - **Admin Tools**:   - Provides a web interface for dispatchers to manage and monitor orders.   - Includes analytics and reporting tools for tracking performance and efficiency.  ## Technical Stack  - **Framework**: FastAPI - **Bot API**: python-telegram-bot - **Database**: SQLite (or extendable to other DBMS) - **Web Server**: Uvicorn - **Logging and Monitoring**: Built-in FastAPI logging  ## How to Run  1. Clone the repository:    ```bash    git clone https://github.com/your-repo-name.git    cd your-repo-name
