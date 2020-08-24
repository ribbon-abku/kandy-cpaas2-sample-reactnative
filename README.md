# kandy-cpaas2-sample-reactnative-android
ReactNative based app of CPaaS modules (SMS, Chat, Presence and Address book) is used to create communication channel between two users.

## Introduction 
This app is used to establish a communication channel between 2 or more users via available Kandy SDK for *SMS*, *Chat* along with other features like *Presence* & *Directory*.

### Available Features
- [x] SMS
- [x] Chat
- [ ] Voice/Video
- [x] Address-book & Directory
- [ ] Presence

## Getting Started

### User manual 

1. Create an account on **AT&T** portal via [Register now for a free account](https://apimarket.att.com/signup).
2. Open application in 2 android devices with *User1* and *User2*.
3. Enter the *server URL*, for e.g.,
	- For AT&T API Marketplace [apimarket.att.com](https://apimarket.att.com), enter `https://oauth-cpaas.att.com`
4. Choose to get accessToken by *Password Grant* flow.
5. Login using two different users' credentials in application.
6. For **Password Grant** flow, enter 
	- *clientId* 
	- *emailId* 
	- *password*   
7. Click ***Login***
8. After successful login you can proceed further accordingly.

## Build and Test
Setup the repository to build the code and run the app. 

### Setup

1. Install **node.js**
2. Install **react-native**, via
```shell
$ npm install -g react-native-cli
```
3. Clone the project, via
```shell
$ git clone https://github.com/hclsampleapps/kandy-cpaas2-sample-reactnative-android.git
```
   Alternatively, you can directly download it as well.

### Build & Run

1. Get inside the cloned/downloaded repository as 
```shell
$ cd kandy-cpaas2-sample-reactnative-android   
```
2. Resolve build dependency via sync gradle in android studio
3. Install all dependencies, via
```shell
$ npm install
```
4. Run and build the app, via
```shell
$ react-native run-android
```
5. Start server, via
```shell
$ react-native start
```
6. Generate final build by android studio

## Contribute

#### Branching strategy

To learn about the branching strategy, contribution & coding conventions followed in the project, please refer [GitFlow based branching strategy for your project repository](https://gist.github.com/ribbon-abku/10d3fc1cff5c35a2df401196678e258a)