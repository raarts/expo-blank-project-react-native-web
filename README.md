# expo-blank-project-react-native-web

This repo can be generated from scratch using the following procedure:

    curl -s https://gist.githubusercontent.com/raarts/8b8637a2a2a04a2ce54214554b1b3468/raw/ab08443947daee4d5202460d8ebd966ab8d25db7/create-expo-web-app > create-expo-web-app
    chmod +x create-expo-web-app
    ./create-expo-web-app myapp
    cd ./myapp

## How to run on Expo

    exp start

and in another terminal:

    exp ios


## How to run on React Native Web:

in another terminal:

    yarn start

and visit http://localhost:8080

To build for deployment:

    yarn build

(and deploy the public directory)

