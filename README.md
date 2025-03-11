# Little Shop - Coupon Codes | Frontend Repo

Jaren Garman

[GitHub](https://github.com/JarenGarman)

[LinkedIn](https://www.linkedin.com/in/jarengarman/)

## Abstract

This app is a demonstration of my abilities to expand on an existing API to add new features, all while following common web conventions like MVC, REST, and CRUD, as well as maintaining the existing styling of the codebase.

## Installation Instructions

To run this app locally, you will need to clone down two separate repos. I recommend creating a new directory to store them in:

```shell
mkdir coupon_codes
cd coupon_codes
```

### Backend

#### Clone the [backend repo](https://github.com/JarenGarman/coupon_codes_be)

```shell
git clone https://github.com/JarenGarman/coupon_codes_be.git
```

#### Run the setup commands

```shell
bundle install
rails db:{drop,create}
rails runner ActiveRecord::Tasks::DatabaseTasks.load_seed
rails db:migrate
```

#### Start the backend server

```shell
rails server
```

### Frontend

#### Clone the [frontend repo](https://github.com/JarenGarman/coupon_codes_fe)

```shell
git clone https://github.com/JarenGarman/coupon_codes_fe.git
```

#### Run the setup command

```shell
npm install
```

#### Start the frontend server

```shell
npm run dev
```

### Connect

You can now connect by opening the following URL in your browser: [http://localhost:5173/](http://localhost:5173/
)

## Preview of App

(Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off. gifs preferred!)

## Context

(Give some context for the project here. How long did you have to work on it? What specific work/improvements did you contribute to this FE application?)

## Learning Goals

(What were the learning goals of this project? What tech did you work with?)

## Wins + Challenges

(What are 2-3 wins you have from this project? What were some challenges you faced - and how did you get over them?)
