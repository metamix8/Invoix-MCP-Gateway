# MCP (Model Context Protocol) Local Gateway service

# Invoix: MCP-Powered Natural Language Invoicing

### **Stop Filling Forms. Start Talking to Your Invoices.**

Managing your business shouldn't be a chore. **Invoix** is an innovative Local Gateway service built on the **Model Context Protocol (MCP)** that redefines how you manage billing. 

By translating natural language into actionable commands, Invoix allows you to handle the entire invoice lifecycle—**Create, Read, Update, and Delete (CRUD)**—through simple conversational prompts.

---

## 🚀 Key Features

* **Natural Language Processing (NLP):** No complex forms or rigid UIs. Simply tell the system what you need (e.g., *"Create a $500 invoice for Gemini"*).
* **Full Lifecycle Management:** Effortlessly manage invoice generation, instant lookups, and real-time modifications.
* **Powered by MCP:** Leverages the Model Context Protocol for robust, secure, and seamless local data handling.
* **User-Centric Efficiency:** Streamline your workflow by focusing on your business, not the data entry.

---

## 🌐 Get Started

Experience the future of invoicing today at our official website:
👉 **[http://invoix.shop](http://invoix.shop)**

---
*Built with passion for the MCP ecosystem.*


# Invoix MCP Gateway for Claude Desktop
MCP (Model Context Protocol) Local Gateway service for Claude Desktop.

## Installation
```bash
npm install -g invoix-mcp-gateway
```

## Configuration

Add to `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "invoix-gateway": {
      "command": "invoix-mcp-gateway",
      "env": {
        "INVOIX_API_KEY": "your-api-key"
      }
    }
  }
}
```

## Usage

Restart Claude Desktop to use it automatically.

## Features

- Create Invoice 
- Get Invoices 
- Update Invoice 
- Delete Invoice

## Contact

Issue : https://github.com/metamix8/Invoix-MCP-Gateway/issues




## MIT License

Copyright (c) 2026 invoix

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
