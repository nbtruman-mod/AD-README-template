Contributors:
- Example Name [GitHub](https://example.com/) [GitLab](https://example.com/)

# Project Title
<!-- Project Description -->
This is where you write a sentence or two about what this project is for or does. Try to answer:
- what problem does it solve
- who is it for
- why does it exist

## Features
<!-- 
  Outline the high-level user-visible features of the project. 
  This is a good place to talk about something you're really proud of. 
-->
- This template has useful links to take you back to the top!.

## Technical Overview
<!-- This section contains all the information about how the system/program/script works -->

### Built With:
<!-- 
  Use this space to tell people what technology and tools you used. 
  Remove or replace as needed. 
-->
* Frontend: React / Vue / Angular (choose what applies)
* Backend: Node.js / Laravel / .NET (choose what applies)
* Styling: CSS / Tailwind / Bootstrap

### Project Structure
<!--
  Include a high-level overview of the project directory layout.
  Focus on key directories that new developers need to understand.
  Avoid listing every file.
-->
```text
.
├── public/                 # Publicly accessible files (web root)
│   ├── index.php           # Application entry point
│   ├── assets/             # Images, CSS, JS, fonts
│   └── uploads/            # User-generated content (if applicable)
│
├── src/                    # Application source code
│   ├── controllers/        # Request handling / routing logic
│   ├── models/             # Data and domain logic
│   ├── services/           # Reusable business or integration logic
│   └── utils/              # Helper functions and shared utilities
│
├── config/                 # Configuration files
│   ├── app.php
│   ├── database.php
│   └── env.example.php
│
├── storage/                # Files written at runtime
│   ├── logs/
│   ├── cache/
│   └── tmp/
│
├── tests/                  # Automated tests
│
├── scripts/                # Utility or maintenance scripts
│
├── README.md
└── LICENSE

```
[Back to top](#project-title)

<!-- GETTING STARTED -->
## Getting Started
<!-- This is an example of how you may give instructions on setting up your project locally. -->
To get a local copy up and running follow these simple example steps.

### Prerequisites
<!-- 
  This section should detail everything required for the system/program/script to run. 
  Consider a disaster recovery scenario where the code has to run on a machine being set up from scratch. 
-->
The following software provides examples of what must be installed on the host machine:

- Apache 2.x
- PHP 7.x
- MySQL
- Git

#### PHP Extensions
<!-- List any extensions your project requires, even if they are enabled by default. -->
Ensure the following PHP extensions are enabled:

- mysqli/PDO
- json
- curl
- openssl
- xml

You can check installed extensions with:
```sh
php -m
```

#### Shared Libraries
<!--
  Detail any libraries the project requires and where the project expects to find them.
  If they are internal libraries with a repo we maintain, consider adding a hyperlink to that repo.
-->
This project requires:

```text
├── var/
│   └── www/
│       └── html/
│           └── libraries_php/                 
│               ├── a_library/         # Does something useful
│               └── another_library/   # Also does something useful
```

### Installation
<!-- 
  Provide fool-proof instructions of how to get this repo installed on a target machine. 
  Consider that it's most likely a repo will be cloned to a VM, then will need to be moved to a web server.
-->
1. Clone the repo
   ```sh
   git clone https://github.com/nbtruman-mod/AD-README-template
   ```
2. Transfer the folder to a web server with FileZilla
   ```text
   /www/var/html/applications/AD-README-template
   ```

[Back to top](#project-title)

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)

[Back to top](#project-title)

<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/nbtruman-mod/AD-README-template/issues) for a full list of proposed features (and known issues).

[Back to top](#project-title)

<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[Back to top](#project-title)

<!-- CONTACT -->
## Contact

Your Name - email@email_client.com

Project Link: [https://github.com/nbtruman-mod/AD-README-template](https://github.com/nbtruman-mod/AD-README-template)

[Back to top](#project-title)
