<h3 align="center"><b>Hello Rails-React</b></h3>

<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)


# 📖 Hello Rails-React <a name="about-project"></a>

The **Hello Rails-React** is a student project. The goal is to integrate the React front-end with the Rails back-end for one versatile monolithic app that can be hosted from a single source.
While there are different ways to achieve this, in **Hello Rails-React** I use Webpack with `jsbundling-rails` gem (this approach is recommended by [DHH](https://world.hey.com/dhh/rails-7-will-have-three-great-answers-to-javascript-in-2021-8d68191b): "It's this path you should probably pick if you're going all-in on something like React with JSX or another JavaScript framework that demands a transpilation step").


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/ru/docs/Web/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/ru/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/ru/docs/Web/JavaScript">JavaScript</a></li>
    <li><a href="https://react.dev/">React</a></li>
    <li><a href="https://redux-toolkit.js.org/">Redux Toolkit</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>


### Key Features <a name="key-features"></a>

- **use Ruby on Rails for back-end of the project**
- **use React framework for front-end of the project**
- **develop project in one repository**

<!-- GETTING STARTED -->
## Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites
In order to run this project, you need:
- A basic understanding of Ruby, Ruby on Rails, and Git

### Setup

Clone this repository to your desired folder:

Login to your GitHub account. Clone this repository to your desired folder:

> cd my-folder
> git clone git@github.com:Zilola-Nazarova/hello-rails-react.git

Setup database:

Update [config/database.yml](./config/database.yml) username and password

OR

Create a user (provide the username and password described in [config/database.yml](./config/database.yml)):
> sudo -u postgres createuser --interactive --pwprompt


### Install

Install the dependencies:
> gem install
> npm install

Create database:
> bin/rails db:create

Fill the database with sample records:
> bin/rails db:seed

### Usage

To run the server:
> ./bin/dev

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


## 👥 Authors <a name="authors"></a>

👤: **Antoine Makdessy**

- GitHub: [@ANTOINE1128](https://github.com/ANTOINE1128)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/antoine-makdessy/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **Advanced UI**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/ANTOINE1128/Budget-app/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

Please support this project and be a part of something meaningful and impactful. Your contribution can make a significant difference and help us achieve our goals faster.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Grateful to all for inspiring codebase, your dedication, and creativity made a lasting impact on our success. Thank you!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :question: FAQ <a name="faq"></a>

- **Can I fork and reuse this repository?**

Please feel free to fork and reuse this repository for your projects.

- **Is it okay to improve this repository? Will my changes be accepted?**

We welcome any improvements or new ideas. If your changes are good and align with the project's goals, we would be happy to incorporate them.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
