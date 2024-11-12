# Hello World in GO

![image](https://github.com/user-attachments/assets/d3fc8ec8-90fb-4c4c-aa41-b96bc31e7295)

## About The Project

The "Hello World" project in Go serves as an introductory example that demonstrates how to create, compile, and execute a basic Go application. This type of application is
commonly used as a starting point to learn a new programming language, allowing developers to gain an initial understanding of Go’s syntax and structure.

## Table of Contents

<ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#configuration">Configuration</a></li>
        <li><a href="#running-the-service">Running the service</a></li>
        <li><a href="#running-with-docker">Running with docker</a></li>
      </ul>
    </li>
    <li>
      <a href="#contributing">Contributing</a>
    </li>
 </ol>

## Overview

This project is a simple "Hello World" application developed in the Go programming language. Its goal is to help beginners 
get acquainted with the basic structure of a Go program, from initial setup to running the code.
## Features

<div>
  <ul>
      <li> <b>Simple Setup:</b> Minimal installation and configuration steps, ideal for beginners.</li>
      <li> <b>Basic Structure:</b> Includes a single main function to print "Hello, World!" to the console, illustrating Go's syntax.</li>
      <li> <b>Learning Opportunity:</b> Provides a foundation for exploring more complex applications and features in Go.</li>
  </ul>
</div>


## Built With

[![Docker][docker.com]][docker-url]
[![Go][go.dev]][go-url]

<!-- GETTING STARTED -->
## Getting Started

## Prerequisites

Before you begin, make sure you have the following tools installed on your machine:

- **Golang 1.23.0 or higher** - [Download Golang](https://go.dev/dl/)

If you don't have any of these tools installed, follow the provided links to install them.

## Installation

1.- Clone the repository
   ```sh
   git clone https://github.com/Retrofiyer/Go-HelloWorld.git
   cd Go-HelloWorld
   ```
2.- Build project
 ```sh
   go build main.go
   ```

## Running the service

  ```sh
    go run main.go
   ```

Open any browser and type 

  ```sh
    localhost:8080
   ```

## Running with docker

1.- Making Docker Pull or Build docker image

 ```sh
   docker pull retroandre/go-helloworld:latest
   ```
```sh
   docker build -t <any-name> .
   ```
2.- Last make a docker run

 ```sh
   docker run -p 8080:8080 retroandre/go-helloworld:latest # or any-name
   ```
3.- Open any browser and type

 ```sh
   localhost:8080
   ```

## Contributing
I would like you to contribute to this project. Whether it's fixing a bug, adding a new feature or improving the documentation, your help is always welcome. Please email me at `sebitas5225@gmail.com` with all the details for improvement.

<!-- LINKS & IMAGES -->

[docker.com]: https://img.shields.io/badge/Docker-black?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
[go.dev]: https://img.shields.io/badge/Go-black?style=for-the-badge&logo=go&logoColor=white
[go-url]: https://go.dev/
