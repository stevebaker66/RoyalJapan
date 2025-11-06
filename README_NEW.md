
> # Online Store with Cryptocurrency Integration

> ## Getting started
> 
> The project is a monorepo structure with a `frontend` (React/Next.js) and a `backend` (Django) directory.
> 
> ### 1. Backend Setup (Django)
> 
> #### Install Backend Dependencies
> 
> The backend is a Django project and requires Python dependencies. It is highly recommended to use a virtual environment.
> 
> ```bash
> # Navigate to the backend directory
> cd backend
> 
> # Create and activate a Python virtual environment
> python3 -m venv venv
> source venv/bin/activate
> 
> # Install the required dependencies
> pip install -r requirements.txt
> ```
> 
> #### Database Setup
> 
> The project uses a database (defaulting to SQLite for development).
> You must run migrations to set up the database schema.
> 
> ```bash
> # Ensure the virtual environment is active
> source venv/bin/activate
> 
> # Apply database migrations
> python manage.py migrate
> ```
> 
> #### Run the Backend Server
> 
> ```bash
> # Ensure the virtual environment is active
> source venv/bin/activate
> 
> # Start the Django development server
> python manage.py runserver
> ```
> 
> ### 2. Frontend Setup (React/Next.js)
> 
> #### Install Frontend Dependencies
> 
> Open a new terminal window, and run the following command to install the frontend dependencies:
> 
> ```bash
> cd frontend
> ```
> 
> ```bash
> npm install
> ```
> 
> #### Run the Frontend Server
> 
> After installing the frontend dependencies, run the following command in the same terminal to start the frontend server:
> 
> ```bash
> npm run dev
> ```
