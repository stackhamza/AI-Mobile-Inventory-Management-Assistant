# 📦 AI-Powered Inventory Management Assistant

### Overview
This project is an **AI-driven Inventory Management Assistant** that operates directly through **WhatsApp chat**. It is designed to simplify inventory management by connecting with **Google Sheets** for record-keeping and **Gmail** for automated communication — ensuring smooth, real-time updates and customer interaction.

---

### 🔹 **Core Functions**
- ➕ **Insert New Records** — Add new inventory items directly through chat.
- ✏️ **Update Records** — Modify existing inventory entries quickly.
- ❌ **Delete Records** — Remove outdated or incorrect items from the sheet.
- 📩 **Send Emails** — Automatically email customers with purchase confirmations and CC the owner for records.
- 📱 **WhatsApp Integration** — Manage all inventory actions seamlessly via WhatsApp chat.

---

### 🔹 **Workflow Process**

#### 🔍 **1. Search Item**
- The assistant searches the inventory for the requested item.
- If found, it asks:
  > “How many units would you like to purchase?”

#### 📥 **2. Insert Quantity**
- The customer provides the desired quantity.
- The assistant updates the inventory accordingly.

#### 👤 **3. Customer Details**
- The assistant collects the customer’s name and email address.

#### 📧 **4. Send Email**
- A confirmation email is sent automatically to the customer.
- The owner is CC’d for record-keeping and tracking.

#### 🗂️ **5. Save Records**
- All transaction data — including item, quantity, customer details, and timestamps — is stored securely in **Google Sheets**.

---

### ⚙️ **Integrations Used**
- **Google Sheets** – For dynamic record storage and updates.
- **Gmail** – For automated communication with customers.
- **WhatsApp** – For interactive chat-based inventory management.

---

### 💡 **Key Benefits**
- Streamlined inventory management via chat.
- Automated communication and updates.
- Zero manual data entry.
- Real-time record syncing.
- Simple, efficient, and scalable for businesses of any size.

---

### 🛠️ **Setup Instructions**

Follow these steps to set up the **AI Inventory Management Assistant** for your business:

#### 1. **Connect Google Sheets**
- Create a Google Sheet with columns for:  
  `Item Name | Quantity | Customer Name | Email | Date | Status`
- Generate a Google API key or connect using **Google Sheets integration** in n8n.
- Share the sheet with your service account email.

#### 2. **Set Up Gmail Integration**
- Connect your Gmail account in **n8n**.
- Allow sending emails from your official business email address.
- Configure the “Send Email” node to include customer and owner CC details.

#### 3. **WhatsApp Integration**
- Use **n8n’s WhatsApp API** or a third-party integration (e.g., Twilio or WhatsApp Cloud API).
- Ensure the webhook receives messages and triggers the workflow.

#### 4. **n8n Workflow Configuration**
- Create a workflow that includes:
  - WhatsApp Trigger (receives user messages)
  - Google Sheets Node (search, update, insert)
  - Gmail Node (send confirmation)
  - Decision logic (handle different intents like search, insert, delete)
- Deploy the workflow and test end-to-end communication.

---

### 💬 **How It Works**
1. Customer messages your WhatsApp number with an item request.  
2. The AI agent searches the inventory in Google Sheets.  
3. It asks for quantity, updates the record, and collects customer details.  
4. The system sends a confirmation email and saves all data automatically.  

---

### 🧩 **Tech Stack**
- **n8n (AI + Automation)**  
- **Google Sheets API**  
- **Gmail API**  
- **WhatsApp Business API**  
- **OpenAI / Azure AI (optional for NLP classification)**  

---

### 📊 **Use Cases**
- Small and medium businesses managing daily inventory.  
- E-commerce stores handling frequent customer inquiries.  
- Wholesalers needing instant WhatsApp-based updates.  
- Teams looking for real-time stock tracking with minimal manual effort.  

---

### 🚀 **Future Enhancements**
- AI-powered stock level alerts.  
- Integration with payment gateways.  
- Advanced reporting dashboard for analytics.  

---

### 📞 **Get This for Your Business**
💬 **Automate your inventory management and communication today — manage everything right from WhatsApp!**
If you’d like to implement a similar AI Assistant for your business, feel free to reach out.

---

### 👨‍💻 **Developed By**
**Hamza Zafar** – WordPress & Automation Expert  
💼 **XpertsWP**  
📧 info@xpertswp.com  
🌐 [www.xpertswp.com](https://www.xpertswp.com)
