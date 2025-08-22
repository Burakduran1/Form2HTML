# 🖼️ Picture to HTML with Gemini API (n8n + Custom UI)

This project is an **automation flow** built on **n8n**, combined with a **custom frontend UI**.  
The UI allows users to **upload an image**, which is then sent via **Webhook** to the n8n workflow.  
Using **Google Gemini API**, the image is processed and converted into **HTML code**.  
The generated HTML can be previewed directly in the browser.  

---

## 🚀 Features
- Upload an image through a **custom UI**  
- Send image via **Webhook** to n8n  
- Process image with **Gemini API**  
- Return the generated **HTML code**  
- Built-in **HTML preview**  

---

## 📸 Workflow Overview
1. User uploads an image from the **custom UI**  
2. The UI sends a POST request to the n8n **Webhook**  
3. The workflow calls the **Gemini API** with the image  
4. Gemini responds with **HTML representation** of the image  
5. UI displays both the **HTML code** and a **live preview**  

---

## 🛠️ Requirements
- [n8n](https://n8n.io/) (self-hosted or n8n.cloud)  
- A **Google Gemini API Key**  
- A **Custom Frontend UI** (provided in this repo)  

---

