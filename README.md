# ReactNative-Certificate-Pinning

```bash
# Setting up
git clone https://github.com/0xBloodHound/ReactNative-Certificate-Pinning
cd ReactNative-Certificate-Pinning
npm install
cd ios

# pod 'RNSslPinning', :path => '../node_modules/react-native-ssl-pinning/ios'
pod install
# pod 'RNSslPinning', :path => '../node_modules/react-native-ssl-pinning'

# Start debugging Server
cd /path/to/ReactNative-Certificate-Pinning
npx react-native start

# Run Android Application
cd /path/to/ReactNative-Certificate-Pinning
npx react-native run-android

# Run iOS Application, Open the project by xcode
./ios/ReactNativeCerificatePinning.xcworkspace
```