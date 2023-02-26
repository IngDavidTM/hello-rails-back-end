<a name="readme-top"></a>


<div align="center">

  <h1>David's project</h1>

</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Author](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello-rails-back-end <a name="about-project"></a>

**Hello-rails-back-end** is the backend part of a full-stack application built with rails as an api and react for the front end. This app show you a random message every time that you reload the page

Follow this [Link](https://github.com/IngDavidTM/hello-react-front-end) for the frontend repo

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>
<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
    <li><a href="https://rubyonrails.org/">Rails</a></li>
    <li><a href="https://reactjs.org/">React</a></li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **It contains one table with diferent messages**
- **Every time that page is reload the message change**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🚀 Live Demo <a name="live-demo"></a>

- Not available yet

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Basic knowledge of the command line.
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) installed on your device.
- [Ruby on Rails](https://guides.rubyonrails.org/v5.0/getting_started.html) installed on your device.
- Postgresql Database, you can follow this [link](https://www.postgresql.org/download/), choose your system & follow the provided instructions.
- Node.js installed to use ```npm```

### Setup

- Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone git@github.com:IngDavidTM/hello-rails-back-end.git
```

- Clone this repository **IN THE SAME** folder:

```sh
  cd my-folder
  git clone git@github.com:IngDavidTM/hello-react-front-end.git
```

### Install

- Navigate to forntend repo & run:
```sh
  npm i
```

- Navigate to the backend repo & run:
```sh
  bundle i
```

- Add the "foreman" gem globally using this command:
```sh
  sudo apt-get install foreman
```
**DON'T ADD THE FOREMAN GEM TO THE GEMFILE**

<hr>

### Usage

To run the project, follow these steps:

- Modify the "database.yml" file to adjust the username & password if needed

- Create database, run migration & populate the database **in the backend cloned repo**
```sh
  rails db:create
  rails db:migrate
  rails db:seed
```
- To run the project in your browser, run(in the backend terminal):
```sh
  foreman start
```

<hr>

### Run tests

- No tests provided at the moment

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Author <a name="authors"></a>

👤 **David Tamayo**

- GitHub: [@IngDavidTM](https://github.com/IngDavidTM)
- Twitter: [@David5TM](https://twitter.com/David5TM)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/ing-david-tamayo)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- Deployment

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Peter1907/hello-react-front-end/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Microverse for overseeing the project.
- Learning, Resarch & Dedication. 🚀

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
