# EduVerse

EduVerse is an interactive web application designed to revolutionize learning by integrating immersive 3D models and fostering student engagement. The platform allows users to explore educational content in a dynamic 3D environment, featuring secure user authentication, real-time communication, and customizable learning experiences.
Live Link - https://eduverse-frontend.onrender.com/ 
## Features

- **Immersive 3D Learning:** Built with React-three-fiber and Three.js, offering engaging 3D models to enhance understanding.
- **Secure Authentication:** Implemented using JWT for user data protection.
- **Real-Time Communication:** Includes group and personal chat functionality powered by Socket.io.
- **Interactive Player Movement:** Logic developed to enable seamless player interactions in the 3D environment.
- **User-Friendly Design:** Intuitive front-end interface designed for an optimal learning experience.
  

## Technologies Used

- **Front-End:** React.js, React-three-fiber, Three.js
- **Back-End:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Real-Time Communication:** Socket.io
- **Development Tools:** VS Code, Postman, Git

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/rajeev210403/EduVerse.git
   ```
2. Navigate to the project directory:
   ```bash
   cd EduVerse
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     MONGO_URI=<your_mongodb_connection_string>
     JWT_SECRET=<your_jwt_secret>
     ```
5. Start the development server:
   ```bash
   npm start
   ```
6. Open the application in your browser at `http://localhost:3000`.

## How to Use

1. **Sign Up/Login:** Create an account or log in with your credentials.
2. **Explore 3D Models:** Navigate through interactive 3D environments to access educational content.
3. **Chat with Experts:** Use the real-time chat feature to connect with subject experts and peers.
4. **Move Your Player:** Interact with the 3D environment using player movement controls.

## Project Highlights

- Reduced learning barriers by introducing immersive 3D content.
- Developed secure and scalable web application architecture.
- Enhanced real-time collaboration through chat and interactive features.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or collaboration, feel free to reach out:

- Rajeev Thota  
  [Portfolio](https://portfolio-one-omega-77.vercel.app/)  
  [GitHub](https://github.com/rajeev210403)  
  [LinkedIn](https://www.linkedin.com/in/rajeev-thota/)
