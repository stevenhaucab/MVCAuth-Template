
## Description

MVCAuth-Template is a project template designed for developing APIs in PHP using the MVC (Model-View-Controller) architectural pattern. This project includes the implementation of secure authentication using JSON Web Tokens (JWT), enabling efficient and secure handling of user authentication and authorization in your applications.

### Features

- MVC Architecture: Project structure based on the Model-View-Controller pattern for clear separation of responsibilities and maintainable code.

- JWT Authentication: Implementation of authentication and authorization using JSON Web Tokens to ensure secure requests.

- CDotenv Configuration: Management of environment variables using the Dotenv package to facilitate configuration and deployment across different environments.

- Composer Autoloading: Use of Composer for class autoloading, simplifying dependency management and code organization.

- RESTful API: Structure prepared for developing RESTful APIs, following best practices in API design and development.

- Integrated Security: Implementation of security measures to protect the API against common attacks.

### Requisitos

- PHP 7.4 or higher
- Composer
- Web server (Apache, Nginx, etc.)
- Database (MySQL, PostgreSQL, etc.)






## Installation

Clone the repository:

```bash
  git clone https://github.com/stevenhaucab/MVCAuth-Template.git
```
Navigate to the project directory:

```bash
  cd MVCAuth-Template
```

Install dependencies using Composer:

```bash
  composer install
```

Configure environment variables by copying the .env.example file to .env and adjusting the values as needed:

```bash
  cp .env.example .env
```

Start the development server:

```bash
  php -S localhost:8000 -t public
```


## Usage

The template includes basic examples of controllers, models, and routes so you can start building your API right away. Check the documentation included in the project for more details on how to extend and customize the template to suit your needs.




## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. See the LICENSE file for more details.


