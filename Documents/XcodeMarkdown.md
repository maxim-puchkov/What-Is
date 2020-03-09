# Xcode Markdown #

[List of options][format-options]




## Callouts ##
- Attention: ...
- Author: ...
- Authors: ...
- Bug: ...
- Complexity: ...
- Copyright: ...
- Date: ...
- Experiment: ...
- Important: ...
- Invariant: ...
- Note: ...
- Postcondition: ...
- Precondition: ...
- Remark: ...
- Remarks: ...
- Requires: ...
- See: ...
- Since: ...
- Todo: ...
- Version: ...
- Warning: ...


## Example ## 

Documentation for `User` structure.

```swift
//
//  User.swift
//  Xcode Markdown
//
//
//
//

import Foundation

/**
 This is your User documentation.
 A very long one.
 
 # Text
 It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](https://google.com)
 
 # Lists
 Sometimes you want numbered lists:

 1. One
 1. One
 1. One
    1. One
        1) One)
 
 Sometimes you want bullet points:

 * Start a line with a star
 * Profit!

 Alternatively,

 - Dashes work just as well
 - And if you have sub points, put two spaces before the dash or star:
    - Like this
    - And this
        - ...
 
 # Code
 ~~~
 if (isAwesome) {
   return true
 }
 ~~~
*/
struct User {
    let firstName: String
    let lastName: String
}
```


[format-options]:  https://stackoverflow.com/questions/19168423/what-are-the-new-documentation-commands-available-in-xcode-5
