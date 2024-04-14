# P.O.W.
Parliament On Website
---

This repository contains the source code for the Parliament website, a web application designed to provide information about the constituencies of the Indian Parliament.

## Overview

The Parliament website allows users to view details about each constituency, including information about candidates, promises made, work done by winning candidates, and changes in their wealth during their tenure. The website also provides a candidate comparison feature for each constituency.

## Technologies Used

- **Django**: Django is used as the backend framework for implementing server-side logic and API endpoints.
- **Django REST Framework**: Django REST Framework is used to create RESTful APIs for fetching constituency data.
- **MongoDB**: MongoDB is used as the database backend for storing constituency data.
- **React**: React is used for building the frontend user interface, providing a dynamic and interactive user experience.
- **React Router**: React Router is used for client-side routing within the React application.
- **Axios**: Axios is used for making HTTP requests from the React frontend to the Django backend.
- **Bootstrap**: Bootstrap is used for styling the frontend components and ensuring responsiveness.

## Setup Instructions

1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/parliament-website.git
   ```

2. **Backend Setup**:
   - Navigate to the `backend` directory:
     ```
     cd backend
     ```
   - Install Python dependencies:
     ```
     pip install -r requirements.txt
     ```
   - Configure Django settings for MongoDB in `settings.py`.
   - Run migrations:
     ```
     python manage.py migrate
     ```
   - Start the Django development server:
     ```
     python manage.py runserver
     ```

3. **Frontend Setup**:
   - Navigate to the `frontend` directory:
     ```
     cd frontend
     ```
   - Install Node.js dependencies:
     ```
     npm install
     ```
   - Start the React development server:
     ```
     npm start
     ```

4. **Accessing the Website**:
   - Open your web browser and navigate to `http://localhost:3000` to access the Parliament website.

## Contributing

Contributions are welcome! If you'd like to contribute to the development of the Parliament website, please follow these steps:
- Fork the repository
- Create a new branch (`git checkout -b feature/your-feature`)
- Make your changes
- Commit your changes (`git commit -am 'Add new feature'`)
- Push to the branch (`git push origin feature/your-feature`)
- Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
