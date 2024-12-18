---

# **Project Name: CRM Ticket System**

The **CRM Ticket System** is a full-stack MERN application designed for managing customer support tickets. It features a client portal and an admin panel, with functionalities including ticket creation, updates, and resolution. The app is deployed on AWS, using modern tools and frameworks to ensure scalability and reliability.

---

## **Mission and Objectives**

### **Mission**
To create an efficient ticketing system that allows businesses to manage customer queries and support tasks seamlessly.

### **Objectives**
1. Develop a **microservice-based MERN stack application** for scalability.
2. Enable secure user authentication and authorization.
3. Provide an admin panel for managing clients and tickets.
4. Allow clients to create and manage their tickets.
5. Deploy the application using AWS services with CI/CD pipelines.

---

## **Technology Stack**

### **Frontend**
1. **React.js**
   - **Why:** For building an interactive UI.
   - **Use Case:** Client and admin portals, forms, and dashboards.

2. **React Router**
   - **Why:** For managing navigation.
   - **Use Case:** Routing between pages such as login, dashboard, and ticket details.

3. **Redux**
   - **Why:** For state management.
   - **Use Case:** Managing shared state like user authentication and ticket data.

### **Backend**
1. **Node.js**
   - **Why:** For building scalable APIs.
   - **Use Case:** Creating RESTful services for authentication, tickets, and user management.

2. **Express.js**
   - **Why:** Lightweight framework for building APIs.
   - **Use Case:** Routing and middleware setup.

3. **Redis**
   - **Why:** For storing JWT tokens and caching.
   - **Use Case:** Enhancing performance and session management.

### **Database**
1. **MongoDB**
   - **Why:** Flexible schema for storing user and ticket data.
   - **Use Case:** Managing collections for users, tickets, and sessions.

### **Deployment**
1. **AWS**
   - **Why:** For scalable cloud hosting.
   - **Use Case:** Using EC2, ECS, CloudFront, and S3 for deployment.

2. **Docker**
   - **Why:** For containerizing the application.
   - **Use Case:** Ensuring consistency across development and production environments.

---

## **System Architecture**
The CRM Ticket System follows a microservice architecture with separate repositories for:
1. **Frontend (React)**
2. **Admin CMS (Node.js with SSR)**
3. **API Services**

It uses AWS services for hosting and load balancing, with a CI/CD pipeline for continuous deployment.

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

