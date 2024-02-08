<a name="readme-top"></a>

<h1>Address Book!</h1>

[contributors-shield]: https://img.shields.io/badge/contributors-_1-blue?style=for-the-badge
[contributors-url]: https://github.com/drewkybrown/Address-Book/graphs/contributors

![](./address_book/screenshots/home.png)

<br />

<!-- TABLE OF CONTENTS -->
<details>
    <summary>Table of Contents</summary>
    <ul>
        <li><a href="#about-the-project">About The Project</a></li>
        <li><a href="#screenshots-and-wireframe">Screenshots</a></li>
        <li><a href="#technologies-used">Technologies Used</a></li>
        <li><a href="#getting-started">Getting Started</a></li>
        <li><a href="#key-features">Key Features</a></li>
        <li><a href="#next-steps-and-future-enhancements">Next Steps and Future Enhancements</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</details>

## About the Project

I have developed a fully-featured Django address book application that incorporates complete CRUD (Create, Read, Update, Delete) functionalities, designed to manage contact information effectively. This application stands out due to its utilization of a robust stack of technologies and deployment on Heroku, making it accessible anywhere.

## Screenshots 

![](./address_book/screenshots/home.png)
![](./address_book/screenshots/edit_address.png)
![](./address_book/screenshots/add_address.png)



## Technologies Used

![Django](https://img.shields.io/badge/Django-5.0.2-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2.9.9-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-21.2.0-%2349B382.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%23E34F26.svg?style=for-the-badge&logo=sql&logoColor=white)


## Getting Started

🚀 Explore Address Book!!: https://agile-meadow-70697-aedee706a193.herokuapp.com/


## Key Features

## Full CRUD Functionality
- Create: I can add new entries to my address book, capturing essential details like name, email, phone number, address, city, state, and zipcode.
- Read: I enable users to browse through all stored contacts in the address book, with options to view detailed information for each contact.
- Update: I provide the capability to edit the information of existing contacts, ensuring the address book remains up-to-date.
- Delete: I allow users to remove outdated or unnecessary contacts, maintaining the relevance and cleanliness of the database.

##Responsive Web Interface
- My application features a responsive web design, utilizing Django templates potentially enhanced with Bootstrap for styling. This ensures a seamless user experience across different devices and screen sizes.

## Database Integration with PostgreSQL
- Leveraging `psycopg2` and `dj-database-url`, my app connects to PostgreSQL for robust and secure data storage. This choice supports the efficient management of the address book's data, offering scalability and reliability.

## Environment and Configuration Management
- Through the use of `python-decouple` and `python-dotenv`, I manage environment variables and application configurations outside the codebase. This practice enhances the security of my application by safeguarding sensitive information such as database credentials.

## Deployment Ready for Heroku
- My address book application is deployed on Heroku, made seamless by `django-heroku` and `gunicorn`. `Whitenoise` serves static files efficiently, ensuring optimal performance. The deployment process is streamlined, making the application accessible from anywhere with internet access.

## Asynchronous Support
- With `asgiref`, my application supports asynchronous operations, which enhances its performance by enabling non-blocking database calls and potentially integrating external API requests efficiently.

These features demonstrate the capabilities and flexibility of my Django address book application, highlighting my focus on creating a user-friendly, secure, and accessible tool for managing contact information.

## Next Steps and Future Enhancements

1. Enhanced Search and Filtering:** Introduce advanced search capabilities with autocomplete suggestions to quickly find specific contacts.
2. User Authentication and Authorization:** Implement secure signup, login, and access control to protect user data and ensure privacy.
3. Contact Grouping and Tags:** Enable users to categorize and tag contacts for easier organization and retrieval.
4. Data Export and Import:** Facilitate the seamless migration of contact data across platforms with support for common file formats like CSV and JSON.
5. Account Recovery Options:** Provide secure methods for users to recover access to their accounts, enhancing trust and security.

## Contact

Andrew Brown </br>
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brown-k-andrew/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
