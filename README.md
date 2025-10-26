# Mr. HelpMate AI — Intelligent Chat Assistant for GetFlowersDaily.com

**Mr. HelpMate AI** is an intelligent chatbot prototype designed for **GetFlowersDaily.com**, an online floral and pooja flower delivery platform.  
The chatbot leverages **OpenAI GPT** and **Retrieval-Augmented Generation (RAG)** to respond to customer queries about:  
- Product details  
- Availability  
- Door delivery within **Bangalore**  
- Outstation deliveries to **nearby bus stops across South India**

---

## Project Objective

To develop a smart conversational agent capable of answering customer questions quickly and accurately using a combination of natural language understanding and document retrieval.  
The system aims to improve customer engagement and reduce support response times on the GetFlowersDaily website.

---

## Technical Design

### **Architecture Overview**
The chatbot uses **OpenAI GPT models** for natural language understanding and **RAG (Retrieval-Augmented Generation)** for context-aware responses.  

#### **Core Components:**
1. **Query Input:** Accepts user queries (e.g., product availability, delivery information).  
2. **Retriever:** Fetches top relevant results from a collection of internal documents (like product details or delivery policies).  
3. **LLM Processor:** Uses GPT to synthesize an accurate, customer-friendly answer using the retrieved text.  
4. **Response Generator:** Formats the final answer and includes relevant citations when applicable.

---

## Files in This Repository

| File | Description |
|------|--------------|
| **Mr_HelpMate_AI.ipynb** | Main notebook containing code for document processing, retrieval setup, and chatbot logic. |
| **sample_product_pdf_files.pdf** | Sample data used to build and test the RAG pipeline. |
| **Mr_HelpMate_AI_Project_Report.pdf** | Detailed project report explaining objectives, design, implementation, challenges, and lessons learned. |
| **README.md** | Project overview and documentation. |
| **Output Screenshot** | query and response snapshots |

---

## Example Query

**User:** “Do you provide pooja flower delivery to JP Nagar?”  
**Response:**  
> Yes, we deliver fresh pooja flowers to all major areas in Bangalore, including JP Nagar.  
> For locations outside Bangalore, we deliver to the nearest outstation bus stop in South India.  
>  
> **Citations:** GetFlowersDaily Product Policy, Page 2

---

## Key Features

- AI-powered chat assistant using OpenAI GPT  
- Retrieval-Augmented Generation (RAG) for relevant, context-based responses  
- Localized delivery logic (Bangalore and nearby states)  
- Document-based knowledge grounding  

---

## Lessons Learned

- Implementing **RAG** significantly improves accuracy compared to direct GPT querying.  
- Structuring PDFs into chunks (fixed-size chunking) enhances search and retrieval quality.  
- Lightweight prototypes can effectively demonstrate customer-facing AI solutions before full-scale integration.

---

## Author

**Chidambaram Subramanian**  
QA Architect | AI & Data Science Enthusiast  
📍 Bangalore, India  
