# shopping-cart


This repo contains a basic command-line application which prompts the user to specify the desired products purchased at Steven Fresh Goods and generates a receipt with the selected items
## Installation
Clone or download this repo onto your local computer. Once the repo is cloned/downloaded, navigate there from the command line. (see below for reference)
```
cd shopping-cart
```
## Setting up
You have the option of Setting up a virtual environment. 
```
conda create -n shopping-env python=3.8 
conda activate shopping-env
```
Be sure to install the required packages:
```
pip install -r requirements.txt
```
### Configuring Environment Variables
Add a new ".env" file to the root directory of this repo, and assign the desired tax rate as a decimal. See below for an example.
```
TAX_RATE=".085"
```
## Running the Application
To run the application:
```
python shopping_cart.py

# Note: When prompted, choose a product identifier between 1 and 20 and type "done" in lower case when you've completed shopping and inserted all product identifiers.


