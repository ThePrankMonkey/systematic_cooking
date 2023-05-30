# Systematic Cooking - Development

I'm using this to practice a couple new topics:

- Poetry
- FastAPI
- Azure
- React Native

## Features

- [ ] Database
  - [ ] Recipes
    - [ ] Needed ingredients
    - [ ] Needed equipment
    - [ ] Steps
      - [ ] Photos
      - [ ] Instructions
      - [ ] Ingredients Used
      - [ ] Equipment Used
      - [ ] Ingredient Mutation
        - Like turning various ingredients into a sauce
      - [ ] Notes
        - Pull from USER
      - [ ] Duration
      - [ ] Duration Scale Multiplier
        - Some steps double in time if you double ingredients, some don't.
  - [ ] Inventory
    - [ ] Ingredients
    - [ ] Equipment
      - [ ] Affiliate Links
  - [ ] User
  - [ ] User Notes
  - [ ] User Favorites
- [ ] Backend
  - [ ] Return recipe names
  - [ ] Return recipe
  - [ ] Produce gantt from recipe
  - [ ] Add personal notes to recipes
  - [ ] Find recipes that match current inventory
- [ ] Frontend
  - [ ] List recipes
  - [ ] View recipe
    - [ ] Start timers and have alerts
    - [ ] Print recipe
  - [ ] Affiliate links
- [ ] Phone App
  - **TBD**

## Create Development Environment

### Prerequisites

- docker
- docker-compose

### Steps

1. Clone repo
2. Spin up docker-compose

## Create Release Environment

Regardless of the cloud hosting, you should just need to push your containers up to get them to work.

### AWS Infra

- [ ] Domain
- [ ] AmazonCertManager
- [ ] RDS
- [ ] IAM Role
- [ ] Secrets Manager
- [ ] ElasticBeanStalk

### Microsoft Azure

**TBD**
