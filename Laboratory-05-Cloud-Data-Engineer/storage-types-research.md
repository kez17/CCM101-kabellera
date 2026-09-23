# Storage Types Research

## Overview

Cloud storage allows users to store, manage, and access data through the internet. It provides different storage types designed for different needs, including **Block Storage, File Storage, and Object Storage**. Each type has its own way of organizing and accessing data, making it suitable for different applications and workloads.

## Comparison of Cloud Storage

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks and works like a traditional hard drive. | Virtual machines, databases, and operating systems | AWS EBS |
| File Storage | Stores data as files and folders that can be shared over a network. | Shared files and applications that need a common file system | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Images, videos, backups, and other unstructured data | AWS S3 |

## Why Object Storage?

Object Storage is a good choice for storing millions of user-uploaded images because it is designed for large amounts of unstructured data. It can store images as separate objects and can be accessed easily by cloud applications.
