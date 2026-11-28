# Day 4 – Tools, Structured Output and Google Sheets

## Workshop
One Person Company – AI Agents Workshop

## Project
**Sweet Crumbs Home Bakery AI Assistant**

## Day 4 Overview

On Day 4, I learned how to make an AI assistant perform real tasks using Python tools. I also learned how to validate customer details using Pydantic and save orders directly into Google Sheets.

## Topics Learned

### 1. AI Tools
- Learned why AI agents need tools to perform real-world tasks.
- Created Python functions as tools using `@tool`.
- Understood how tools help an AI assistant get information and perform actions.

### 2. Function Calling
- Learned how an AI model selects the correct tool.
- Understood how the model passes arguments to a Python function.
- Learned how the tool returns its result to the AI agent.

### 3. Writing Good Tools
- Learned the importance of meaningful tool names.
- Used clear docstrings to describe each tool.
- Understood how tool descriptions help the agent choose the correct tool.

### 4. Creating an AI Agent
- Used LangChain's `create_agent`.
- Connected multiple Python tools to the bakery assistant.
- Tested the agent with questions about cake prices and bakery opening hours.

### 5. Error Handling and Rate Limits
- Learned about API rate limits and error 429.
- Understood how retries help handle temporary errors.
- Learned the importance of handling tool errors properly.

### 6. Structured Output with Pydantic
- Learned how to create structured data using Pydantic.
- Created an `Order` model with customer name, cake item, quantity, date and eggless preference.
- Used structured output to convert customer messages into organized order details.
- Learned how Pydantic checks whether the given data is valid.

### 7. Google Sheets Integration
- Connected Google Colab with Google Sheets using `gspread`.
- Created a sheet to store bakery customer orders.
- Used the `log_order` tool to add new orders automatically.
- Understood how Python can update Google Sheets.

### 8. Complete Order Automation
Combined all the concepts to create an order management workflow:

1. Customer sends a message to the AI assistant.
2. The assistant understands the order.
3. It checks the price using the `get_price` tool.
4. It collects the required customer details.
5. Pydantic validates the order information.
6. The `log_order` tool saves the order.
7. The order is added to Google Sheets.
8. The assistant sends a confirmation message to the customer.

## Technologies Used
- Python
- Google Colab
- LangChain
- Groq API
- Pydantic
- Google Sheets
- gspread

## Key Takeaways
- Creating and using tools in AI agents.
- Understanding function calling.
- Writing meaningful tool names and descriptions.
- Validating data with Pydantic.
- Connecting Python with Google Sheets.
- Automating customer order management.

## Day 4 Outcome

Successfully learned how to connect AI agents with Python tools, validate customer orders using Pydantic and store order details in Google Sheets.

This improved the **Sweet Crumbs Home Bakery AI Assistant** by making it capable of checking prices, handling customer orders and saving order information automatically.

---

**Workshop:** One Person Company – AI Agents Workshop  
**Project:** Sweet Crumbs Home Bakery AI Assistant  
**Progress:** Day 4 Completed
