## macOS Catalyst Snippets - Popup Modal
### 1. Add to button action or use another method to call this function
````
@IBAction func basicTriggeringOption(sender: Any) {
      // Popup modal
      let storyboard : UIStoryboard = UIStoryboard(name: "ProfileScreen", bundle: nil)
      let popupVC = storyboard.instantiateViewController(withIdentifier: "hello") as! ProfileViewController
      popupVC.modalPresentationStyle = .formSheet
      popupVC.modalTransitionStyle = .crossDissolve
      popupVC.preferredContentSize = CGSize(width: 480, height: 150)
      present(popupVC, animated: true, completion: nil)
}
````
### Note:
Note if you are presenting this popup modal after selecting a system menu item, there may be a need to refresh the system menu.
This refresh would be done from the ViewController class where the popup modal is created or controlled

## Video Tutorial
youtube link
