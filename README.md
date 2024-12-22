# ColumnCompute 

## Table of content
1. FlowChart (HLD)
2. Features
3. Tech Stack
4. Installation
5. Future Scope
6. Usage


---

## FlowChart (HLD)
Here’s the high-level diagram showing the architecture of the project.
![image](https://github.com/user-attachments/assets/25e44262-e69f-4802-9954-704e52416cf6)

---

## Features

1. **Third-Party Authentication**  
   Uses [Auth0](https://auth0.com/) for secure authentication with trusted Google services.

2. **Data Storage**  
   Stores data in a relational format using [Supabase](https://supabase.com/), a reliable and scalable service.

3. **Scalability**  
   Both **Auth0** and **Supabase** are designed for scalability, ensuring efficient handling of increased traffic.

4. **Column Validation (C3 & C4)**  
   - Invalid data types for mathematical operations are flagged by the backend.
   - Empty (NaN) rows are automatically ignored.
   - Missing columns (C3 or C4) trigger an error and notify the user.

5. **Docker Integration**  
   Uses a **Dockerfile** to consolidate dependencies, simplifying deployment and enabling scalable containerization for high traffic.

---
## Tech Stack
1. Frontend 
   <img src="https://github.com/user-attachments/assets/3ea4e122-1987-4569-a203-0caed7ba4f6b" width="90"/>
2. Backend
    <img src="https://github.com/user-attachments/assets/bad1b8ca-e958-484b-8f11-58cd27135b67" width="90"/>




