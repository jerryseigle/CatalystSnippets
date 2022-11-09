## macOS Catalyst Snippets
#### Select a branch to see examples (PR are accepted)

### Todo -> Add examples
- File system (document) picker | native and React Native
- Make system menu | native and React Native
- Muliple Windows (launch 2 or 3 windows) | native and React Native
- UIView created by code and in storyboard (in Swifth) | React Native
- Native Popup modal | native and React Native
- Popup Button with menu | native and React Native

### For React Native
If you create React Native project using a pure swift template run the following script in your project root directory

````react-native bundle --entry-file index.js --platform ios --dev false --bundle-output ios/main.jsbundle --assets-dest ios````

- You will need to copy the main.jsbundle file to your project {TARGET} build phases -> Copy Bundle Resources
- Add the newly created ```assets directory ``` located in ProjectName/ios into xcode file panel, under the project name

### Bonus Todo
- React Native create bundle for production release | how to add the bundle
- Codepush example with swift project
- Video example
