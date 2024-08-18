<h1 style="color: #5b14c7; font-weight: 1000;">Nxt Watch</h1>

In this project, I have developed **Nxt Watch**, an application that offers a seamless and immersive video watching experience. Users can log in and access a wide variety of video content with features such as trending videos, gaming content, and saved videos. The app also provides a detailed view of individual videos with like, dislike, and save functionalities.

### Link: https://NxtWatch99.ccbp.tech

The key components and functionalities of this project include:

- **User Interface**: I created distinct pages for Login, Home, Trending, Gaming, Saved Videos, and Video Item Details using React components. These components leverage React's capabilities for handling props, state management, event handling, and form inputs.
- **Authentication**: Users can log in by providing their username and password. The application performs an HTTP API call for login authentication. Upon successful login, a JSON Web Token (JWT) is generated and stored in the client's storage. This token is subsequently included in the headers of API requests to authorize the user.
- **Routing**: To ensure a seamless user experience, I implemented routing using React Router components such as Route, Switch, and Link. This enables users to navigate between the Login, Home, Trending, Gaming, Saved Videos, and Video Item Details pages with ease.
- **Theme**: The application supports both light and dark themes. The theme can be toggled using a button in the header.
- **Error Handling**: The application displays appropriate error messages when invalid login credentials are provided or when there are issues with API requests.
- **Protected Routes**: Routes such as Home, Trending, Gaming, Saved Videos, and Video Item Details are protected and require authentication. Unauthenticated users are redirected to the Login page.
- **Filtering and Search**: Users can search for videos on the Home page using a search input. The search query is sent as a query parameter in API calls to retrieve specific video listings.
- **Security**: Protected routes ensure that only authenticated users can access certain pages. JWT tokens are used for authorization in API requests.

**Technologies used**: React JS, JS, CSS, Routing, REST API Calls, Local Storage, Cookies, JWT Token, Authorization, Authentication

In summary, Nxt Watch is a comprehensive video platform that leverages React's capabilities for creating a dynamic and secure user experience. It offers features like user authentication, video filtering, theme toggling, and seamless navigation while providing a rich video watching experience.

