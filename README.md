# Assessment for React Developer

<br>

This project is designed to test an examinee’s knowledge of Javascript/Typescript Design principles and its implementations on React Library.

**Assessment Point System**: The assessment total is 100 points with additional 50 bonus points.
Passing grade is 60.

| Points | Bonus | Total |
| -----: | ----: | ----: |
|    100 |    50 |   150 |

**Asessment Duration**: Examinee is given 4 days to complete the assessment.
For any questions regarding the exam please send inquiry to <a href="mailto: info@matrix-erp.sy"> info@matrix-erp.sy</a> or HR.

**Output**: The examinee is required to send a WhatsApp message containing two links: one for the demo and one for the code repository. The code must be uploaded to either GitHub or GitLab.
<br> Please send the message to <a href="https://wa.me/963989505074"> Matrix HR Whatsapp</a> or <a href="mailto: info@matrix-erp.sy"> info@matrix-erp.sy</a> or HR.

<br>
<hr>
<br>

## Project

### BaseUrl:

https://test-front.matrix-erp.sy

<br>

##### Pages

-  **+25 points** - _Login / Register_
-  **+25 points** - _Homepage_
-  **+25 points** - _Add / Update Post_
-  **+0 points** - _Admin Dashboard_

<br>

##### Code

-  **+5 points** - Protecting routes.
-  **+5 points** - Implementing robust validation.
-  **+5 points** - Efficient data fetching.
-  **+5 points** - Well-organized folder structure.
-  **+5 points** - Clean and maintainable code.

<br>

##### User Types

-  Quest user.
-  Admin user.
-  Authenticated User.

<br>

##### Goals

-  [ ] **Register and Login pages**.
-  [ ] **Homepage**: Display all posts with pagination, showing 5 posts per page. Pagination options include either navigation buttons or infinite scroll.
-  [ ] **Post Actions:** Each post should have "Edit" and "Delete" actions, which are visible based on the user’s role.
-  [ ] **Add/Update Posts:** Optional—this can be a dedicated page or a pop-up.
-  [ ] **Admin Dashboard:** An empty page contain paragraph `<p>Admin Dashboard</p>`

<br>

##### Instructions

1. Guest users (unauthenticated users) can only access the homepage, login, and register pages.
2. Access to the admin dashboard page is restricted to admin users only.
3. Admin users do not have access to the add post page but can edit or delete any existing post.
4. Regular users can only update or delete their own posts.

<br>

##### ✎ Notes

-  Style the pages using a preferred framework (e.g. tailwind, bootstrap, matrial ui, etc.).
-  All Parameters in login and register endpoints are required.
-  In the Add Post endpoint, title and description are required, image is optional. If an image is provided, it must be in JPG or PNG format and not exceed 1.5 MB in size.
-  Ensure that the description text in add/update post form remains simple and avoid using any text editor libraries, such as React Quill, for styling. Use a basic HTML field instead.
-  The Update Post endpoint should only include parameters with values that have changed.

<br>

##### ★ Bonus

-  **+25 points** - Implement the project using the `TypeScript language` for added type safety and better code maintainability.

-  **+7 points** - Leverage the `React Hook Form` library to streamline form handling.

-  **+4 points** - Integrate with a schema validation library of your choice (e.g., zod, yup, joi) to ensure robust data validation.

-  **+7 points** - Utilize the `Redux Toolkit` for efficient and organized state management.

-  **+7 points** - Employ Redux Toolkit Query for managing API requests and caching responses.

<br>
<hr>
<br>
