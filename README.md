# Haiku Haven

Haik-Haven is a full-stack JavaScript application that allows users to create, read, update, and delete haikus. It features secure user authentication, image uploads with AI-powered enhancements, and a MongoDB backend.

## Features

- User authentication with bcrypt password hashing
- CRUD operations for haikus
- Image uploads to Cloudinary
- AI-powered image completion for cover images
- Responsive design for desktop and mobile devices
- Beautiful and consistent UI components with DaisyUI

## Tech Stack

- **Frontend**: React.js
- **UI Framework**: TailwindCSS with DaisyUI
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: bcrypt for password hashing
- **Image Storage**: Cloudinary
- **AI Image Processing**: Cloudinary AI capabilities

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- MongoDB (local installation or cloud service)
- Cloudinary account
- npm or yarn package manager

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/45beepy/Haiku-Haven.git
   cd Haiku-Haven
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Start the development server:
   ```
   npm run dev
   ```

## Usage

- Register a new account or log in with existing credentials
- Create new haikus by clicking the "New Haiku" button
- Upload an image for your haiku, and watch as AI fills in any blank spaces
- View, edit, or delete your haikus from your dashboard
- Explore haikus created by other users

## API Endpoints

- `POST /api/auth/register`: Register a new user
- `POST /api/auth/login`: Log in a user
- `GET /api/haikus`: Get all haikus
- `POST /api/haikus`: Create a new haiku
- `PUT /api/haikus/:id`: Update a haiku
- `DELETE /api/haikus/:id`: Delete a haiku
- `POST /api/upload`: Upload an image to Cloudinary

## Contributing

Contributions to Haiku-CRUD are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

## License

This project is licensed under the MIT License. See LICENSE for more details.

## Contact

If you have any questions or feedback, please open an issue on this repository or contact the maintainer through GitHub.

Happy haiku writing!
