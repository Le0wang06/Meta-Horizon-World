# Meta Horizon World

A **Meta Horizon Worlds** project built in **TypeScript** that explores custom UI systems, interactive stations, and reusable gameplay scripts.

## Overview

This repository contains a set of scripts for building and testing interactive experiences inside **Meta Horizon Worlds**.  
The project appears to be organized around multiple **station-based examples**, each demonstrating a different UI or interaction pattern, such as dialogs, overlays, scrolling interfaces, asset loading, and item interactions.

This project is useful for:
- learning Horizon Worlds scripting with TypeScript
- prototyping custom UI interactions in VR
- organizing reusable scripts across multiple interaction stations
- experimenting with player-facing world mechanics

## Features

- Multiple station-based interaction demos
- Custom UI experiments and reusable UI library code
- Dialog and overlay systems
- Scrolling and column/combo view examples
- Asset/image loading examples
- Simple interaction scripts such as candy pickup/display logic
- Player management script for handling user-related behavior

## Project Structure

```text
.vscode/
node_modules/
types/

PlayerManager.ts
Station00-Welcome.ts
Station01 -CustomUIFonts.ts
Station02-ImageFromAsset.ts
Station03-ScrollingUI.ts
Station04-GenericYesNoDialog.ts
Station05-OrbOfUINess.ts
Station06a-ColumnView.ts
Station06b-ComboView.ts
Station07a-SeeCandy.ts
Station07b-GetCandy.ts
Station08-DisplayCustomUI.ts
Station08-LoadCustomUIData.ts
Station09a-ScrollAsset.ts
Station09b-StartStopAnimation.ts
Station10-BuildInfo.ts
Station10-NonInteractiveOverlay.ts
Station10-StopTimer.ts
StationAll-CustomUI-Library.ts
package.json
tsconfig.json
```

## Tech Stack

- **Meta Horizon Worlds**
- **TypeScript**
- **Node.js / npm**
- **VS Code**

## Example Components

Some of the included scripts suggest the following functionality:

- **Welcome station** for onboarding or intro interactions
- **Custom font UI** experiments
- **Image-from-asset rendering**
- **Scrolling UI panels**
- **Generic yes/no dialog system**
- **Column and combo layout views**
- **Custom UI display and data loading**
- **Animation control**
- **Build info / timer / overlay utilities**
- **Shared custom UI library** for reuse across stations

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Le0wang06/Meta-Horizon-World.git
cd Meta-Horizon-World
```

### 2. Install dependencies

```bash
npm install
```

### 3. Open the project

Open the folder in **VS Code** and connect it to your **Meta Horizon Worlds** workflow/editor setup.

### 4. Run or test scripts in Horizon Worlds

Import or attach the scripts to the relevant entities/stations in your world and test interactions directly inside the Horizon Worlds environment.

## Purpose

This project is mainly a **learning and prototyping environment** for building interactive UI-driven systems in Meta Horizon Worlds. It demonstrates how different scripts can be separated into modular stations while still sharing common functionality through a central library.

## Future Improvements

- Add screenshots or a GIF demo of each station
- Add setup steps specific to Horizon Worlds editor workflow
- Document how each station works in detail
- Remove committed dependency folders like `node_modules` if not needed in source control
- Add comments and usage instructions for each script
- Include a demo video or world preview link

## Author

**Leo Wang**  
Systems Design Engineering @ University of Waterloo
