# SwiftSetlistFM
[![Build Status](https://app.bitrise.io/app/94a7be0c-1c8f-45b4-b474-d5b657892242/status.svg?token=zS8gqA0ZGrIBlzSSDoxHQw&branch=main)](https://app.bitrise.io/app/94a7be0c-1c8f-45b4-b474-d5b657892242)
[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fbdh777psu%2FSwiftSetlistFM%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/bdh777psu/SwiftSetlistFM) [![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fbdh777psu%2FSwiftSetlistFM%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/bdh777psu/SwiftSetlistFM)

A Setlist.fm API Swift Package (swift-openapi-generator edition)


## Description
This setlist.fm API Swift Package has been designed to give you easy access to setlist data in order to build fancy applications. This service provides methods to get both setlists and components of setlists such as artists, cities, countries or venues.

This is the Swift 5.8, OpenAPI 3.0.x, Apple swift-openapi-generator edition of the [DRLSetlistFM](https://github.com/bdh777psu/DRLSetlistFM) Swift Package.


## Requirements
... Understand how setlist.fm works (the [FAQ](https://www.setlist.fm/faq) and [Guidelines](https://www.setlist.fm/guidelines) are good starting points),
... read this documentation carefully and
... [apply for an API key](https://www.setlist.fm/settings/api) (link for logged in users only) - if you're not a registered user yet, then [register first](https://www.setlist.fm/signup) (it's free).


## Internationalization
Most of the featured methods honor the 'Accept-Language' header. This header is used for localizing cities and countries. The default language is English (en), but you can provide any of the languages Spanish (es), French (fr), German (de), Portuguese (pt), Turkish (tr), Italian (it) or Polish (pl).


## Installation
SwiftSetlistFM is available as a Swift Package. To install
it, simply add the following line to your 'Package.swift' file:

```ruby
.package(url: "https://github.com/bdh777psu/SwiftSetlistFM", branch: "main"),
```

## API Keys
API keys must be included in the request with the 'x-api-key' header.


## Usage Example
To get started, check out the 'Using the generated code in your target' section of the official Apple swift-openapi-generator [documentation](https://swiftpackageindex.com/apple/swift-openapi-generator/0.1.3/tutorials/swift-openapi-generator/clientswiftpm#Using-the-generated-code-in-your-target), which contains step-by-step tutorials!

See the generator in action in [Meet Swift OpenAPI Generator from WWDC23](https://developer.apple.com/videos/play/wwdc2023/10171/).


### Supported platforms and minimum versions

| Component | macOS | Linux | iOS | tvOS | watchOS |
| -: | :-: | :-: | :-: | :-: | :-: |
| Generator plugin and CLI            | ✅ 10.15+  | ✅     | ❌     | ❌     | ❌    |
| Generated code, runtime, transports | ✅ 10.15+  | ✅     | ✅ 13+ | ✅ 13+ | ✅ 6+ |


## Author
Diogo Lessa


## License
SwiftSetlistFM is available under the MIT license.
