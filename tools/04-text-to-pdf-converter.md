### **Title:** Text to PDF Converter  

#### **Tool Details:**  
**Technology Stack:**  
- **Frontend:** Web Components (Lit or Vanilla JS)  
- **Backend:** Express.js (Node.js)  
- **File Processing:** Text to PDF conversion  
- **Data Handling:** User input & API requests  

**Goal:**  
By completing this assignment, candidates will:  
- Learn how to build a **RESTful API** using **Express.js**.  
- Implement **file processing** to convert text into a **PDF document**.  
- Work with **Web Components** to create a modular frontend.  
- Understand **client-server communication** via API calls.  
- Gain experience integrating third-party packages for **PDF generation**.  

#### **Assignment Description:**  
Develop a **Text to PDF Converter** where users enter **text** via a **WebComponent-based form**. The backend, built with **Express.js**, will process the input text and generate a **PDF file**. The processed file should be available for download.  

#### **Tasks & Steps:**  

**1. Backend API Development (Express.js):**  
- Set up an **Express.js** server to handle **text input from users**.  
- Use a suitable **Node.js package** to generate a **PDF file** from the provided text.  
- Implement API routes for **text processing** and **downloading** the generated PDF.  

**2. Frontend (WebComponent-based UI):**  
- Create a **form** using Web Components that allows users to **input text**.  
- Send the text data to the backend using the **fetch API**.  
- Display the **status of the conversion process** and provide a **download link** once the PDF is ready.  

**3. Integration & Testing:**  
- Ensure the frontend **properly sends data** to the backend.  
- Handle errors gracefully (e.g., **empty input, request failures**).  
- Test **end-to-end functionality** to ensure seamless integration.  

#### **Mathematical Calculation/Steps (if applicable):**  
- No complex mathematical calculations, but ensure **text formatting** (font size, alignment, page breaks) is handled properly.  

#### **Third-Party Packages (if required):**  
- `express` (for backend server)  
- `body-parser` (for handling text input)  
- `pdfkit` (for generating PDF files)  
- `lit` (for WebComponent development)  

#### **Acceptance Criteria:**  
- The **Express.js backend** should successfully process **text input** and return a **downloadable PDF file**.  
- The **WebComponent-based frontend** should have a **responsive form** that allows users to enter text.  
- Proper **error handling** should be in place for **invalid or empty input**.  
- The application should work seamlessly across **modern web browsers**.  

#### **Submission Guidelines:**  
1. **Fork** the provided GitHub repository.  
2. **Create a folder** named `text-to-pdf-<your-name>`.  
3. **Implement the backend and frontend** in the respective subfolders.  
4. **Push the code** to your forked repository.  
5. **Submit a pull request** with a brief description of your implementation.  

**Ensure that the backend correctly handles requests, processes the text input, and seamlessly integrates with the WebComponent-based frontend.**  
