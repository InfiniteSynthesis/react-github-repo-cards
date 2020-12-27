# react-github-repo-cards ![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg) ![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-pink.svg)

![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)
![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)

A beautiful card that displays Github repository infos.


<p align="center"><img src="docs/demo.png" alt="demo"></p>

## Demo Show

- **Online** [Demo Webside](https://infinitesynthesis.github.io/react-github-repo-cards/)

- **Local**

    ```shell
    git clone https://github.com/InfiniteSynthesis/react-github-repo-cards.git
    cd react-github-repo-cards
    npm i
    npm start
    ```
    open `localhost:3001`



## How to Use 🍕

1. install
    ```shell
    npm i react-github-repo-cards
    ```

1. import
    ```javascript
    import import { RepoCard } from 'react-github-repo-cards'
    ```

2. use
    ```javascript
    <RepoCard username="InfiniteSynthesis" reponame="react-github-repo-cards" />
    ```

## Settings 🔨

| Parameter   | Type           | Default  | Description|
| :----------: |:---:| :---:| :------------- |
| `username` | String | "" | User name of this repository. |
| `reponame` | String | "" | Name of the repository. |
| `center` | Boolean | false | If card is aligned center. |
| `squareAvatar` | Boolean | false | If avatar is displayed with square outline. |
| `descriptionLine` | Number | 2 | The maximum line of repo description. |
