<!-- @format -->

# Reading: React Native

## Reading

[getting started with react native](https://reactnative.dev/docs/getting-started)

### Name three Core Components of React Native and describe what they do.

-View: A container that supports layout with flexbox, style, some touch handling, and accessibility controls. It is similar to a div in web development.
-Text: A component for displaying text. It supports style and touch handling.
-Image: A component for displaying images. It supports a flexible image source, styles, and touch handling.

### What problem does React Native solve (why call it native)?

React Native solves the problem of building mobile apps that feel truly "native" by using the same fundamental building blocks as regular iOS and Android apps. Instead of using web technologies like HTML, CSS, and JavaScript to build mobile apps, React Native allows developers to use the same React JavaScript library for building mobile apps that look and feel like they were built with traditional iOS and Android technologies.

### What are the building blocks of a React Native app? How does that compare to a React app?

The building blocks of a React Native app are the same as a React app: components and a virtual DOM. However, in React Native, these components map to native components (e.g. View maps to UIView on iOS and android.view on Android) and the virtual DOM is used to update the native views.
[expo](https://expo.dev/)

### What solution does expo provide?

Expo is a tool that allows developers to build React Native apps without needing to set up and configure the native development environment. It provides a development environment that is fully set up and ready to use, as well as a set of tools and services to help developers build, test, and deploy their apps.

### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the \_\_\_\_ workflow.

Simplified

### What is the difference between React Native and Expo?

The main difference between React Native and Expo is that React Native allows you to use the full power of the underlying platform, while Expo abstracts away many of the platform-specific details and provides a more opinionated workflow.
[expo snack](https://snack.expo.dev/)

Checkout this tool. What does snack allow you to do?
[ejecting](https://docs.expo.dev/versions/latest/expokit/eject)

### What does “eject” mean within the context of Expo?

Ejecting in the context of Expo means to remove the app from the Expo development environment and configure it to be built and run as a standalone app.

### When should you not eject?

You should not eject an app if you want to continue using Expo's development and hosting services, or if you want to continue to use the Expo client app for testing and deployment.

### Why might you choose to eject?

You might choose to eject an app if you need to use native modules or APIs that are not currently supported by Expo, or if you want to have more control over the build process and configuration of your app.
