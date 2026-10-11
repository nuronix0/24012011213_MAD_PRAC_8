
# Mobile Application Development – Practical 8

## Student Information

- **Name:** Aditya Prajapati
- **Enrollment Number:** 24012011213
- **Subject Name:** Mobile Application Development
- **Practical Number:** 8

## Aim

To create your first Hello World iOS app in SwiftUI.

## Practical Content

### 1. Create a New iOS App

1. Open Xcode and select **File → New → Project**.
2. Choose the **App** template from the iOS tab.
3. Set the app name to `hello world`.
4. Select **SwiftUI** as the interface technology.
5. Select **Swift** as the programming language.
6. Keep Core Data and unit testing options unselected.
7. Enable the Git repository option and save the project.

### 2. Understanding the Structure of a Basic SwiftUI iOS App

The project contains source code files that define the app's main scene and user interface.

**hello_worldApp.swift**

```swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

**ContentView.swift**

```swift
struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

The `App` structure defines the main scene, while `ContentView` displays the "Hello, world!" text.

### 3. Run the iOS App in the Simulator

1. Select an iOS simulator in Xcode.
2. Click the **Play** button to build and run the application.
3. Verify that the application runs successfully.
4. Open `ContentView.swift` to view the preview code.
5. Press **Resume** to preview changes to the user interface.

SwiftUI previews allow developers to view interface changes without running the app in a simulator.

## Practical PDF

Click below to view the complete practical PDF.

[**View Practical 8 PDF**](24012011213_MAD_PRAC8.pdf)
