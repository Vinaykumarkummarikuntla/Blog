# Blog Application

## Description

Blog Application is a comprehensive web application developed using the Django framework. It allows users to create, read, update, and delete blog posts, as well as interact with other users through comments and tags. The application provides a visually appealing and user-friendly interface implemented using HTML, CSS, JavaScript, and Bootstrap. The back end is designed using an SQLite3 database to efficiently store and manage data.

## Features

- **User Authentication:** Users can register, log in, and log out to manage their blog posts and interact with other users.
- **Blog Posts:** Users can create, view, edit, and delete their blog posts. Each blog post includes a title, content, and a timestamp indicating when it was published.
- **Comment Box:** Users can leave comments on blog posts to share their thoughts and engage in discussions.
- **Pagination:** Blog posts are paginated to enhance the browsing experience and allow users to navigate through multiple pages of posts.
- **Link Tags:** Blog posts can be tagged with relevant keywords or topics to facilitate categorization and improve searchability.
- **Email Send and Receive:** Users can send and receive emails related to their blog posts, such as notifications for new comments or password reset requests.

## Installation

To run the Blog Application locally, follow these steps:

1. Clone the repository:
`git clone https://github.com/Vinaykumarkummarikuntla/blog-application.git`

2. Change into the project directory:
`cd blog-application`

3. Install the required dependencies using pip:
`pip install -r requirements.txt`

4. Run database migrations to set up the SQLite3 database:
`python manage.py migrate`

5. Start the development server:
`python manage.py runserver`

6. Access the application through a web browser by navigating to `http://localhost:8000`.

## Usage

1. Register a new user account or log in with an existing account.
2. Create, edit, or delete blog posts from the user dashboard.
3. View blog posts from the homepage or by navigating through the paginated pages.
4. Leave comments on blog posts and engage in discussions.
5. Add relevant tags to blog posts for better organization and searchability.
6. Receive email notifications for activities related to your blog posts.

## Contributing

Contributions to the Blog Application project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request to the project repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.





