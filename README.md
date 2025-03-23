# URL Shortener

An efficient and easy-to-use URL shortener that transforms long URLs into concise, shareable links, making it more convenient to distribute via social media, email, or messages.

## Features

- Quick and efficient URL shortening
- User-friendly and easy to set up
- Compatible with Windows, Mac, and Linux

## Installation

### 1. Download or Clone the Repository

First, download the project as a ZIP file or clone it using Git:

```sh
git clone https://github.com/Jahid-Hasan-96/URL-Shortener.git
```

Extract the ZIP file (if downloaded) and navigate to the project directory:

```sh
cd URL-Shortener
```

### 2. Set Up a Virtual Environment

A virtual environment helps to manage dependencies efficiently.

#### Install Virtual Environment

```sh
pip install virtualenv
```

#### Create a Virtual Environment

- **For Windows:**
  ```sh
  python -m venv venv
  ```
- **For Mac/Linux:**
  ```sh
  python3 -m venv venv
  ```

#### Activate Virtual Environment

- **For Windows:**
  ```sh
  venv/Scripts/activate.bat
  ```
- **For Mac/Linux:**
  ```sh
  source venv/bin/activate.bat
  ```

### 3. Install Dependencies

Ensure you have all necessary dependencies installed:

```sh
pip install -r requirements.txt
```

### 4. Prepare the Database

Before running the server, create the necessary database migrations and apply them:

```sh
python manage.py makemigrations
```

Before running the server, apply database migrations to set up the SQLite database:

```sh
python manage.py migrate
```

### 5. Run the Server

Start the development server using the appropriate command for your OS.

- **For Windows:**
  ```sh
  python manage.py runserver
  ```
- **For Mac/Linux:**
  ```sh
  python3 manage.py runserver
  ```

## Usage

Once the server is running, open your browser and navigate to:

```
http://127.0.0.1:8000/
```

From there, you can shorten URLs and manage them easily.

## Contributing

Feel free to fork this repository, make improvements, and submit a pull request!

---
