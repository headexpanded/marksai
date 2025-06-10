## A simple AI chatbot ##

### Requirements

Docker

Anthropic API key

### Installation

Clone the repo

cd marksai

git submodule update --init --recursive

docker compose up --build -d

### After install

Pocketbase db is served at localhost:8090

Create an admin user at localhost:8090/_

Create a new collection:

name=conversations

field: user relation users

field userInput text nonempty

field aiResponst text nonempty


Front end is served at localhost: 5173 : register as a user into your local Pocketbase db
