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

Pocketbase db is served at localhost:8090 : create an admin user!

Front end is served at localhost: 5173 : register as a user into your local Pocketbase db
