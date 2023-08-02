# Alvin's React Native Sandbox

I'm using this as a way to learn React Native and to showcase my work.

# Quickstart

## Android

```bash
cd ~/personal/react-native-sandbox;
nvm install $(cat .nvmrc)
nvm use
yarn android
```

## OSX

```bash
cd ~/personal/react-native-sandbox;
nvm install $(cat .nvmrc)
nvm use
yarn ios
```

# First Start

1. Update your Xcode
2. Install [Homebrew](https://brew.sh/)
3. Set your android to developer mode [link](https://developer.android.com/studio/debug/dev-options)
4. Enable USB debugging on your android phone (Settings -> Developer Options -> then toggling USB debugging to ON)
5. Run these commands

```bash
cd ~/personal
git clone git@github.com:alvinycheung/react-native-sandbox.git
cd ~/personal/react-native-sandbox
brew install nvm
nvm install $(cat .nvmrc)
nvm use
npm install -g react-native-cli
npm install -g react-native
npm install -g yarn
```

# Errors

If the server is already running but you don't see it, kill it

```
ps -ef | grep react
kill -9 <pid>
```

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.
