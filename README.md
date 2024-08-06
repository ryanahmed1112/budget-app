# RoR-budget-app

## Getting Started

The RoR budget app is a mobile web application where you can manage your budget: users have a list of transactions associated with a category, so that you can see how much money you spent and on what.

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Setup](#setup)
  - [Usage](#usage)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 RoR-budget-app <a name="about-project"></a>

The **RoR-budget-app** allows users to register and log in, so that the data is private to them, introduce new transactions associated with a category and see the money spent on each category. Here is a [video](https://www.loom.com/share/27aaafc6cdb04841b97d97e3728401eb) of me explaining the app in action.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Server</summary>
  <ul>
    <li>Deployed on Render <a href="https://rails-ny91.onrender.com/">Budget app</a></li>
  </ul>
</details>

<details>
<summary>Franwork</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
  </ul>
</details>


<!-- Features -->

### Key Features <a name="key-features"></a>

> Key features of the repository.

- **Was created with RoR** 
- **Has a login and registration authentication system with the help of devise**
- **Has a database that stores the records of it's users**
- **Has Rubocop to enforce best ruby practices**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

Follow these steps in order to run ruby code.

### Prerequisites

First you need to ensure that you have ruby installed in your computer. 

### Install

It varies depending on your operating system so here are some links to help you install it on [Windows](https://gorails.com/setup/windows/10) and on [Ubuntu](https://www.ruby-lang.org/en/documentation/installation/#apt). 

For MacOS run the following commands

```sh
  brew install rbenv ruby-build
  # Add rbenv to bash so that it loads every time you open a terminal
  echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
  source ~/.bash_profile

  # Install Ruby
  rbenv install 3.0.1
  rbenv global 3.0.1
  ruby -v
```

This example shows how to install Ruby 3.0.1 which was the latest version in April 2021, but you can check to see if there is a newer version [here](https://www.ruby-lang.org/en/downloads/releases/). Iy is also assumed that you have [homebrew](https://brew.sh/) already installed on your Mac.

Next you'll want to intall Rails and postgreSQL by running the following commands, but you can also use any SQL application of your choice

```shell
  gem install rails -v 7.0.6

  sudo apt install postgresql libpq-dev
```

And start postgreSQL and the app with 

```shell
  sudo service postgresql start

  rails server
```

### Setup

Once you have ruby installed, run this command to get the project on your local machine.

```sh
  git clone git@github.com:jlvFlores/RoR-budget-app.git
```

### Usage

Once you have the project installed, access the project's root directory usign this command 

```sh
  cd RoR-budget-app
```

And lastly, run this command to see the project in in your browser.

```sh
  rails server
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

> Here is a mention all of the collaborators of this project.

👤 **Author**

- GitHub: [@jlvFlores](https://github.com/jlvFlores)
- Twitter: [@JoseVaz44312762](https://twitter.com/JoseVaz44312762)
- LinkedIn: [Jose (Luis) Vazquez](https://www.linkedin.com/in/jose-luis-vazquez/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

> The following are the future features that will be added to the project.

- [ ] **Add more navigational options to the side menu**
- [ ] **Add functionality to the search icon**
- [ ] **It will probably not take over the world**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project you can give me a hand by recommending me to potential employers! 😉🤝

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank those who have motivated me to keep on fighting despite how tough the journey may become.

**I'd also like to mention [Gregoire Vella](https://www.behance.net/gregoirevella) and his [design](https://www.behance.net/gallery/19759151/Snapscan-iOs-design-and-branding?tracking_source=) from which I took inspiration for this project.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
