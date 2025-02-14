# This is the Company's Goals plugin for Zuri Chat

## Getting Started

Make sure you have nodejs installed by running the following command:

```bash
node -v
```

If the output is not the version of your nodejs installation, install nodejs from [here](https://nodejs.org/en/download/)

## Getting Started With the Backend (Node)

After installing nodejs install [yarn](https://www.npmjs.com/package/yarn) if you don't have it then install the project's dependencies:

```bash
yarn install
```

Run the development server using either of the following commands:

```bash
npm run run-dev
# or
yarn run run-dev
```

Project will be ruuning @ [http://127.0.0.1:8080](http://127.0.0.1:8080)

## Getting Started With the Frontend/Client (React)

cd into the client folder and install the client's dependencies

```bash
yarn install
```

Run the development server using either of the following commands:

```bash
npm start
# or
yarn start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Concurrently Run Both (React & Node)

make sure you are in the root folder

Run the development server using either of the following commands:

```bash
npm run dev
# or
yarn run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### CONTRIBUTION GUIDE

1. Fork the central repository, i.e the team's general repository.

2. After forking it will appear in your personal profile, copy the url and open your favorite code editor, add the forked repo to your local machine using the git command - git clone (url of repo you copied) on your terminal.

   - git clone clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository

   - the upstream is named origin by default

3. Create a new branch for the task you are assigned to with a descriptive branch name, using the git command: git checkout -b (branch name)

4. After implementation, use the git command -: git add . or git add -A or git add (the file name) to effect changes you've made to the branch

5. Commit your changes with a descriptive commit message, the commit message should give an idea of the feature you worked on, use the git command: git commit -m "commit message"

6. Push changes to your forked repo with the new branch you created using the git command: git push origin your-branch-name

7. Create a pull request to the develop branch of the central repository from your forked repo on github. The button is on the GUI

- Pro tip: It is possible that commits may have been merged to central repository, to avoid conflicts, fetch and merge from the central repo on the GUI, then you can update your local machine by using the command: git pull
