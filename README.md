

# 🌟 Learning Management Application 🚀

A **full-stack Learning Management System** (LMS) built with cutting-edge technologies for a **production-ready deployment**. This application offers scalable features and modern UI/UX to provide an exceptional e-learning experience.  


https://github.com/user-attachments/assets/95008b77-3e9a-40ff-8b6e-30f9d49ad364


---

## 🎯 **Features**
- 🎥 **Video Course Support**: Seamlessly manage video content with progress tracking.  
- 🔍 **Course Search & Categorization**: Find courses quickly with an intuitive search system.  
- 🔐 **Authentication**: Powered by **Clerk** for secure and hassle-free user management.  
- 📊 **Scalable Backend**: Built with **Node.js** and **Express**, optimized for high performance.  
- 🌐 **Responsive Design**: Accessible across desktop, tablet, and mobile devices.  
- 🛠️ **Production Ready**: Deployed with **Docker** on **AWS**, utilizing **Lambda** and **DynamoDB**.  
- 📈 **Enterprise-Level Architecture**: Ensures maintainability, scalability, and flexibility.  

---

## 🛠️ **Technologies Used**
| **Category**      | **Technologies**                          |
|--------------------|-------------------------------------------|
| **Frontend**       | ![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white) ![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white) |
| **Backend**        | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000?style=flat-square&logo=express&logoColor=white) |
| **Database**       | ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white) |
| **Authentication** | ![Clerk](https://img.shields.io/badge/Clerk-FE5E42?style=flat-square&logo=clerk&logoColor=white) |
| **Deployment**     | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Other**          | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) |

---

## 🚀 **Getting Started**

### Prerequisites
- **Node.js** >= 16.x  
- **Docker** installed  
- AWS Account  

---

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/learning-management-app.git
   cd learning-management-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set up Environment Variables**
   Create a `.env` file with the following values:
   ```env
   NEXT_PUBLIC_CLERK_FRONTEND_API=your-clerk-frontend-api
   CLERK_API_KEY=your-clerk-api-key
   AWS_REGION=your-aws-region
   AWS_ACCESS_KEY_ID=your-aws-access-key
   AWS_SECRET_ACCESS_KEY=your-aws-secret-key
   ```

4. **Run Locally**
   Start the development server:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to view in your browser.

---

### Deployment

1. **Build Docker Image**
   ```bash
   docker build -t lms-app .
   ```

2. **Push Image to AWS ECR**
   Follow AWS instructions to push the Docker image to Elastic Container Registry (ECR).

3. **Deploy Using AWS Lambda**
   - Set up AWS Lambda for containerized deployment.  
   - Use **DynamoDB** for backend data storage.

4. **Access Your Application**
   The application will be available at your AWS endpoint.

---
