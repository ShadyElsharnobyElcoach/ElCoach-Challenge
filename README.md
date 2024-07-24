<p align="center">
<img src="./assets/elcoachLogo.jpg" width="100" alt="ElCoach Logo">
</p>

# ElCoach-Challenge

Welcome to the ElCoach-Tech development challenge. This document provides a detailed overview of the challenge, including tasks, requirements, and submission instructions.

## The Challenge

Your task is to develop a set of screens for an online grocery shopping application using React Native.

### Provided Materials:

- **Design Mockups**: [View the design mockups on Figma](https://www.figma.com/design/IMN7twbII4yBaWFOnRyAKP/Simple-Grocery-app?node-id=0-1).
- **API Endpoints**:
  - **Products**: [https://run.mocky.io/v3/78b00e72-00c0-47b5-84f3-de42b02336a7](https://run.mocky.io/v3/78b00e72-00c0-47b5-84f3-de42b02336a7)
  - **Categories**: [https://run.mocky.io/v3/c893c10f-79a7-4e25-bf76-8aca2fe6dabb](https://run.mocky.io/v3/c893c10f-79a7-4e25-bf76-8aca2fe6dabb)

### Design Guidelines

Follow the design guidelines provided, including color schemes, fonts, and other style elements. Ensure that your implementation aligns closely with the provided mockups.

## Screens

### 1. Splash Screen

- **UI**:
  - Implement the splash screen according to the provided design.
  - The splash screen should only display UI elements with no additional functionality.

### 2. Home Screen

- **UI**:
  - Implement the home screen according to the provided design.
- **Functionality**:
  - **Search Component**: Implement functionality to navigate to the Search screen when the search component in the header or the search icon in the bottom tab is pressed.
  - **Cart Icon**: Implement functionality to navigate to the Cart screen when the cart icon is pressed.

### 3. Search Screen

- **UI**:
  - Implement the search screen according to the provided design.
- **Functionality**:
  - **Tab Management**: Render and manage products based on the selected tab in the UI. Ensure that the displayed products are filtered or updated according to the active tab.

### 4. Cart Screen

- **UI**:
  - Implement the cart screen according to the provided design.
- **Functionality**:
  - **Increase/Decrease/Delete Items**: Allow users to increase or decrease the quantity of items and delete items from the cart.
  - **Dynamic Total Cost**: Display the total cost dynamically based on the items in the cart.

## Development Requirements

1. **UI Development**:

   - Convert the provided design mockups into functional React Native screens.
   - Ensure the UI is responsive and adapts to various screen sizes.

2. **Navigation**:

   - Implement navigation between screens using a suitable navigation library, such as React Navigation.

3. **Offline Storage**:

   - Implement functionality to save user cart information offline using a suitable library such as Redux.

4. **Code Quality**:

   - Write clean, well-structured code and follow React Native best practices.

5. **Unit Tests**:

   - If possible, include unit tests using libraries such as Jest or React Native Testing Library for your components and functionality.

6. **Optional Enhancements**:

   - Add interactive elements for product cards.
   - Include additional features like product search filters or user reviews.
   - Provide brief documentation explaining your code structure, components used, and any libraries or tools.

## Submission Instructions

1. **Create a Repository**:

   - Complete your work in a new Git repository.
   - Ensure the repository is public.

2. **Email Your Submission**:

   - Email the link to your repository to tech@elcoach.me.
   - Use the subject line:
     ```
     RN-Challenge-App-[Your Name]
     ```

3. **Include Run Instructions**:
   - In your submission, please include detailed instructions on how to run your project, covering both iOS and Android platforms.

## Evaluation Criteria

- **Completeness**: Ensure all tasks are fully completed according to the requirements.
- **Code Cleanliness**: Write clean, well-organized code and follow best practices.
- **Reusability**: Structure your code to promote reusability of components and modules.
- **Scalability**: Ensure your codebase can scale with additional features and modules.
- **Performance**: Optimize the application for smooth performance.
- **Responsive Design**: Ensure the UI is responsive on various screen sizes.

**The output should be bullet-proof and production-ready. We would love to see your best display of Software Engineering through this sample work.**

---

Thank you for participating in the ElCoach-Tech challenge. We look forward to reviewing your work!
