### **Title:** JSON to CSV Converter  

#### **Tool Details:**  
**Technology Stack:**  
- **Frontend:** Web Components (Lit or Vanilla JS)  
- **Backend:** Express.js (Node.js)  
- **Processing:** Convert JSON data into a structured CSV format  
- **Data Handling:** API requests & file downloads  

**Goal:**  
By completing this assignment, candidates will:  
- Learn how to build a **RESTful API** using **Express.js**.  
- Implement **JSON to CSV conversion** using Node.js.  
- Work with **Web Components** to create an interactive frontend.  
- Understand **client-server communication** via API calls.  
- Gain experience in handling **file processing and structured data conversion**.  

#### **Assignment Description:**  
Develop a **JSON to CSV Converter** where users can input or upload **JSON data** via a **WebComponent-based form**. The backend, built with **Express.js**, will process the data and return a **CSV file** that the user can download.  

#### **Tasks & Steps:**  

**1. Backend API Development (Express.js):**  
- Set up an **Express.js** server to accept **JSON input**.  
- Implement **JSON to CSV conversion** logic.  
- Provide an API route that **accepts JSON data, converts it to CSV, and returns a downloadable file**.  

**2. Frontend (WebComponent-based UI):**  
- Create a **form** using Web Components that allows users to **input or upload JSON data**.  
- Send the JSON data to the backend using the **fetch API**.  
- Display the **converted CSV file download link** after processing.  

**3. Integration & Testing:**  
- Ensure the frontend **properly communicates** with the backend.  
- Handle errors gracefully (e.g., **invalid JSON format**).  
- Test the **JSON to CSV conversion process** to ensure accuracy.  

#### **Mathematical Calculation/Steps (if applicable):**  
- **CSV Formatting:** Convert JSON objects into **comma-separated values**.  
- **Header Extraction:** Extract unique keys from JSON objects for CSV headers.  

#### **Third-Party Packages (if required):**  
- `express` (for backend server)  
- `csv-writer` or `json2csv` (for JSON to CSV conversion)  
- `lit` (for WebComponent development)  

#### **Acceptance Criteria:**  
- The **Express.js backend** should successfully **convert JSON to CSV**.  
- The **WebComponent-based frontend** should have a **form** for JSON input or file upload.  
- The converted CSV file should be **accurate and downloadable**.  
- Proper **error handling** should be in place for **invalid JSON input**.  

#### **Submission Guidelines:**  
1. **Fork** the provided GitHub repository.  
2. **Create a folder** named `json-to-csv-<your-name>`.  
3. **Implement the backend and frontend** in the respective subfolders.  
4. **Push the code** to your forked repository.  
5. **Submit a pull request** with a brief description of your implementation.  

**Ensure that the backend correctly processes JSON data and integrates seamlessly with the WebComponent-based frontend.**  
