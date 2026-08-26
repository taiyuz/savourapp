# savourapp — early SwiftUI scaffold

Xcode SwiftUI + SwiftData starter for a restaurant app idea (Savour). Default `Item` list, add/delete timestamps, and a vendored `Alamofire.xcodeproj`.

This is not a shipped product. `ContentView` is the stock Xcode template (list of `Item.timestamp`). Networking is not implemented in app sources; Alamofire is present only as an Xcode project tree.

The more complete (still unfinished) Savor attempt is [Authentication-and-ML](https://github.com/taiyuz/Authentication-and-ML).

## Layout

```
savour/
  savour/            SwiftUI app (savourApp, ContentView, Item)
  savour.xcodeproj
  Alamofire.xcodeproj
  savourTests/       Xcode UI/unit test targets
  savourUITests/
```

## Stack

SwiftUI, SwiftData, iOS. Created August 2024.

## Run

Open `savour/savour.xcodeproj` in Xcode 15+ and run the `savour` scheme on a simulator.

## Status

Homework / early scaffold. Keep it on the profile as iOS shipping practice, not as a backend or ML system.

MIT license for original files in this repo.
