<p align="center">
  <a href="" rel="noopener">
 <img width=100px height=111px src="https://i.imgur.com/oM2M7PG.jpg" alt="Helti logo"></a>
</p>

---
![slogan](https://github.com/helti-software/helti-docs/blob/main/images/HeltiCropped.png)


---

Helti.io is a health and wellness project that aims to help individuals achieve their weight goals and optimal physical condition. The product offers a variety of tools to assist users in their weight loss journey, including the tools to track their progress and to generate customized, up-to-date meal plans using a trustworthy database, without giving up on their favorite foods and restaurant cuisines.

Sprint: [Asana Sprint](https://app.asana.com/0/1204283110227787/board)

Roadmap: [Asana Roadmap](https://app.asana.com/0/1204283111097387/list)

---

## Table of Contents:
- [The Problem](#the_problem)
- [The Solution](#the_solution)
- [The Competition](#competition)
- [Future ideas](#future_ideas)
- [Success metrics](#success_metrics)
- [Monetization](#monetization)
- [Lean canvases](#lean_canvas)
- [Modules](#modules)
- [Installation](#installation)
- [Contacts](#contacts)

---

## The Problem  <a name = "the_problem"></a>

The problem Helti.io is solving is the difficulty people face in achieving their weight goals due to misinformation, fake gurus, and lack of time and support. With so many ineffective and unsustainable diets out there, people struggle to find a reliable solution to their weight loss/gain needs. Often they get unmotivated by not seeing results by the time they want, because of having unrealistic goals or failing to stick to the plan, causing the so-called yo-yo effect. Additionally, busy lifestyles make it challenging to plan and prepare healthy and tasty meals and keep track of their progress.


## The Solution <a name = "the_solution"></a>

Helti.io's solution to the problem of ineffective diets for weight loss and lack of time is to provide users with personalized meal plans that fit their favorite foods. Additionally, user-friendly tips, progress tracking, and motivation are offered to help users achieve their desired body weight and improve their overall health. In the future, Helti.io plans to integrate with restaurants to provide macronutrients, price, and allergens data for their meals, giving users even more options and flexibility in their meal planning without requiring them to give up on their favorite dishes.


## Competition <a name = "competition"></a>

The main competitors are:

- [MyFitnessPal](https://www.myfitnesspal.com/) - the most popular calorie counter and diet tracker in the world. It offers a large database of foods and recipes, and it is free to use. However, it does not offer personalized meal plans, and it does not provide any tips or motivation to its users.
- [Cronometer](https://cronometer.com/) - a calorie counter and diet tracker that offers a large and reliable database of foods and recipes, and it is free to use. However, it does not offer personalized meal plans, and it does not provide any tips or motivation to its users.
- [YAZIO Fasting & Food Tracker](https://www.yazio.com/en) - a calorie counter and diet tracker that offers a large database of foods and recipes, and it is free to use. However, it does not offer personalized meal plans, and it does not provide any tips or motivation to its users. Having fasting functionality and mood tracking.
- [Calory](https://calory.app/) - a calorie counter and diet tracker that offers a large database of foods and recipes, and it is free to use. However, it does not offer personalized meal plans, and it does not provide any tips or motivation to its users. Very user friendly and easy to use.

## Future ideas <a name = "future_ideas"></a>
- **Restaurant integration:** - Add restaurants to the app (probably via separate app which they will use), so users can order food from them and get the macronutrients, price, and allergens data for their meals. Same can be done for supermarkets.
- **Social media integration:** - Make shareable content such as meal plans, progress, motivational tips and so on, to be used for marketing purposes
- **PDF exporter:** - Export to PDF meal plans, shopping lists, receipts, invoices
- **Coach - client integration:** - Coaches can create meal plans for their clients, and clients can track their progress and send feedback to their coaches. Also coaches will be able to offer discounts for subscription to their clients.
- **Monetization:** - Freemium and Restaurant subscription model


## Success metrics <a name = "success_metrics"></a>

- **Number of users who achieve their weight goals:** This can be measured by tracking the progress of each user over time. The app can ask users to input their initial weight and goal weight when they sign up, and then track their progress through regular weigh-ins or other measurements. The app can then calculate the percentage of users who have successfully reached their goal weight, and use this as a metric of success.
- **User engagement and retention rates:** This can be measured by tracking how often users log into the app, how long they stay on the app, and how often they use the app's features. The app can use this data to calculate a user engagement score, and track how it changes over time. The app can also track how many users return to the app after a certain period of time, such as a week or a month, to calculate the retention rate.
- **Positive user feedback and ratings:** This can be measured by asking users to rate the app and leave reviews. The app can prompt users to rate and review the app after they've been using it for a certain period of time, or after they've achieved a certain milestone, such as reaching their goal weight. The app can then calculate an average rating and track how it changes over time.
- **Increase in healthy eating habits and physical activity levels:** This can be measured by asking users to input information about their diet and exercise habits, and then tracking how they change over time. The app can prompt users to log their meals and exercise, and then use this data to calculate metrics such as calorie intake, macronutrient balance, and average daily activity levels. The app can then track how these metrics change over time, and use them as a measure of success.


## Monetization <a name = "monetization"></a>
- Freemium
- Restaurant subscription model

## Lean Canvas <a name = "lean_canvas"></a>

Lean canvases can be found in following folders:
- [Lean Canvas - B2C](https://github.com/helti-software/helti-docs/blob/73f8a9c58960ee8d829f8a65a870898fd8075b7a/leancanvas/heltib2c.pdf)
- [Lean Canvas - B2B2C](https://github.com/helti-software/helti-docs/blob/73f8a9c58960ee8d829f8a65a870898fd8075b7a/leancanvas/heltib2b2c.pdf)


## Modules  <a name = "modules"></a>

The project is built from the following components:

- Frontend: [helti-web](https://github.com/KristianKonov/helti) by [Kristian Konov](https://github.com/KristianKonov)
- Backend is built by several modules:
  - [helti-core](https://github.com/helti-software/helti-core) - Docker and SQLs, containing the client module used by Feign and other apps for cross service communication
  - [user-service](https://github.com/helti-software/user-service) - Authentication service and exposing data and endpoints for user-related operations
  - [food-service](https://github.com/helti-software/food-service) - Food registry service containing data about all our foods.
  - [recipe-service](https://github.com/helti-software/recipe-service) - Recipe service containing data for the recipes.
  - [training-service](https://github.com/helti-software/training-service) - Service providing the users ability to the track their workouts, which enables us to use the data from it in order to determine their workout duration and number of workouts per week.
  - [generation-service](https://github.com/helti-software/generation-service) - Service used for generating meals. Currently working with input of 3 foods.


## Installation <a name = "installation"></a>

Refer to helti-core's [README.md](https://github.com/helti-software/helti-core)


## Contacts <a name = "contacts"></a>
Email: [helti.soft@gmail.com](helti.soft@gmail.com)

Contributors: 
- Deyvid Dimitrov - [LinkedIn](https://www.linkedin.com/in/deyvid-p-dimitrov/) [Github](https://github.com/DeyvidDimitrov)
- Kristian Konov - [LinkedIn](https://www.linkedin.com/in/kristian-konov/) [Github](https://github.com/KristianKonov)
- Petyo Vakov - [LinkedIn](https://www.linkedin.com/in/petyo-vakov-7b8238107/) [Github](https://github.com/Petyo98)
