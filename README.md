# NavigationToast
Shows Navigation Toast below the bar Ex: "No Internet connection."

### Usage

```swift

NavigationToast.init(duration: 0.5, delay: 3)
  .message(message: "No Internet Connection.")
  .messageIcon(icon: #imageLiteral(resourceName: "warning-icon"))
  .messageColor(color: .white)
  .messageFont(font: UIFont.init(name: "Helvetica", size: 15.0)!)
  .backgroundColor(color: UIColor.red)
  .show()
  ````
  
  Use with View controller 
  
  ```swift

  //Show navigationToast with `self` (UIViewController) with default configuration.
  self.navigationToast(message: "No Internet Connection.")
  
  ```
