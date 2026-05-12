# Project 2 Web Build

This repository contains the exported Unity WebGL build for **Project 2**, a Unity 6 2D platformer built as the follow-up to Project 1.

The source code, gameplay systems, scripts, assets, and full project documentation are available in the main Unity repository:

[Project 2 Source Repository](https://github.com/nikola-pacaric/project_2)

## About This Repository

This repo is used only for hosting and deployment of the playable WebGL version of the game.

It contains:

- Unity-generated `index.html`
- WebGL build files in `Build/`
- Unity WebGL template files in `TemplateData/`
- Runtime data files in `StreamingAssets/`

The gameplay code is not edited here. Any game changes should be made in the Unity source project, exported again as a WebGL build, and then copied into this repository.

## Related Repositories

- [Project 2](https://github.com/nikola-pacaric/project_2) - main Unity source project
- [Project 2 Web Build](https://github.com/nikola-pacaric/project_2_Web_Build) - exported WebGL build repository

## Build Notes

Project 2 uses Unity Gaming Services for online leaderboard support instead of a separate custom backend. The WebGL build expects the Unity project to be configured with Authentication and Leaderboards in the Unity Cloud project.

The configured leaderboard ID is:

```text
main_scores
```

## Notes

This build is part of my portfolio and represents the WebGL-deployable version of Project 2 at this stage of development.
