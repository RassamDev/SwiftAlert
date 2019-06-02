# SwiftAlert
An Alert/Question library for Swift

***How to use :***

The usage is pretty simple, Just copy the file SwiftAlert.swift into your project, And in each of your `ViewController` you can call `alert` or `showQuestion`
That's it!

**alert** 
It has two argument, The first one is a string which is the message to be shown and the second is `completion handler` which is optional and will be called by the time the alert is dismissed.

*Example 1:*

alert(Message: "Hello World")

*Example 2:*

alert(Message: "Hello World", completion: { print("Hellow word has shown to user")})

**showQuestion**
It has 5 argument message: that to be shown to user, Ok Button Text, Cancel Button Text, Action to perform after Ok is pressed, Action to perform after Cancel is pressed.

*Example 1:*

showQuestion(Message: "Do you want to quit?", OKLabel: "Yes", CancelLabel: "No", OkAction: {
            fatalError()
        })

*Example 2:*

showQuestion(Message: "Do you want to quit?", OKLabel: "Yes", CancelLabel: "No", OkAction: {
            fatalError()
        },CancelAction: {print("No pressed")})
