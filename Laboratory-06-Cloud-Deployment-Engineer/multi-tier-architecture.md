# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture separates an application into two functional levels that communicate with each other. The first level handles the application and user interaction, while the second level is responsible for managing the application's stored information.

## The Web/Application Tier

The Web/Application Tier provides the application that users access through a web browser. Its responsibilities include receiving HTTP requests and presenting the application's interface. In this activity, Nextcloud represents this tier.

## The Database Tier

The Database Tier provides the storage system used by the application. It manages persistent information that needs to be saved and retrieved when required. MariaDB is used as the database service for the Nextcloud application.

## Why Separate Them?

Using two separate containers keeps the web application and database as distinct services with their own responsibilities. This makes it easier to maintain or troubleshoot one component without combining its operations with the other. It also creates a more organized application structure.
