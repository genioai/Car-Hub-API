<a name="readme-top"></a>

<div align="center">

<h3><b>Carhub API</b></h3>

</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
  - [Kanban Board](#Kanban-Board)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Carhub App <a name="about-project"></a>

**Carhub App:** is a full stack web application with a react client and rails api that allows users to book reservations for renting or buying a car.

=> [Link to the front-end main react app](https://github.com/deniodev/car_reservation_front_end)

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
 <summary>Client</summary>
  <ul>
    <li><a href="https://react.dev/">ReactJS</a></li>
  </ul>
  <ul>
    <li><a href="https://tailwindcss.com/">Tailwind CSS</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **The user logs in to the website, only by typing the username**
- **The user can see links to: Cars, Reserve, My Reservations, Add Car, and Delete Car**
- **See a list of cars**
- **User can select the item and see details of the item**
- **user clicks the "Add item" link in the navigation panel they can see a form for adding a new item.**
- **When the user clicks the "Delete item" link in the navigation panel they can see a list of all items with title and "Delete" button.**
- **When the user clicks the "My reservations" link in the navigation panel they can see a list of their reservations (with information about item name, date and city).**
- **"Add item" and "Delete item" links are accessible only by users who are admins.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 🚀 Live Demo <a name="live-demo"></a>

- <a href="https://dev--cozy-concha-614dd5.netlify.app">Carhub App Live</a>
- [Backend API](https://carhub-nxj0.onrender.com/api/v1/cars)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🚀 Kanban Board <a name="Kanban-Board"></a>
  ## A Team of 5 Members worked on this project - [See list of authors](#authors)
   - <a href="https://github.com/users/unorjikingsley/projects/6/views/1">Kanban Board Link</a>
   - [Kanban Screenshot 1](https://user-images.githubusercontent.com/99336776/272520515-00422de1-c8f6-4970-839b-bd1ae78846b3.png)
   - [Kanban Screenshot 2](https://user-images.githubusercontent.com/99336776/272520581-ffb1d505-33b2-4727-8a8e-5b9a2961b9e3.png)
   - [Kanban Screenshot 3](https://user-images.githubusercontent.com/99336776/272520633-b4b7e1dc-cfe2-4e1c-9019-d4cac923e4b2.png)

  <p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- `React`
- `Redux`
- `Ruby`
- `Rails`
- `Code editor (VSCode, RubyMine)`

### Setup

Clone this repository to your desired folder:

```sh
  git clone https://github.com/unorjikingsley/Reservation-API.git
```

### Install

Install this project run these commands in order:

```sh
  cd my-project
  bundle install
  rails db:create
  rails db:migrate
  rails db:seed
```

### Usage

To run the project, execute the following command:

```sh
  rails server
```

### Run tests

To run tests, run the following command:

```sh
  rspec ./spec/models
```
To run tests for controllers(request) and for API Documentation, run the following command:

Install the gem -
 Add the `gem 'rswag'` and `gem 'rswag-ui'` in your gem file and run `bundle install`

Run

```sh
  rails generate rswag:install
```

```sh
  rake rswag:specs:swaggerize
```

### Deployment

You can deploy this project using your own deployment solution

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Unorji Kingsley**

- GitHub: [@unorjikingsley](https://github.com/unorjikingsley)
- LinkedIn: [unorjikingsley](linkedin.com/in/unorjikingsley)

👤 **Biftu Girma**

- GitHub: [@Bifabig](https://github.com/Bifabig)
- Twitter: [@biftu94](https://twitter.com/biftu94)
- LinkedIn: [Biftu Girma](https://www.linkedin.com/in/biftu-girma/)

👤 **Musangamfura Emmmanuel**

- [GitHub](https://github.com/musangamfure)
- [Twitter](https://twitter.com/musangamfure)
- [LinkedIn](https://www.linkedin.com/in/musangamfurae)

👤 **Salma Ibrahim**

- GitHub: [@Saluumaa](https://github.com/saluumaa)
- Twitter: [@SalmaHIbrahim20](https://twitter.com/SalmaHIbrahim20)
- LinkedIn: [Salma ibrahim](https://www.linkedin.com/in/salma-ibrahim-78bb5a14a/)

👤 **Denio Nhanale**

- GitHub: [@Denio Nhanale](https://github.com/deniodev)
- Twitter: [@Denio Nhanale](https://twitter.com/DNhanale)
- LinkedIn: [Denio Nhanale](https://www.linkedin.com/in/denionhanale)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- **Add an option to buy new cars**
- **Implement Edit button in the Delete car section**
- **Redirect the email confirmation link to the login page**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Bifabig/blog-app-rails/issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project consider adding a ⭐️

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

Original design idea by [Murat Korkmaz on Behance](https://www.behance.net/gallery/26425031/Vespa-Responsive-Redesign).

We would like to thank [Microverse](https://bit.ly/MicroverseTN).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
