# Multi-Tier Architecture

## What Is a Two-Tier Architecture?

A two-tier architecture is an application design that separates an application into two main parts: the Web/Application Tier and the Database Tier. In this mission, Nextcloud serves as the web application, while MariaDB stores the application's database information.

## The Web/Application Tier

The Web/Application Tier handles user interactions and provides the web interface. In this deployment, Nextcloud allows users to access the private cloud storage system through a web browser and processes requests from users.

## The Database Tier

The Database Tier stores and manages persistent information needed by the application. In this deployment, MariaDB stores Nextcloud's database records, such as user account information and file metadata.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container has its own responsibility, and the application can communicate with the database through Docker's internal network. This setup also makes it easier to update or troubleshoot one component without combining everything in a single container.
