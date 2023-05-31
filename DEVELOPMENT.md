# Systematic Cooking - Development

I'm using this to practice a couple new topics:

- Poetry
- FastAPI
- Azure
- React Native

## Features

- [ ] Database
  - [ ] Multicomponent Meals
    - These are basically combined recipes. Like Chicken Caesar Salad = Grilled Chicken + Caesar Salad.
  - [ ] Recipes
    - [ ] Needed ingredients
      - Scalable
      - Should this just parse from the steps? No.
    - [ ] Needed equipment
      - Should this just parse from the steps? Maybe.
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
      - [ ] Reason
        - Give cool science reason for why a step is performed.
    - [ ] Notes
      - Pull from USER
    - [ ] Source
  - [ ] Inventory
    - These are per household? Per user?
    - [ ] Ingredients
      - [ ] Name
      - [ ] Location
      - [ ] Expiratation date
      - [ ] Affiliate Links
    - [ ] Equipment
      - [ ] Name
      - [ ] Location
      - [ ] Type
      - [ ] Capacity
      - [ ] Affiliate Links
      - [ ] Brand/Model?
        - Could be useful for tracking recalls...
  - [ ] User
  - [ ] User Notes
    - [ ] Recipe
    - [ ] Step
      - Step 0 is for the whole Recipe
    - [ ] Content
  - [ ] User Favorites
    - [ ] User ID
    - [ ] Recipe ID
- [ ] Backend
  - [ ] Return recipe names
  - [ ] Return recipe
  - [ ] Produce gantt from recipe
  - [ ] Add personal notes to recipes
  - [ ] Find recipes that match current inventory
  - [ ] Using a recipe subtracts from inventory
  - [ ] Override current inventory
- [ ] Frontend
  - [ ] List recipes
  - [ ] View recipe
    - [ ] Select Scale
    - [ ] Start timers and have alerts
    - [ ] Print recipe
  - [ ] Affiliate links
  - [ ] Inventory maintenance
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
