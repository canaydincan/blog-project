<h1 align="center">Blog Web App</h1>

A Django-based blog application where users can create, edit, and delete posts, as well as comment on them. The project is designed to be easily extensible and customizable.

![githubpage](https://github.com/user-attachments/assets/d4bbd2c3-f63a-4fde-a9d4-ba2a4e891f88)

## Live Link: Coming Soon...

## Table of Contents
- [Tech Stack](#tech_stack)
- [Installation](#installation)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## 💻 Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%2523E34F26.svg?style=for-the-badge&logo=css3&logoColor=white&color=blue)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

## Installation

Follow the steps below to set up and run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/canaydincan/blog-project.git

2.  Install the dependencies:
    ```bash
    pip install -r requirements.txt

3.  Apply the migrations:
    ```bash
    python manage.py makemigrations
    python manage.py migrate

4.  Create a superuser:
    ```bash
    python manage.py createsuperuser

5.  Run the development server:
    ```bash
    python manage.py runserver

6.  Access the application: Open your browser and go to [localhost](http://localhost:8000/)

## Features

The blog-project Django Web App offers the following features:

- **User Authentication**: Users can sign up, log in, and manage their profiles.
- **Post Management**: Authenticated users can create, edit, and delete blog posts.
- **Comment System**: Users can comment on posts and engage in discussions.
- **Search Functionality**: Search for posts by title or content.
- **Responsive Design**: The application is responsive and works well on all device sizes.
- **Admin Panel**: Fully featured admin panel for managing users, posts, and comments.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make your changes.
4. Commit your changes (git commit -m 'Add some feature').
5. Push to the branch (git push origin feature/your-feature-name).
6. Open a pull request.
7. Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License, which is a permissive open-source license. Below is a summary of the key points of the license:

- **Permission is granted to use, copy, modify, and distribute** the software for any purpose, as long as the following conditions are met:
  - The above copyright notice and this permission notice shall be included in all copies or substantial portions of the software.

- **The software is provided "as is"**, without any warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

- **In no event shall the authors or copyright holders be liable** for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

- **You are free to use** this software in both open and closed source projects, as well as commercial projects, without any cost or restrictions.

For more detailed information, please refer to the full text of the MIT License, which can be found in the [LICENSE](LICENSE) file in this repository.

### Why Choose MIT License?

The MIT License is a popular choice for many developers because it is simple and flexible. It allows you to use the software in almost any way you want, with minimal restrictions. This makes it an ideal choice for open-source projects, where collaboration and sharing are encouraged.

By using the MIT License, you're making your code available to the broader community, allowing others to learn from it, build upon it, and contribute to it, all while retaining credit for your work.
