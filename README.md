# GrowMeOrganic PVT LTD React.js Assignment

# Task 1: Application Configuration
- Create a new React application using Typescript and Vite.
- If you are unfamiliar with Vite, please refer to the following link for more information: https://vitejs.dev/guide/
- Configure the application with MUI, ensuring that all components within the application (e.g. buttons, text fields, dialogs) use MUI components. If you are unfamiliar with MUI, please refer to the following link for more information: https://mui.com/material-ui/getting-started/overview/
  
# Task 2: First Page of the Application
- Create a form to collect the following information from the user:
- Name
- Phone number
- Email
- Upon completion, save the user details in localstorage and route the user to the second page.
- If the user attempts to access the second page without providing the necessary information, redirect them back to the first page with a message indicating that they 
must enter their details before accessing the page.

# Task 3: Second Page of the Application[Component 1]
- Fetch a list of JSON details from an API. You may use any API that returns a list of data. One example is https://jsonplaceholder.typicode.com/posts
- Convert the retrieved JSON data into a model/interface in Typescript. If you are unfamiliar with models or interfaces in Typescript, please refer to the following link for more information: https://www.educative.io/blog/typescript-interfaces
- Display the data in a table using the following package: https://mui.com/x/react-data-grid/
  
- Task 4: Second Page of the Application[Component 2]
- This component is the most important component, any error or issue within this component will discard your submission instantly.
- Create another component below the table from the given json(https://docs.google.com/document/d/1uQCFny5aXfMD9v2TPy3rbE8EHw-xZVdZfj4g-2Yv6IU/edit?usp=sharing) 
- You can hardcode the given json in your application
- The component will be the list of department and each department has sub departments
- Sub departments can be expanded and collapsed by the user
- There must be an icon on the right/left side of the department through which users can expand or collapse the sub departments.
- Example UI -

- You don’t need to be pixel perfect in terms of UI
- Users can select department or sub departments.
- If user select a department then all of the sub departments must get selected in the UI
- If user select all sub departments of a department then the parent department must get selected as well in the UI
- YOU’RE NOT ALLOWED TO USE ANY LIBRARY TO CREATE THIS COMPONENT APART FROM MUI(NOT EVEN MUI/TREE).
- You can find the relevant components of MUI from here.
- You can use components from the MUI library. 
- Note:
- The focus of this assignment is on the quality and robustness of your code, not the aesthetics of the UI.
- Clean code and proper file structure are important considerations.
- You are only allowed to use typescript to complete this assignment.

- Output Screenshots :-
  ![Screenshot (689)](https://github.com/sachindolase/GrowMeOrganic-React-Assignment/assets/125812863/095243af-e2ee-4234-aa5c-3161bd4757a3)
  ![Screenshot (690)](https://github.com/sachindolase/GrowMeOrganic-React-Assignment/assets/125812863/8f419be9-62ec-487b-82a0-3ec00dd847ca)
  ![Screenshot (691)](https://github.com/sachindolase/GrowMeOrganic-React-Assignment/assets/125812863/5de206f3-0605-4088-b1b4-cdb80fe6babe)
  ![Screenshot (692)](https://github.com/sachindolase/GrowMeOrganic-React-Assignment/assets/125812863/4c5fb3e6-fa9b-4d31-9ceb-9fb889c3cf55)
  ![Screenshot (693)](https://github.com/sachindolase/GrowMeOrganic-React-Assignment/assets/125812863/dcdaf8fd-bdec-4015-8190-2142ca26ddcf)
