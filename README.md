# Django_School_Management


## How to Run

To set up and run the project, follow these steps:

1. **Download and Extract:**
   - Download the project file and unzip it.
   - Navigate to the project’s root folder.

2. **Set Up a Virtual Environment (Recommended):**
   - Create a virtual environment to manage dependencies:
     ```bash
     python -m venv env
     ```
   - Activate the virtual environment:
     - **Windows:**
       ```bash
       .\env\Scripts\activate
       ```
     - **macOS/Linux:**
       ```bash
       source env/bin/activate
       ```

3. **Install Dependencies:**
   - Install the required packages using pip:
     ```bash
     pip install -r requirements.txt
     ```

4. **Apply Database Migrations:**
   - Run the following commands to set up your database schema:
     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```

5. **Run the Development Server:**
   - Start the Django development server:
     ```bash
     python manage.py runserver
     ```

6. **Access the Application:**
   - Open your preferred web browser.
   - Navigate to `http://127.0.0.1:[PORT_NUMBER]/` to view the application. (Replace `[PORT_NUMBER]` with the port number specified by the server, typically `8000`.)

7. **Admin Login Credentials:**
   - To access the admin interface, you need to create a superuser. Run:
     ```bash
     python manage.py createsuperuser
     ```
   - Follow the prompts to set up your admin credentials.

---

Feel free to adjust the port number or any other details specific to your project!
