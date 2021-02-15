**CLASS**

# `TestRouter`

```swift
class TestRouter: TestRouterInterface
```

Listens from the about which screen to present and executes that.

## Properties
### `viewController`

```swift
weak var viewController: UIViewController?
```

Module's View Controller

## Methods
### `createModule()`

```swift
static func createModule() -> UIViewController
```

Setup Modules classes and viewController
- returns: UIViewController