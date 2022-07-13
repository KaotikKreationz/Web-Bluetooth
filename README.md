# Web-Bluetooth
Nowadays, browsers are evolving, bringing new APIs and ways to connect to other devices and allowing access to more functionality than they ever did before. One such API is the Web Bluetooth API. (https://googlechrome.github.io/samples/web-bluetooth/)

This API is still in beta as of this writing, but once this gets released to the public, it will open a whole lot of opportunities for developers who want to use Bluetooth but don’t want to create a native application for each platform.

Even though the Bluetooth API is still in beta, we will try it out and make a simple web page that will pair with our phone and give us basic details such as the battery percentage, name of the device, and basic information provided by the device manufacturer.

We won’t be using styles in this tutorial because we just need to understand how to interact with the Bluetooth API with JavaScript.

Remember, not all browsers support this API, and you won’t be able to test this with every phone. Some phones might not allow fetching device information. In this tutorial, I will be using an Apple iPhone 11, which allows me to fetch my device information through Bluetooth on my browser without any problems.
