# SwiftAlert
An Alert/Question library for Swift

***How to use :***

The usage is pretty simple, Just copy the file SwiftAlert.swift into your project, And in each of your `ViewController` you can call `alert` or `showQuestion`
That's it!

**Alert** 
It has two argument, The first one is a string which is the message to be shown and the second is `completion handler` which is optional and will be called by the time the alert is dismissed.

*Example 1:*
alert(Message: "Hello World")

*Example 2:*
alert(Message: "Hello World", completion: { print("Hellow word has shown to user")})
