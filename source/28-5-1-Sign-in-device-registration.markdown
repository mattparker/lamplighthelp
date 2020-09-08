# 28.5.1 Setting up computers to use for public sign-in

> You need to register the devices you'll use for public sign-in because no login is required to access the sign-in page

### Overview

The sign-in page is publicly accessible, if you know or guess the URL, then access to it means that you can see published {{work}} records, add people to them, and create new profiles in your system.  To provide some security, you need to register the device and browser that you'll use, and only registered devices can access the sign-in page.  In effect, registration gives the device a type of long-lasting password which works only for the sign-in page.


#### Viewing sign-in module settings

To view sign-in module settings, as a system administrator go to System Admin > Publishing module > Sign-in module settings and device management.  You will see a screen like this, where we have already registered three devices:

![Sign-in module admin](28.5.0a.png)

The first section gives the URL for the sign-in page, and also a QR code version of the URL.  Once you have registered a device you need to
visit this URL to see the public sign-in page for today.  This URL doesn't change for your system, so you can save it as a favourite and refresh each day on the device without having to go into system admin.

The currently registered devices are listed, and by ticking the box you can de-register them.  You should do this if the device is stolen, or you suspect it's been tampered with, or it's no longer being used as a sign-in device.  Click the 'update devices' button to de-register an existing device.

#### Registering a new device

To add a new device, enter a name for it.  This is for your reference only, so give it a name that will mean you can tell which device is which - perhaps add a brand name and model number, for example.  Then click 'update devices'.  You will see a screen like this, showing a QR code and the URL it represents.

![Sign-in module device registration](28.5.1a.png)

You now need the device you'll be using as the public sign-in device.  Use its QR scanner (or transfer the URL by email or something) to visit the registration URL.  Make sure you're not logged in to Lamplight on the device you are registering.  When you do, Lamplight will place an identifier (like a cookie) that will allow that browser on that device to access the sign-in page.  Other browsers won't work.  You can now return to the device management page.

You can now visit the URL shown at the top of the sign-in module settings page on your registered device.  But you'll need some [{{work}} records set up appropriately](/en/help/index/p/28.5.2) to see anything useful.

###### publish module

