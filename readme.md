# Deployed Blog

This is a deployed blog project created using Python and Django.

## Features

- User authentication
- Create, read, update, and delete blog posts
- Comment on blog posts
- Responsive design

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/deployed-blog.git
    ```
2. Navigate to the project directory:
    ```bash
    cd deployed-blog
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Apply the migrations:
    ```bash
    python manage.py migrate
    ```
2. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```
3. Run the development server:
    ```bash
    python manage.py runserver
    ```
4. Open your web browser and go to `http://127.0.0.1:8000/` to see the blog.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact jochananalberts@gmail.com.

