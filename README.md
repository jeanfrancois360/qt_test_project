
# Task Management System (TMS)

## Introduction
Welcome to the Task Management System (TMS) built using Frappe framework. TMS is a robust web-based application designed to streamline task management within organizations. With its intuitive user interface and powerful features, TMS simplifies task assignment, tracking, and collaboration, ultimately boosting productivity and efficiency.

## Features
### User Management Module
- **User Registration**: Easily add new users to the system with basic details and permissions.
- **User Authentication**: Secure login system with authentication mechanisms to protect user data.
- **User Roles and Permissions**: Assign roles and permissions to users based on their responsibilities within the organization.
- **User Profile Management**: Users can update their profile information and preferences.

### Task Management Module
- **Task Creation**: Create tasks with detailed descriptions, deadlines, priorities, and assignees.
- **Task Assignment**: Assign tasks to individual users or teams within the organization.
- **Task Tracking**: Track the progress of tasks through various stages from creation to completion.
- **Task Prioritization**: Set priority levels for tasks to ensure the most critical tasks are addressed first.
- **Task Comments and Attachments**: Collaborate effectively by adding comments and attaching relevant files to tasks.
- **Task Filters and Search**: Easily find and filter tasks based on various criteria such as status, priority, assignee, etc.
- **Task Reports**: Generate reports to analyze task performance, workload distribution, and productivity metrics.

## Getting Started
To set up the Task Management System on your server, follow these steps:

1. **Prerequisites**: Make sure you have the following prerequisites installed:
   - Python
   - Frappe framework
   - MariaDB database server

2. **Clone Repository**: Clone the TMS repository from GitHub to your local machine.

   ```sh
   git clone https://github.com/jeanfrancois360/qt_test_project.git
   ```

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies using pip.

   ```sh
   cd qt_test_project
   pip install -r requirements.txt
   ```

4. **Database Configuration**: Configure the database settings in the `site_config.json` file located in the `config` directory.

5. **Initialize Database**: Initialize the database schema and data by running the following commands:

   ```sh
   bench --site sitename install-app qt_test
   bench --site sitename migrate
   bench --site sitename qt_test.dev
   ```

   Replace `sitename` with the name of your Frappe site.

6. **Run Server**: Start the Frappe development server.

   ```sh
   bench start
   ```

7. **Access TMS**: Open a web browser and navigate to `http://localhost:8000` to access the Task Management System.

8. **Login**: Use the default administrator credentials to log in and start managing tasks.

## System Screenshots
<img width="1438" alt="Screenshot 2024-05-08 at 12 18 07" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/4327b2b1-9cdc-4dc5-a4a9-fa97b72afb1b">
<img width="1438" alt="Screenshot 2024-05-08 at 12 18 40" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/b774a8ca-6d29-4620-bc6f-237f542d6a3b">
<img width="1438" alt="Screenshot 2024-05-08 at 12 33 41" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/3f9a5d36-80d7-4d66-bbe7-764445cf4291">
<img width="1438" alt="Screenshot 2024-05-08 at 12 19 13" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/7e4c0b3c-8854-4bb2-825d-9408fdee870c">
<img width="1438" alt="Screenshot 2024-05-08 at 12 19 55" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/1dd3ef94-04b1-44b1-9b84-36461cf9ff57">
<img width="1438" alt="Screenshot 2024-05-08 at 12 20 08" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/84237bb5-ba10-42e0-8c15-0260d251e4bc">
<img width="1438" alt="Screenshot 2024-05-08 at 12 20 20" src="https://github.com/jeanfrancois360/qt_test_project/assets/23524232/b327e987-b63c-4068-b971-9e61a9aa7d73">


