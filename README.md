# Note Taker Web Application

## Introduction

The **Note Taker** web application is a simple yet powerful tool for managing your notes. It allows users to create, edit, and delete notes, helping them stay organized and productive. This README provides an overview of the application's features, how to set it up, and use it effectively.

## Features

- **Add Notes:** Easily add new notes with a title and content.

- **Edit Notes:** Update and modify existing notes as your needs change.

- **Delete Notes:** Remove unwanted notes to keep your list tidy.

- **View All Notes:** Access and review all your notes in one place.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- [Java](https://www.java.com/en/download/)
- [Apache Tomcat](http://tomcat.apache.org/)
- [MySQL](https://dev.mysql.com/downloads/)
- [Hibernate](https://hibernate.org/)

### Installation

1. Clone the repository from GitHub.

   ```bash
   git clone https://github.com/Alokdey07/Note_Taker.git
   ```

2. Import the project into your favorite Java IDE.

3. Set up the database by running the SQL script provided in the project directory. You can use a tool like [phpMyAdmin](https://www.phpmyadmin.net/) or the MySQL command line to execute the script.

4. Update the Hibernate configuration file, `hibernate.cfg.xml`, with your database connection details.

### Running the Application

1. Deploy the application on your Apache Tomcat server.

2. Access the application by visiting `http://localhost:8080/note-taker` in your web browser.

## Usage

1. **Home Page:** Upon accessing the application, you'll be greeted with the home page. Click the "Start Here" button to begin.

2. **Add Notes:** Fill in the title and content of your note and click "Add." Your note will be saved, and you'll receive a confirmation message.

3. **View All Notes:** Navigate to the "Show Note" page to see a list of all your notes. Here, you can also edit or delete notes.

4. **Edit Notes:** Click the "Update" button next to a note to edit its title and content. Save your changes to update the note.

5. **Delete Notes:** To remove a note, click the "Delete" button next to the note you want to delete.

## SEO-Friendly URL

This application utilizes clean and user-friendly URLs for better search engine optimization (SEO). For example, the URL for viewing all notes is `/all_notes.jsp`, making it easy for search engines to index your content.

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request. Please follow the [contributing guidelines](CONTRIBUTING.md) for this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or need assistance, please don't hesitate to contact us at [alokdeykv@gmail.com].

Happy note-taking!

![Note Taker](img/note.png)

