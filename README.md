## About Rythm

**Rythm** is a minimalistic web-based music application built on the Internet Computer using Motoko for backend logic and plain HTML/CSS for the frontend. The app allows users to interact with basic music features—like play, pause, and manage tracks—showcasing how decentralized applications can be built on the ICP ecosystem.

## Deploying from ICP Ninja

When viewing this project in ICP Ninja, you can deploy it directly to the mainnet for free by clicking "Deploy" in the upper right corner. Open this project in ICP Ninja:

[![](https://icp.ninja/assets/open.svg)](https://icp.ninja/i?url=https://github.com/your-github/rythm)

## Project structure

The `/backend` folder contains the Motoko canister, `rythm.mo`, which manages the core logic such as track storage, playback control, and user interactions.

The `/frontend` folder contains web assets for the application's user interface. The user interface is built using plain HTML and CSS. You can extend it further using JavaScript or integrate your favorite frontend framework.

Edit the `mops.toml` file to add [Motoko dependencies](https://mops.one/) to the project.

## Build and deploy from the command-line

To migrate your ICP Ninja project off of the web browser and develop it locally, follow these steps. These steps are necessary if you want to deploy this project for long-term, production use on the mainnet.
