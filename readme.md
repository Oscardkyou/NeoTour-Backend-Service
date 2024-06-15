# NeoTour-Backend-Platform 🎉

Welcome to the NeoTour-Backend-Platform project! This repository contains the backend code for the NeoTour application, an optimized platform for booking tours. The backend is built using Django and integrates Cloudinary for media storage.

## Features ✨

- User Authentication and Management 🔐
- Tour Management System 🏞️
- Booking System 📅
- Integration with Cloudinary for Media Storage ☁️
- API Documentation with Swagger 📜

## Installation and Setup 🚀

### Prerequisites

- Python 3.8+
- PostgreSQL
- Virtualenv

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/NeoTour-Backend-Platform.git
    cd NeoTour-Backend-Platform
    ```

2. **Create and activate a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Create a `.env` file in the root directory and add the following configuration**
    ```plaintext
    SECRET_KEY=your_secret_key
    DEBUG=True
    DB_NAME=your_db_name
    DB_USER=your_db_user
    DB_PASSWORD=your_db_password
    DB_HOST=your_db_host
    DB_PORT=your_db_port
    CLOUD_NAME=your_cloudinary_cloud_name
    API_KEY=your_cloudinary_api_key
    API_SECRET=your_cloudinary_api_secret
    CSRF_TRUSTED_ORIGINS=your_csrf_trusted_origins
    ```

5. **Run migrations**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Create a superuser**
    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server**
    ```bash
    python manage.py runserver
    ```

8. **Access the application**
    Open your browser and navigate to `http://127.0.0.1:8000`

## API Documentation 📚

The API documentation is available through Swagger. Once the development server is running, navigate to `http://127.0.0.1:8000/swagger/` to explore the API endpoints.

## Technologies Used 🛠️

- Django
- Django Rest Framework
- PostgreSQL
- Cloudinary
- Swagger

## Contributing 🤝

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact 📬

If you have any questions or suggestions, feel free to contact us at support@neotour.com.
