# **Aitaca Frontend Developer Test**

## **Context**  
We are looking for a motivated and skilled **Frontend Developer** to join our team at **Aitaca**. This technical test is designed to evaluate your ability to build **user-friendly** and **responsive** web interfaces by consuming an existing API.  

For this test, we’ll be using the **Swagger Petstore API** ([documentation here](https://petstore.swagger.io/)) as the backend for your application.  

---

## **General Instructions**  
1. **Fork** this repository to your GitHub account.  
2. Complete the tasks described below, committing your progress as you go.  
3. Include a brief response to the **evaluation questions** at the end of this README.
4. Reply to the email where you received this test with a link to your repository.

---

## **Objective**  
Your task is to **build a Pet Management Dashboard** that consumes the **Swagger Petstore API**. This dashboard should allow users to perform basic operations like **viewing, searching, adding, and updating pets**. The application must be **responsive, visually appealing**, and demonstrate your **ReactJS** skills.  

---

## **Core Tasks**  

### **1. Pet List Page**  
- Fetch and display a list of pets from the `/pet/findByStatus` endpoint.  
- Allow users to filter the list by **status** (_available_, _pending_, _sold_).  
- Display basic information for each pet:  
  - `id`  
  - `name`  
  - `status`  
  - `category` _(if available)_  
- Include a button to **view details** for each pet.  

### **2. Pet Details Page**  
- Clicking on a pet in the list should navigate to a **details page**.  
- Fetch and display **detailed information** for the selected pet using the `/pet/{petId}` endpoint.  
- Allow users to **update the pet's status** (e.g., _available → sold_).  

### **3. Add Pet Form**  
- Create a **form** to add a new pet using the `/pet` endpoint.  
- **Required fields:**  
  - `name` _(required)_  
  - `status` _(default to "available")_  
- **Optional fields:**  
  - `category`  
- Include **input validation** to ensure proper data entry.  

### **4. Search Functionality**  
- Add a **search bar** to filter pets by name.  
- Perform the search **locally** on the already fetched list of pets.  

---

## **Bonus Tasks**  
If you want to stand out, consider implementing one or more of the following:  

✔ **State Management**: Use **Redux** or **Context API** to manage application state.  
✔ **UI Framework**: Use a design system like **Material-UI, Ant Design, or Chakra UI** to improve styling.  
✔ **Performance Optimization**: Implement **caching for API responses** or optimize the app for speed.  
✔ **Testing**: Write **unit tests** for one or more components using **Jest or React Testing Library**.  
✔ **Responsive Design**: Ensure the app looks great on both **desktop and mobile devices**.  
✔ **Accessibility**: Follow **accessibility best practices** (e.g., proper use of **ARIA roles, focus management**).  

---

## **Technical Requirements**  
✔ Use **ReactJS** and **TypeScript** for the implementation.  
✔ Follow modern React patterns (**functional components, hooks**).  
✔ Use **React Router** for navigation between pages.  
✔ Ensure the application is **fully responsive**.  
✔ Use **GitHub effectively**, with at least **3 commits** showing your workflow.  

---

## **Evaluation Criteria**  
We will assess your submission based on:  

✅ **Code Quality**: Clean, modular, and reusable code.  
✅ **API Integration**: Effective use of the **Swagger Petstore API**.  
✅ **UI/UX Design**: A **user-friendly** and **visually appealing** interface.  
✅ **ReactJS Proficiency**: Demonstrating modern React practices.  
✅ **Documentation**: Clear and concise **README instructions** for setup and usage.  

---

## **Questions to Answer**  
At the end of the test, please answer these questions in your **Pull Request description**:  

1️⃣ **How long did you spend on the test?**  
2️⃣ **What part of the application are you most proud of?**  
3️⃣ **If you had more time, what would you improve or add?**  

---

## **Documentation**  
📌 Update the **README.md** file in your repository with:  
- **Instructions** on how to **set up and run** the application.  
- How to **test the app** (if tests are included).  
- A **brief explanation** of any **bonus tasks or additional features** you implemented.  

---

## **How to Get Started**  
1️⃣ **Review the** [Swagger Petstore API documentation](https://petstore.swagger.io/) **to familiarize yourself with the endpoints.**  
2️⃣ **Plan your application structure** and component breakdown.  
3️⃣ **Start coding**, and don’t forget to **commit regularly** to show your progress.  

---

## **Good Luck!** 🚀  
We’re excited to see your solution and look forward to having you on our team. If you have any questions, feel free to reach out at 📩 **tech@aitaca.io**.
