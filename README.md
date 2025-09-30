📚 Vandana E-Learning Platform Prototype
"शिक्षित भारत, विकसित भारत।" (Sikhshit Bharat, Viksit Bharat.)
Vandana is a prototype for a single-page interactive e-learning platform designed to connect local school teachers and students. Its primary goal is to provide a child-friendly, engaging, and trackable environment for accessing local class content and monitoring academic progress.
This application is a static, interactive mockup built within a single HTML file, demonstrating the proposed Information Architecture and User Experience (UX) flow.


🚀 Key Features

The prototype is built as a Single Page Application (SPA) with dynamically rendered sections based on user role and navigation:

1. Dual User Portals: A visible User Role Toggle allows seamless switching between the Student view and the Teacher view.
2. Interactive Learning Tree: Content (lessons/chapters) is visualized using a tree structure metaphor on the Student Home page. Subjects are the main trunk, chapters are branches, and lessons are leaves. Completed lessons are visually marked with rewards (flowers/fruit).
3. Functional Search: A working search bar allows students to filter content by Topic Name or Content Writer. It displays a "NO Content Found" message if no results match.
4. Teacher Dashboard: The Teacher Portal features dynamic Chart.js visualizations to track:
    . Overall Classroom Progress (Bar Chart).
    . Individual Student Progress by Subject (Horizontal Bar Chart).
5. Responsive Profile Views: The My Account section dynamically displays detailed, role-specific profile information for the mock Student and Teacher users.

   
📐 Information Architecture & Design Philosophy
The application uses an SPA approach to ensure a smooth, app-like experience without page reloads, which is better for student engagement.

1. Structure: Content is not organized strictly by the original report's layout but by user role and function (Home/Content Exploration, My Account/Profile, Teacher Portal/Management).
2. Aesthetics: A Vibrant Learning color palette (Sky Blue, Leaf Green, Sunny Yellow) is used throughout, along with rounded corners and clean typography, ensuring the platform is inviting and child-friendly.
Content Visualization: The Learning Tree is the key interactive element for content organization, replacing standard menus with a visually rewarding hierarchy. Progress data in the Teacher Portal is clearly conveyed via Chart.js for effective comparison and tracking.


💻 Technical Stack
This is a self-contained, dependency-managed prototype for maximum portability.
Component                         Technology                                   Purpose
Structure & Logic             Vanilla JavaScript                 Core navigation, state management (currentUserRole), search handling, and Tree interactivity.
Styling & Layout              Tailwind CSS (CDN)                 Fully responsive, mobile-first design and clean professional aesthetics.
Data Visualization             Chart.js (CDN)                    Generating dynamic, responsive bar charts for progress tracking.
Base Data                     JavaScript Objects/Arrays          Storing mock user data and content hierarchy (learningContent).

▶️ How to Run the Prototype
 Since this is a single HTML file, no server or build steps are required.
1. Save the code as vandana_platform.html.
2. Open the file directly in any modern web browser (Chrome, Firefox, Edge, etc.).
All navigation and interactive elements are handled by the embedded JavaScript.

▶️ A video of the prototype -
https://1drv.ms/v/c/6c1cf0da3c7d1d8b/EZnAFHV9Fz5EmIV1oeYi8I8BQ_0Zrorur3schlWTcG_FiQ


