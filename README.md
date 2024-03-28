# Multi-Stage Docker Build with Distroless Images

This repository contains an example of a multi-stage Docker build using distroless images to reduce image size. The main purpose of this example is to demonstrate the advantages of using distroless images, particularly in scenarios where minimal dependencies are required.

## Overview

Docker images built with traditional Linux distributions often include unnecessary packages and dependencies, leading to larger image sizes. Distroless images, on the other hand, provide a minimal base without extra layers, resulting in smaller and more secure images.

## Features

- Uses GoLang to create a simple application for demonstration purposes.
- Implements a multi-stage Docker build to separate the build environment from the final runtime environment.
- Utilizes a distroless base image to minimize the image size without sacrificing security or functionality.

## Usage

To use this example, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/docker-multistage-distrolss-example.git
   ```
   
2. Navigate to the cloned directory:

   ```bash
   cd docker-multistage-distrolss-example
  
3. Build the Docker image:

   ```bash
   docker build -t your_image_name .

4. Run the Docker container:

   ```bash
   docker run -it your_image_name
   ```

  ## Licence

  This project is licensed under the MIT License - see the LICENSE file for details.

1. Clone this repository to your local machine:
   
```bash
You can copy and paste this entire block into your README.md file. Adjust the URLs, paths, and any other details to match your project's specifics.
```
