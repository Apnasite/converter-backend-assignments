### **Title:** HEIC to JPG Converter  

#### **Tool Details:**  
**Technology Stack:**  
- **Frontend:** Web Components (Lit or Vanilla JS)  
- **Backend:** Express.js (Node.js)  
- **File Processing:** Convert **HEIC** images to **JPG** format  
- **Data Handling:** File uploads & API requests  

**Goal:**  
By completing this assignment, candidates will:  
- Learn how to build a **RESTful API** using **Express.js**.  
- Implement **file handling and processing** for **image format conversion**.  
- Work with **Web Components** to create a modular frontend.  
- Understand **client-server communication** via API calls.  
- Gain experience integrating third-party packages for **HEIC to JPG conversion**.  

#### **Assignment Description:**  
Develop a **HEIC to JPG Converter** where users upload a **HEIC image** via a **WebComponent-based form**. The backend, built with **Express.js**, will process the HEIC file and convert it into a **JPG file**. The processed file should be available for download.  

#### **Tasks & Steps:**  

**1. Backend API Development (Express.js):**  
- Set up an **Express.js** server to handle **file uploads**.  
- Use a suitable **Node.js package** to convert HEIC images to **JPG format**.  
- Implement API routes for **file processing** and **downloading** the converted JPG file.  

**2. Frontend (WebComponent-based UI):**  
- Create a **form** using Web Components that allows users to **upload a HEIC file**.  
- Send the uploaded file to the backend using the **fetch API**.  
- Display the **status of the conversion process** and provide a **download link** once the file is ready.  

**3. Integration & Testing:**  
- Ensure the frontend **properly sends data** to the backend.  
- Handle errors gracefully (e.g., **unsupported formats, missing files**).  
- Test **end-to-end functionality** to ensure seamless integration.  

#### **Mathematical Calculation/Steps (if applicable):**  
- Not applicable, but **ensure quality retention** while converting HEIC to JPG format.  

#### **Third-Party Packages (if required):**  
- `express` (for backend server)  
- `multer` (for handling file uploads)  
- `heic-convert` (for HEIC to JPG conversion)  
- `sharp` (for additional image processing, if needed)  
- `lit` (for WebComponent development)  

#### **Acceptance Criteria:**  
- The **Express.js backend** should successfully process **uploaded HEIC files** and return a **downloadable JPG file**.  
- The **WebComponent-based frontend** should have a **responsive form** that allows users to upload files.  
- Proper **error handling** should be in place for **invalid inputs**.  
- The application should work seamlessly across **modern web browsers**.  

#### **Submission Guidelines:**  
1. **Fork** the provided GitHub repository.  
2. **Create a folder** named `heic-to-jpg-<your-name>`.  
3. **Implement the backend and frontend** in the respective subfolders.  
4. **Push the code** to your forked repository.  
5. **Submit a pull request** with a brief description of your implementation.  

**Ensure that the backend correctly handles requests, processes the HEIC file, and seamlessly integrates with the WebComponent-based frontend.**  