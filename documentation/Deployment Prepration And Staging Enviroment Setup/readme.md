# Day 6 - Deployment Preparation and Staging Environment Setup - Summary  

## Overview  
On Day 6, the focus was on preparing for deployment, establishing a staging environment, and ensuring that the marketplace functions properly in a production-like setting. Below is a summary of the steps completed and the results achieved.  

---  

### **Step 1: Hosting Platform Setup**  
- **Chosen Platform:**  
  I selected **Vercel** for fast and efficient application deployment.  
- **Repository Integration:**  
  The GitHub repository was successfully connected to Vercel, with the appropriate build settings and deployment scripts configured.  

---  

### **Step 2: Configure Environment Variables**  
- **Environment Variables Added:**  
  A `.env` file was created to store sensitive information, including:  
NEXT_PUBLIC_SANITY_PROJECT_ID=project_id
NEXT_PUBLIC_SANITY_DATASET=production
API_KEY=api_key

markdown
Copy
Edit
These variables were securely uploaded to Vercel's dashboard.  

---  

### **Step 3: Deploy to Staging**  
- **Deployment to Staging:**  
The application was successfully deployed to the staging environment.  
- **Deployment Validation:**  
- The build process completed without any errors.  
- Basic functionality, including navigation and API integration, was verified within the staging environment.  

---  

### **Step 4: Staging Environment Testing**  
- **Testing Performed:**  
- **Functional Testing:** Validated core features like product listing, cart operations, and API integration.  
- **Performance Testing:** Utilized Lighthouse and GTmetrix to evaluate speed and responsiveness, yielding positive results.  
- **Security Testing:** Verified input validation, HTTPS usage, and secure API communication.  

- **Test Case Reporting:**  
A detailed CSV report was prepared, including the following fields:  
- Test Case ID  
- Description  
- Steps  
- Expected Result  
- Actual Result  
- Status  
- Remarks  

---  

### **Step 5: Documentation Updates**  
- **README.md Creation:**  
A comprehensive README.md file was drafted, summarizing the project's activities, deployment process, and testing results.  
- **Project Organization:**  
All files from Days 1 to 6 were organized into appropriate folders and uploaded to the GitHub repository.  

---  

## Achieved Outcomes:  
1. A fully deployed staging environment for the marketplace.  
2. Environment variables securely configured on the hosting platform.  
3. A detailed test case and performance report documenting all staging tests.  
4. Organized project files and documentation uploaded to the GitHub repository.  
5. A README.md file summarizing the project and folder structure.  

---  

**Day 6 Checklist:**  
- **Deployment Preparation:** ☑  
- **Staging Environment Testing:** ☑  
- **Documentation:** ☑  
- **Form Submission:** ☑  
- **Final Review:** ☑  

With the successful completion of these tasks, the marketplace is now ready for further testing and final deployment.