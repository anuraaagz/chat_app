
# Talk-Trove

Talk-Trove is a modern chatting web application that leverages the power of the MERN (MongoDB, Express, React, Node.js) stack. It boasts a user-friendly interface crafted with React frameworks such as Chakra UI for stunning UI/UX design. This application incorporates Socket.io, a powerful npm module, enabling seamless real-time communication among users. The combination of these technologies ensures a smooth and interactive experience for users engaging in dynamic conversations.


## Tech Stack

**MERN Stack:**
The MERN stack is a       powerful and comprehensive  set of technologies that forms the backbone of Talk-Trove:

  - **MongoDB:** As a NoSQL database, MongoDB provides flexibility and scalability, allowing Talk-Trove to manage and store user data efficiently. Its schema-less design enables seamless integration with Node.js and facilitates handling of real-time data updates for chat conversations.

  - **Express:** Talk-Trove utilizes Express, a minimal and fast web application framework for Node.js. Express simplifies the process of building robust APIs and handling HTTP requests, enabling smooth communication between the frontend and backend of the application.

  - **React:** React plays a pivotal role in Talk-Trove's frontend development. Its component-based architecture and virtual DOM make the user interface highly responsive and dynamic. React's efficient rendering ensures a seamless chat experience by updating only the necessary components when new messages arrive, enhancing the overall performance.

  - **Node.js:** The server-side runtime environment of Node.js powers Talk-Trove's backend, allowing for scalable and asynchronous event-driven architecture. Node.js enables handling multiple concurrent connections efficiently, facilitating real-time communication through Socket.io for instant messaging capabilities.

**Chakra UI:**
  
  - **Chakra UI:** Leveraging Chakra UI within the React framework, Talk-Trove delivers a visually appealing and user-friendly interface. Chakra UI's comprehensive component library simplifies the design process, ensuring accessibility, responsiveness, and aesthetic appeal throughout the application.

**Socket.io:**
  - **Socket.io:** As a crucial npm module, Socket.io facilitates real-time, bidirectional communication between clients and the server. It enables instant message delivery and updates in Talk-Trove's chat feature, ensuring seamless and responsive conversations among users.

The synergy of these technologies within the MERN stack, coupled with the integration of Chakra UI for UI/UX design and Socket.io for real-time communication, empowers Talk-Trove to offer a robust, interactive, and efficient chatting web application experience to its users.



## Features
Talk-Trove encompasses a range of functionalities designed to create an immersive and user-friendly chatting experience:

**User Authentication:**
- **Signup and Sign-in:** Users can securely create accounts and sign in using their email and password credentials, ensuring data privacy and access control.

- **JWT Authentication:** Implements JSON Web Token (JWT) authentication to verify and authenticate users, ensuring secure access to the application's features.

**Chatting Functionalities:**
- **One-to-One Chatting:** Users can engage in private conversations with other users in real-time, ensuring privacy and direct communication.
- **Group Chatting:** Facilitates group chats, enabling multiple users to communicate simultaneously within a shared conversation space.
- **Managing Group Chats:** Admins have the ability to remove other participants from group chats, leave group chats, and modify the name of group chats, enhancing control and customization options.
- **Real-Time Notifications:** Users receive instant notifications for new messages, ensuring they stay updated and engaged in ongoing conversations.
- **Typing Indicator:** Displays typing indicators, providing real-time feedback to users when others are composing or replying to messages, enhancing the interactive chatting experience.

**Additional Features:**
- **Responsive Design:** Ensures seamless user experience across various devices, including desktops, tablets, and mobile phones.

- **Search Functionality:** Enables users to search through conversations, messages, or users within the application, facilitating easy navigation and information retrieval.

- **Emojis and Rich Text Support:** Integrates emojis and supports rich text formatting for enhanced expression and communication.
## Getting Started 
Follow these instructions to get a copy of Talk-Trove up and running on your local machine for development and testing purposes.

**Prerequisites**
- Node.js and npm installed on your machine.
- MongoDB installed locally or configured connection to a MongoDB instance.

**Installation**

1. Clone the repository

```bash
git clone git@github.com:anuraaagz/mern-estate.git
```
2. Go to the project directory and install dependencies for both the client and server
- For Server  
```bash
npm install
```  
 - For Frontend
 ```bash
 cd frontend/
npm install
```
3. Start the server
```bash
npm start
```
4. Start the client
```bash
cd frontend/
npm start
```

## Usage
- SignIn/SignUp Page
  ![Screenshot 2024-01-07 184638](https://github.com/anuraaagz/chat_app/assets/121785178/85cdc29b-0fea-4311-91f5-b44fbd122920)

- Search Users
  ![Screenshot 2024-01-07 191226](https://github.com/anuraaagz/chat_app/assets/121785178/42254862-d87f-47bd-9555-fac0365a7bce)

- Create Group Chat
  ![Screenshot 2024-01-07 191308](https://github.com/anuraaagz/chat_app/assets/121785178/30461365-566f-40cb-8870-2bbae766cc73)

- Remove user From Group Chat/ Leave Group Chat
  ![Screenshot 2024-01-07 191824](https://github.com/anuraaagz/chat_app/assets/121785178/60fb837e-d80b-4b0d-abf6-3de035175c18)

- Real Time Chatting With Typing Indicator
  ![Screenshot 2024-01-07 192416](https://github.com/anuraaagz/chat_app/assets/121785178/66ec49b0-8e23-4bda-a4fe-f9266c6e3a5c)

- Notification Centre
  
  ![Screenshot 2024-01-07 192253](https://github.com/anuraaagz/chat_app/assets/121785178/f5f72241-842f-425f-8273-99cbcee893dd)

- Group Chatting
  ![Screenshot 2024-01-07 193055](https://github.com/anuraaagz/chat_app/assets/121785178/7a4ec990-d92a-438d-a02b-0ed557d74dde)

- Profile Modal
  ![Screenshot 2024-01-07 190451](https://github.com/anuraaagz/chat_app/assets/121785178/55b7020b-ad80-427f-b949-0eb40466f464)

  
