

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).



In the project directory, you can run:


Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

React and TailwindCSS were used in the development of the totally front-end,
browser-based ENTNT Equipment Rental Management Dashboard. It uses
localStorage for all data storage and mimics an equipment rental system for
administrators, employees, and customers.
 Login-based access, equipment inventory, rental booking,
maintenance logs, calendar view, KPI charts, and local storage durability are some
of the primary features.

Technologies and Libraries Used
- React (Frontend framework)
- TailwindCSS (Styling)
- React Router (Routing between pages)
- Recharts (Visual charts: pie and bar)
- react-calendar (Calendar UI)
- localStorage (Browser-based data persistence)

Step-by-Step Implementation
Step 1: Set up React App with TailwindCSS - Created using create-react-app -
TailwindCSS configured with postcss
Step 2: Bootstrap Data: To preload users and equipment in localStorage, use
bootstrapData.js.
Step 3: LoginPage.jsx authentication
- Local login with localStorage's predefined users
Step 4: Dashboard (DashboardPage.jsx)
- Role-based conditional routing - Equipment, Rentals, Maintenance, Charts, and
Calendar sections
Step 5: Feature Components: Rental Form and Rental List; Maintenance Form and
Maintenance List; Equipment Form and Equipment List; Rental Calendar; KPI
Cards and Charts
Step 6: Utilities
- The helper methods in localStorageUtils.js emulate backend

Sample Users

Admin:admin@entnt.in /password: admin123
Staff: staff@entnt.in / password: staff123
Customer: customer@entnt.in / password: cust123

Screenshots.

![Screenshot (47)](https://github.com/user-attachments/assets/9b6ea011-2896-45cd-823a-04972e62a8bb)

![Screenshot (46)](https://github.com/user-attachments/assets/23fee9c2-35f2-46be-a2a0-65a0ff33469c)

![Screenshot (45)](https://github.com/user-attachments/assets/f0a069c1-6896-463e-aad0-ea0e1926bdff)

![Screenshot (44)](https://github.com/user-attachments/assets/25b77d46-28c9-4f0f-af20-bb82a46e8122)

![Screenshot (43)](https://github.com/user-attachments/assets/d9d8818c-f2da-4fd5-851e-df74b0f69b23)


Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.



Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.





If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.




This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
