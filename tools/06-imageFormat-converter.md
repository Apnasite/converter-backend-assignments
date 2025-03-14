### **Title:** Image Format Converter  

#### **Tool Details:**  
**Technology Stack:**  
- **Frontend:** Web Components (Lit or Vanilla JS)  
- **Backend:** Express.js (Node.js)  
- **File Processing:** Image format conversion (e.g., PNG to JPG, JPG to WebP, etc.)  
- **Data Handling:** File uploads & API requests  

**Goal:**  
By completing this assignment, candidates will:  
- Learn how to build a **RESTful API** using **Express.js**.  
- Implement **file handling and processing** for **image format conversion**.  
- Work with **Web Components** to create a modular frontend.  
- Understand **client-server communication** via API calls.  
- Gain experience integrating third-party packages for **image processing and conversion**.  

#### **Assignment Description:**  
Develop an **Image Format Converter** where users upload an **image file** via a **WebComponent-based form**. The backend, built with **Express.js**, will process the image and convert it to a user-selected format (e.g., **PNG, JPG, WebP, BMP**). The processed file should be available for download.  

#### **Tasks & Steps:**  

**1. Backend API Development (Express.js):**  
- Set up an **Express.js** server to handle **file uploads**.  
- Use a suitable **Node.js package** to process the uploaded image and convert it to the selected format.  
- Implement API routes for **file processing** and **downloading** the converted image.  

**2. Frontend (WebComponent-based UI):**  
- Create a **form** using Web Components that allows users to **upload an image file**.  
- Provide a dropdown/select option for users to **choose the output format** (PNG, JPG, WebP, BMP, etc.).  
- Send the uploaded file and selected format to the backend using the **fetch API**.  
- Display the **status of the conversion process** and provide a **download link** once the file is ready.  

**3. Integration & Testing:**  
- Ensure the frontend **properly sends data** to the backend.  
- Handle errors gracefully (e.g., **unsupported formats, missing files**).  
- Test **end-to-end functionality** to ensure seamless integration.  

#### **Mathematical Calculation/Steps (if applicable):**  
- No complex mathematical calculations, but ensure **proper resolution and aspect ratio preservation** during conversion.  

#### **Third-Party Packages (if required):**  
- `express` (for backend server)  
- `multer` (for handling file uploads)  
- `sharp` (for image processing and format conversion)  
- `lit` (for WebComponent development)  

#### **Acceptance Criteria:**  
- The **Express.js backend** should successfully process **uploaded image files** and return a **downloadable converted image**.  
- The **WebComponent-based frontend** should have a **responsive form** that allows users to upload files and select output formats.  
- Proper **error handling** should be in place for **invalid inputs**.  
- The application should work seamlessly across **modern web browsers**.  

#### **Submission Guidelines:**  
1. **Fork** the provided GitHub repository.  
2. **Create a folder** named `image-format-converter-<your-name>`.  
3. **Implement the backend and frontend** in the respective subfolders.  
4. **Push the code** to your forked repository.  
5. **Submit a pull request** with a brief description of your implementation.  

**Ensure that the backend correctly handles requests, processes the image file, and seamlessly integrates with the WebComponent-based frontend.**  
