# Words App

Words app allows you to select a letter and use Intents to navigate to an Activity that
presents a number of words starting with that letter. Each word can be looked up via a web search.

Words app contains a scrollable list of 26 letters A to Z in a RecyclerView. The orientation
of the RecyclerView can be changed between a vertical list or a grid of items.

The app demonstrates the use of Intents in two ways:
* to navigate inside an app by specifying an explicit destination, and,
* allowing Android to service the Intent using the apps and resources present on the device.

Also demonstrates creation of simple appbar menu.

## Intents

An intent is an object representing some action to be performed. The most common, but certainly not only, use for an intent is to launch an activity. 
There are two types of intents — implicit and explicit.

Generally, when showing an activity in your own app, you use an explicit intent.

An implicit intent is a bit more abstract, where you tell the system the type of action, such as opening a link, composing an email, or making a phone call, and the system is responsible for figuring out how to fulfill the request. You've probably seen both kinds of intents in action without knowing it.

For actions that don't necessarily involve the current app—say, you found an interesting Android documentation page and want to share it with friends—you'd use an implicit intent.

## RecyclerView

Learn more about how to implement RecyclerView: https://developer.android.com/guide/topics/ui/layout/recyclerview

## Appbars

Learn more from MaterialDesign.io
https://material.io/components/app-bars-top

## How to install apk:

You can find app-debug.apk file in app->builds->outputs->debug. Download and install it on you smartphone.

(Included appbar icons will only be visible on API level 21 or later, and Adapive icon will be available from API level 26 or later.)
