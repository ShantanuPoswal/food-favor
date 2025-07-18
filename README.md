<p align="center">
    Transforming leftovers into culinary wonders! <br/>
    Unleash your kitchen creativity, share delightful recipes, and champion a zero-waste lifestyle. <br>
    Join us in savoring sustainability, one delicious dish at a time! 🌍🍽️
</p>

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Recipe Revival

  Rediscover magic in leftovers with creative

  <details>
    <summary> Sample UI of Recipe Generator</summary>
    <img src="https://github.com/SusheelThapa/Quine-ZeroSpoil/assets/83631265/6859f5d2-9633-47bd-a90e-f72ac372e058" width=750/>
  </details>

- Community Connection:

  Join a vibrant community of food enthusiasts, sharing recipes, stories, and culinary adventures.

  <details>
    <summary> Sample UI of Community Connection</summary>
    <img src="https://github.com/SusheelThapa/Quine-ZeroSpoil/assets/83631265/3b078fb5-c04f-40d0-ade2-337d2efd1a1c" width=750/>
  </details>

- Donation Hub:

  Easily connect with local charities and food banks to share excess food and reduce waste.

  <details>
    <summary> Sample UI of Donation Hub</summary>
    <img src="https://github.com/SusheelThapa/Quine-ZeroSpoil/assets/83631265/20063ba6-0490-4514-b1bb-42e9bf4938ee" width=750/>
  </details>

- Expiration Alerts:

  Receive timely notifications about expiring ingredients to optimize your pantry.

  <details>
    <summary> Sample UI of Expiry Track </summary>
    <img src="https://github.com/SusheelThapa/Quine-ZeroSpoil/assets/83631265/2ed8605d-b10d-47a9-be42-729348b8f03d" width=750/>
  </details>

## Installation

### Prerequisites

Before running, FoodFavor, you will need an OpenAI API key if the project utilizes OpenAI's services. You can obtain an API key by registering on the OpenAI platform.

### Setup

#### FrontEnd

1. Clone the repository:

   ```bash
   git clone https://github.com/ShantanuPoswal/FoodFavor.git
   cd FoodFavor
   ```

2. Change directory to `frontend`

   ```bash
   cd frontend/
   ```

3. Installation of node packages

   ```bash
    yarn
   ```

4. Running the project:

   ```bash
   yarn run dev
   ```

#### Backend

1. Change directory to `backend`

   ```bash
   cd backend/
   ```

2. Installation of node packages

   ```bash
    pip install -r requirements.txt
   ```

3. Setting up .env in root backend folder for saving openai api key

  - Create a .env file 
    
    ```bash 
      # inside .env file
      OPENAI_API_KEY=******************************* # Your key 
    ```

4. Running the project:

   ```bash
   python manage.py runserver
   ```


## Dependencies

### Frontend
- Vite
- React
- React Router
- React Icons
- shadcn/ui
- Tailwind CSS


### Backend
- Openai 
- Django Rest Framework
- django-jazzmin 
- django-spectacular
