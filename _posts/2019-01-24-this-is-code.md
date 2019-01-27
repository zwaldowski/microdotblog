---
layout: post
microblog: true
audio: 
date: 2019-01-24 02:06:01 -0400
---

I wanted to test a post that has some monospaced stuff in it. Lorem ipsum dolor amet cred activated charcoal pork belly `CGFloat`, you know?

```swift
import UIKit

extension UIFont {

    static var readableWidth: CGFloat {
        return preferredFont(forTextStyle: .body).readableWidth
    }

    var readableWidth: CGFloat {
        let text = String(repeating: "M", count: 46)
        let attributedText = NSAttributedString(string: text, attributes: [
            .font: self
        ])
        let width = attributedText.size().width
        return ceil(width / 8) * 8
    }

}
```
