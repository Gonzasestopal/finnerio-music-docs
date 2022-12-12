---
description: >-
  This is Finnerio Music App architecture, it will consist of three services and
  one database. I chose a layered architecture for this purpose.
---

# Architecture

## Finnerio Music Scrapper

This service will handle our data layer. This includes data input, data normalization and data persistance into our database.

## Finnerio Music API

This is where the application logic exists, this will handle core business rules and features.

## Finnerio Music Backoffice

Our backoffice will handle the UI and user interaction as the presentation layer.

![](<../.gitbook/assets/Finnerio Scraping Architecture.drawio.png>)
