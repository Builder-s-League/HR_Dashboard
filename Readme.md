# UBC Dashboard Setup Guide

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed
- [Node.js](https://nodejs.org/en/download/) installed
- [npm](https://www.npmjs.com/get-npm) installed
- [npx](https://www.npmjs.com/package/npx) installed

## Clone the Repository

First, clone the repository using the following command:

```bash
git clone https://github.com/Builder-s-League/UBC_Dashboard.git
cd UBC_Dashboard
```

## Run Appsmith Locally

To run Appsmith locally, use Docker:

```bash
docker compose up -d
```

This will start the required services in the background.

## Install Dependencies

Install the necessary dependencies for the project using npm:

```bash
npm install
```

## Start Supabase

To start Supabase locally, run the following command:

```bash
npx supabase start
```

## Access the Application

Once all the services are running, open your browser and go to:

```
http://localhost:8080
```

## Create an Account

Once you are on the local instance, create an account to access the dashboard.

## Import JSON File

Navigate to the `src/` directory of the repository and import the JSON file that is present there into the app.

## Modify the JSON

Once the import is done, replace the JSON file in the same `src/` directory with the updated one.

## Create a Pull Request (PR)

After making your changes, Export the project to the `src/` directory with same filename.
Then create a pull request.

```bash
git add src/
git commit -m "Updated JSON file"
git push origin <your-branch-name>
```

Then, go to the repository on GitHub and create a pull request for review.

---

This completes the setup and contribution process for the UBC Dashboard.
