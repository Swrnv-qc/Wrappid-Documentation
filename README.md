# Wrapper Framework for Rapid Development

<img src="https://github.com/Swrnv-qc/Documentation/blob/main/logo-1200x400.png" width="50%" height="auto" alt="Wrappid"/>

## Introduction

The Wrappid Framework is a wrapper framework designed to facilitate rapid development of applications. It allows developers to write code once and then use the Wrappid Toolkit to build both web and mobile applications simultaneously .

The framework is based on technologies such as React, React Native, Node, Express, etc. It includes a repository of components known as CoreComponents for application developers to use. Developers also have the flexibility to write their own components .

By default, the styling libraries used are [mui for web](https://mui.com/material-ui/) and [react native paper](https://reactnativepaper.com/) for mobile. The framework also comes with a set of pre-coded business handling modules like app builder, user/role/permission management, authentication, authorization, error reporting, notifications (push/mail/sms/whatsapp), etc .

## Getting Started

To get started with the Wrappid Framework, you need to go through several steps:

### 1. Get Early Access to Wrappid:

You need to fill out the [Wrappid Early Access Request form](https://docs.google.com/forms/d/e/1FAIpQLSe4l2KlbHjubjbpWrIhArBZJc12Lv2TnOevh2Cj9WUfYEuRSw/viewform) to get a valid`<WRAPPID_TOKEN>`. This token is used to read and download the Wrappid packages .

### 3. Check Pre-requisites: Ensure that you meet the requirements for setting up the Wrappid Framework

Required for web app development:

- [Node.js - version 16.20.X](https://nodejs.org/en/blog/release/v16.20.0)
- npm - version 8.X.X

>**Note:** If you have multiple node versions, to set up node 16.20.x & npm 8.x.x, follow the documentation [here](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).
  
**Check your version of Node.js and npm:**
To see if you already have Node.js and npm installed and check the installed version, run the following commands:

```
node -v
```

Expected output:  
v16.20.x

```
npm -v
```

Expected output:  
8.x.x
>**Note:** _Above mentioned version is based on the time of documentation, 16.20.(x), 8.(x).(x), x may differ._.

###### Required for mobile app development

- [JDK - 11](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)
- [Android Studio](https://developer.android.com/studio)Recommended Code editor:
- [VS Code](https://code.visualstudio.com/)/[VS Codium](https://vscodium.com/)

3. **Install `Wrappid Toolkit`**
To use `Wrappid Toolkit`, you need to setup scoped wrappid package registry and install `@wrappid/toolkit` globally in your system.

 >**Note:**
 >_It is expected that you successfully went through [1. get early access to wrappid](https://github.com/Swrnv-qc/Documentation#1-get-early-access-to-wrappid) section. If you don't, you won't be able to setup wrappid framework._
