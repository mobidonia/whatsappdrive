---
description: How to get started with WhatsApp Taxi?
---

# Introduction

Welcome to WhatsApp Taxi's Documentation.

![](<.gitbook/assets/CoverHiRes (1).jpg>)

### Folder structure

![](<.gitbook/assets/CleanShot 2022-05-04 at 11.23.05 2.png>)

1. Driver Mobile app - The app for the driver
2. Client Mobile app - The app for the client
3. This is the zip that contains the code for the web project of WhatsApp Taxi. (Start with it)

## Tech stack

#### Web Project - [Laravel](https://laravel.com/) - v8

Inside it, we use a standard blade view. The landing page is using[ Tailwind CSS](https://tailwindcss.com/). However, the backend uses [Bootstrap](https://getbootstrap.com/).&#x20;

### Mobile app,  is [React Native app](https://reactnative.dev/), using [Expo](https://expo.dev/)

The driver app, uses a geolocation service, to determine the driver's location

The client app is a simple wrapper on top of the web project.

To learn about all the APIs needed, please check the API setup section

### Web project of WhatsApp Taxi

#### To install the project directly on shared hosting

{% content-ref url="docs/installation.md" %}
[installation.md](docs/installation.md)
{% endcontent-ref %}

#### To install the project locally

{% content-ref url="docs/run-locally.md" %}
[run-locally.md](docs/run-locally.md)
{% endcontent-ref %}



### Driver mobile app

{% embed url="https://mobidonia.gitbook.io/mobile-apps" %}

### Client Taxi mobile app

{% embed url="https://mobidonia.gitbook.io/mobile-apps" %}