### **Week 1: Project Setup and UI Development**
- **Goal:** Set up the foundational structure and design the app UI.
- **Tasks:**
  1. Initialize React and Express projects.
     - **Reading:** [Setting Up MERN Stack](https://www.mongodb.com/mern-stack)  
     - **Video:** [MERN Stack Crash Course](https://www.youtube.com/watch?v=fnpmR6Q5lEc)
  2. Create UI components using React.
     - **Reading:** [React Components](https://reactjs.org/docs/components-and-props.html)  
     - **Video:** [React Basics](https://www.youtube.com/watch?v=SqcY0GlETPk)
  3. Implement navigation with React Router.
     - **Reading:** [React Router Docs](https://reactrouter.com/en/main/start/overview)  
     - **Video:** [React Router Tutorial](https://www.youtube.com/watch?v=Law7wfdg_ls)
  4. Set up a GitHub repository and integrate with Trello for task management.
     - **Reading:** [Trello Docs](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions)  
     - **Video:** [React Router Tutorial](https://www.youtube.com/watch?v=QA_RSS2dXK8)
     

- **Deliverables:**  
  - Basic project setup with GitHub integration.
  - Responsive UI for login, dashboard, and ticket pages.

---

### **Week 2: Authentication**
- **Goal:** Implement secure user authentication using JWT.
- **Tasks:**
  1. Set up MongoDB schemas for users and sessions.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)  
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build login and signup APIs.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)  
     - **Video:** [JWT Implementation](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Implement login/logout functionalities on the frontend.
     - **Reading:** [Login docs](https://dev.to/sanjayttg/jwt-authentication-in-react-with-react-router-1d03)  
     - **Video:** [Login Turorial](https://www.youtube.com/watch?v=Xc_MPV9EtNs)
- **Deliverables:**  
  - Functional authentication system with JWT.

---

### **Week 3: Ticket Management**
- **Goal:** Create and manage tickets for clients and admins.
- **Tasks:**
  1. Design ticket schemas in MongoDB.
     - **Reading:** [MongoDB Schema Guide](https://www.mongodb.com/docs/manual/data-modeling/)  
     - **Video:** [MongoDB Data Modeling](https://www.youtube.com/watch?v=3GHZd0zv170)
  2. Build APIs for creating, updating, and fetching tickets.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)  
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  3. Implement ticket UI on the client side.
    
- **Deliverables:**  
  - Functional ticket creation and management system.

---

### **Week 4: Admin Panel**
- **Goal:** Build an admin CMS for managing clients and tickets.
- **Tasks:**
  1. Create admin-specific APIs for client and ticket management.
  2. Develop admin panel UI with server-side rendering.
     - **Reading:** [Server-Side Rendering in Node.js](https://www.geeksforgeeks.org/node-js-server-side-rendering-ssr-using-ejs/)  
     - **Video:** [Node.js SSR Tutorial](https://www.youtube.com/watch?v=yy9cbu_e3Xg)

- **Deliverables:**  
  - Fully functional admin panel with protected routes.

---

### **Week 5: Deployment**
- **Goal:** Deploy the application to AWS.
- **Tasks:**
  1. Set up AWS services (EC2, ECS, VPC).
     - **Reading:** [AWS Deployment Guide](https://aws.amazon.com/getting-started/)  
     - **Video:** [Deploying to AWS](https://www.youtube.com/watch?v=l134cBAJCuc)
  2. Configure CI/CD pipelines for automated deployment.
     - **Reading:** [CICD Guide](https://www.ibm.com/think/topics/ci-cd-pipeline)  
     - **Video:** [CICD video](https://www.youtube.com/watch?v=G1u4WBdlWgU) 
  4. Test the deployed application for bugs and performance.
     - **Reading:** [Testing Guide](https://jestjs.io/docs/tutorial-react)  
     - **Video:** [Testing video](https://www.youtube.com/watch?v=8Xwq35cPwYg&t=2017s) 
 

- **Deliverables:**  
  - Live CRM Ticket System accessible via public URL.

---

## **Features**
1. **Client Portal**:  
   - Login/Signup  
   - Ticket creation and tracking  
   - Conversation history with admins  

2. **Admin Panel**:  
   - Manage clients and tickets  
   - View dashboard analytics  

3. **Secure Backend**:  
   - JWT-based authentication  
   - Role-based access control  

4. **AWS Deployment**:  
   - Scalable and reliable hosting  

---

## Screenshots
![Screenshot (341)](https://github.com/user-attachments/assets/9b871a93-9a4a-44c9-8b57-f6baa6dab665)
![Screenshot (342)](https://github.com/user-attachments/assets/a18aa79c-ad83-43bd-9a4f-60699debee94)
![Screenshot (343)](https://github.com/user-attachments/assets/784e53a0-fbda-41b2-a07d-8f138b042714)
![Screenshot (344)](https://github.com/user-attachments/assets/37861a18-0104-4566-b211-41a2cb2a53e1)
![Screenshot (335)](https://github.com/user-attachments/assets/9bad54aa-0833-401b-9b91-22733e0d5109)
![Screenshot (336)](https://github.com/user-attachments/assets/9e72f7c4-0454-403c-9199-cebe233d6683)
![Screenshot (337)](https://github.com/user-attachments/assets/ec5b3c82-d900-43ef-8e89-52f6f586597d)
![Screenshot (338)](https://github.com/user-attachments/assets/92b9a525-15bd-4b3b-8fa1-31fe93b70f1f)
![Screenshot (339)](https://github.com/user-attachments/assets/f1364eed-5adf-4ea1-943e-805ada9e6279)
![Screenshot (340)](https://github.com/user-attachments/assets/4b5b36aa-c09c-4c32-8305-62074acb963a)

---

## **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/)
3. [Express Documentation](https://expressjs.com/)
4. [AWS Documentation](https://aws.amazon.com/documentation/)
5. https://www.youtube.com/watch?v=yiO8qXQ4BIc&list=PLtPNAX49WUFN8yq2vEuAY6AhM5EJOXQQ0&index=3
6. https://github.com/DentedCode/javascript-tutorial
