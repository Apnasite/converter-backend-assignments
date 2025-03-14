### **Title:** HTML to Markdown Converter  

#### **Tool Details:**  
**Technology Stack:**  
- **Frontend:** Web Components (Lit or Vanilla JS)  
- **Backend:** Express.js (Node.js)  
- **Processing:** Convert HTML content into Markdown format  
- **Data Handling:** API requests & text transformation  

**Goal:**  
By completing this assignment, candidates will:  
- Learn how to build a **RESTful API** using **Express.js**.  
- Implement **HTML to Markdown conversion** using Node.js.  
- Work with **Web Components** to create an interactive frontend.  
- Understand **client-server communication** via API calls.  
- Gain experience in handling **text transformation and structured data conversion**.  

#### **Assignment Description:**  
Develop an **HTML to Markdown Converter** where users can input or upload **HTML content** via a **WebComponent-based form**. The backend, built with **Express.js**, will process the data and return a **Markdown-formatted response** that the user can view or download.  

#### **Tasks & Steps:**  

**1. Backend API Development (Express.js):**  
- Set up an **Express.js** server to accept **HTML input**.  
- Implement **HTML to Markdown conversion** logic.  
- Provide an API route that **accepts HTML data, converts it to Markdown, and returns the formatted output**.  

**2. Frontend (WebComponent-based UI):**  
- Create a **form** using Web Components that allows users to **input or upload HTML content**.  
- Send the HTML data to the backend using the **fetch API**.  
- Display the **converted Markdown output** after processing.  
- Provide a **download button** for the Markdown file.  

**3. Integration & Testing:**  
- Ensure the frontend **properly communicates** with the backend.  
- Handle errors gracefully (e.g., **invalid HTML input**).  
- Test the **HTML to Markdown conversion process** to ensure accuracy.  

#### **Mathematical Calculation/Steps (if applicable):**  
- **Tag Mapping:** Convert HTML tags (`<h1>`, `<p>`, `<a>`, etc.) into **Markdown equivalents**.  
- **Inline Formatting:** Replace `<strong>` with `**bold**`, `<em>` with `*italic*`, and `<ul>` with `-` for lists.  

#### **Third-Party Packages (if required):**  
- `express` (for backend server)  
- `turndown` (for HTML to Markdown conversion)  
- `lit` (for WebComponent development)  

#### **Acceptance Criteria:**  
- The **Express.js backend** should successfully **convert HTML to Markdown**.  
- The **WebComponent-based frontend** should have a **form** for HTML input or file upload.  
- The converted Markdown output should be **properly formatted and displayed**.  
- Proper **error handling** should be in place for **invalid HTML input**.  

#### **Submission Guidelines:**  
1. **Fork** the provided GitHub repository.  
2. **Create a folder** named `html-to-markdown-<your-name>`.  
3. **Implement the backend and frontend** in the respective subfolders.  
4. **Push the code** to your forked repository.  
5. **Submit a pull request** with a brief description of your implementation.  

**Ensure that the backend correctly processes HTML data and integrates seamlessly with the WebComponent-based frontend.**  

