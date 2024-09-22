---
layout: project-right
title: "Academic Learning Resource Optimizer"
description: "A web application designed to generate personalized and contextually relevant study schedules based on academic documents."
date: 2024-09-21T10:20:00Z
weight: 1
thumbnail: "/assets/images/gen/projects/project-1-1-thumbnail.webp"
image: "/assets/images/gen/projects/project-1-2.webp"
categories: ["Development"]
role: "Lead Developer"
gallery:
  - image: "/assets/images/gen/projects/project-1-1.webp"
    caption: "<strong>Above:</strong> Personalized study schedule generation interface."
  - image: "/assets/images/gen/projects/project-1-2.webp"
    caption: "<strong>Above:</strong> Example of a generated study plan."
gallery_limit: 2
---

The **Academic Learning Resource Optimizer** is a web application designed to generate personalized and contextually relevant study schedules. By leveraging document embeddings and deadlines extracted from uploaded academic materials, the application produces a structured study plan that accurately references the content of the materials. This system is built on a serverless architecture using AWS services, ensuring scalability, reliability, and efficiency.

### Features

- **Document Upload & Embedding Generation**: Users can upload academic documents. The system generates embeddings representing the content of these materials.
- **Personalized Study Schedule**: The application processes the embeddings and deadlines to create a detailed, day-by-day study schedule, ensuring that each task is aligned with the relevant materials.
- **Asynchronous Processing**: Handles large datasets by separating the schedule generation into background processes, allowing for efficient handling and improved user experience.
- **Responsive User Interface**: A clean and intuitive React-based frontend that allows users to easily interact with the system, upload documents, and view generated schedules in a tabular format.
- **Serverless Architecture**: Built using AWS Lambda, DynamoDB, and API Gateway to ensure scalability, reliability, and security.

### Technologies

- **Frontend**: React, Axios, Material-UI
- **Backend**: Node.js, AWS Lambda, DynamoDB, API Gateway, OpenAI GPT-4
- **APIs**: OpenAI API for generating embeddings and study schedules
- **Database**: DynamoDB for storing document embeddings and generated schedules

### Getting Started

#### Prerequisites

- Node.js
- AWS account with access to Lambda, DynamoDB, and API Gateway
- OpenAI API key

#### Installation

**Clone the Repository:**

```bash
git clone https://github.com/your-username/context-aware-study-schedule-generator.git
cd context-aware-study-schedule-generator
