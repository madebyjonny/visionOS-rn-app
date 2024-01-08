# React Native Vision OS demo app

This is an experiment with the React Native visionOS repo from @CallStack
[link to their repo](https://github.com/callstack/react-native-visionos)

## issue I found 

I found there is an issue when trying to install the boost pod. There is a work around over on the React Native repo, this works for this to, 
but make sure you apply it to the boost.podspec file in the 
node_modules/@callstack/react-native-visionos/third-party-podspecs/boost.podspec file. 

[Link to the issue](https://github.com/facebook/react-native/issues/42180)

## getting started 
Once you have pulled the repo
```
npm install
cd visionos
bundle install
bundle exec pod install

npm run start 

open the YourApp.xcworkspace in xcode 
hit play button
```

