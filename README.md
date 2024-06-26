<a href="https://www.producthunt.com/posts/robotqa-real-device-debugging-on-cloud?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-robotqa&#0045;real&#0045;device&#0045;debugging&#0045;on&#0045;cloud" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=458979&theme=light" alt="RobotQA&#0032;Real&#0032;Device&#0032;Debugging&#0032;on&#0032;Cloud - Android&#0032;Development&#0032;Debugging&#0032;Plugin&#0032;on&#0032;Cloud&#0032;Devices | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
<a href="https://www.g2.com/products/robotqa-real-device-debugging-on-cloud/reviews" target="_blank"><img src="https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/g2-logo.png?raw=true" alt="RobotQA&#0032;Real&#0032;Device&#0032;Debugging&#0032;on&#0032;Cloud - Android&#0032;Development&#0032;Debugging&#0032;Plugin&#0032;on&#0032;Cloud&#0032;Devices | G2.com" style="width: 54px; height: 54px;" width="54" height="54" /></a>

# RobotQA Android Studio Plugin - Real Device Debugging on Cloud
![RobotQA Plugin Main](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/main-photo.png?raw=true)

RobotQA serves as a mobile application testing and development platform, a repertoire of over 60 real devices encompassing iOS, Android, Huawei, and Xiaomi operating systems. This plugin facilitates the integration of the RobotQA device farm, enabling remote debugging of Android applications across Android, Huawei, and Xiaomi OS devices.

## How to install Android Studio Plugin

This plugin is tailored for use with Android Studio and Intellij IDE. Therefore, it is imperative to ensure the prior installation of Android Studio, with support extending from versions released in 2021 onwards. The installation of the plugin can be executed through two distinct methods:

**Note: Please ensure that the adb tools are installed on your system before proceeding.**

### Upload using Android Studio Plugin Page

Start Android Studio and click 
> Settings-->Plugins-->Marketplace </code></pre>

Find **RobotQA Real Device Debugging on Cloud** plugin and install.

## How to start debugging

To start this plugin usage, firstly you have to register on RobotQA.com. We offer **1 week free** access to all users. 
When Android Studio starts, click **Help-->Find Action** and search: *RobotQA Device List*

### Register and get token

When you activate this plugin, Device List table will be displayed. After opening device list, click **Start free usage**.

![RobotQA Plugin Table Page](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/first-page.png?raw=true)

Follow the opening link. When you register our platform we will send token to use on plugin. 

### Get Token From Profile Page

If you need to find token value, you can find it in "Profile Page". Copy that value and use in plugin setting.



### Activate device farm connection

Upon acquiring a token, input it into the designated textbox within the **RobotQA Token Setting** dialog. To access this dialog, navigate to **Help --> Find Action** and search for it accordingly. Once the token value has been entered, you will gain the capability to establish connections with devices and access the associated screen.

![RobotQA Plugin Enter Token](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/token-enter.png?raw=true)

### Connect a device and start debugging

To connect a device, firstly click **Enable RobotQA Device Farm Connection** button. 
*Note that: When you enable connection and using our device farm, you will lost your local device connections*

After enabling device farm connection, you can connect any devices that you want. After connecting devices, select a device from connected devices and start project as you do in Android Studio.

![RobotQA Plugin Connect Device](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/device-connected.png?raw=true)

After starting project, open **RobotQA console** and follow the logs. These logs give information about *user packages, device status, live testing links etc.* 
When device connection is ready, click the link in Notification to connect and use device manually. This functionality enables you to perform actions such as clicking, swiping, and navigating between pages with ease.

![RobotQA Plugin Live Testing](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/live-testing-click.png?raw=true)

![RobotQA Plugin Live Testing Page](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/live-testing-page.png?raw=true)

### Close debugging

When you finished your debugging, stop the project run as usual. * ***Important Note: Close the live testing page when you finished your testing*** * 
RobotQA offers reports for each debugging. To get video and logs about your debugging, login to [RobotQA login page](https://robotqa.com/login) and click the latest test on dashboard. You will see the this report.

![RobotQA Plugin Dashboard](https://github.com/robotqa/Android-Studio-Plugin-for-Debugging/blob/main/test-result.png?raw=true)

## About Issue Tracking

When you face a problem, please open a ticket here. We will use this repo for tracking all issues. Also you can write us *hello@robotqa.com*

## About RobotQA

RobotQA is a mobile application development and test platform. RobotQA has more than 60 real devices including iOS, Android, Huawei and Xiaomi OS. In terms of testing capabilities, RobotQA provides support for popular frameworks like Appium and UiPath, allowing users to remotely execute their test scripts on real devices. Additionally, the platform offers a convenient codeless testing feature to streamline the initiation of tests. On the development front, RobotQA facilitates debugging of Android applications through dedicated plugins, enabling remote debugging on real devices. For further details, please visit: [RobotQA](https://robotqa.com)

### Conclusion

This plugin is specifically crafted for testing Android mobile applications. Its functionality enables you to assess the performance of your mobile applications on real devices, ensuring accuracy and reliability. Moreover, in instances where debugging is necessary for a particular device, you can utilize this plugin to establish a connection and remotely debug your applications. Access to the live testing page grants you the opportunity to interact with devices as if they were physically in your possession, facilitating comprehensive testing and debugging procedures.
