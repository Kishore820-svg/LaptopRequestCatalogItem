# 💻 Laptop Request Catalog Item – ServiceNow Project

Hi! I’m **Bandaru Krishna Kishor**, a ServiceNow enthusiast and ITSM developer. I enjoy designing practical, user-centric solutions that simplify complex workflows and improve service delivery. This project highlights my ability to create **dynamic Service Catalog items** that streamline organizational processes and enhance the employee experience.

---

## 🔹 About this Project

● Many organizations face challenges with manual laptop request processes that are slow, error-prone, and difficult to track.  
● To address this, I built a **Laptop Request Catalog Item in ServiceNow** with dynamic form behavior and approval workflows.  
● Through this project, I gained hands-on experience with:  
   ● Service Catalog configuration  
   ● UI Policies for dynamic field behavior  
   ● Client Scripts for user interactions  
   ● Update Sets for governance and deployment  
● This strengthened my skills in building automated, efficient, and user-friendly IT service solutions.  

---

## 🔹 Prerequisites & Tools Used

● ServiceNow Developer Instance (with Service Catalog access)  
● Knowledge of Service Catalog Items and Variables  
● Catalog UI Policies and Client Scripts  
● Update Sets for moving customizations between instances  
● Basic JavaScript for UI Actions and Client Scripts  

---

## 🔹 How to Use / Deploy

● Create a local Update Set named *Laptop Request* and make it current.  
● Build the Service Catalog Item with variables:  
   ● Laptop Model  
   ● Justification  
   ● Accessories (checkbox)  
   ● Accessories Details (shown dynamically if checkbox is selected)  
● Configure UI Policies to **show/require Accessories Details** when needed.  
● Add a **Client-side UI Action (Reset Button)** to clear form fields.  
● Test the item in the **Service Catalog → Hardware category**.  
● Export the Update Set and import it into other instances for deployment.  
