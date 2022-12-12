---
description: >-
  This is Finnerio Music App architecture, it will consist of three services and
  a  database layer. I chose a layered architecture for this purpose.
---

# Architecture

## Finnerio Music Scrapper

This service will handle our data input layer. This includes data input, data processing and data normalization.

## Finnerio Music DB layer

This handles data persistance of our data layer.

## Finnerio Music API

This is where the application logic exists, this will handle core business rules and features.

## Finnerio Music Backoffice

Our backoffice will handle the UI and user interaction as the presentation layer.



![](<../.gitbook/assets/Finnerio Scraping Architecture.drawio.png>)
