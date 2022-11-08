## macOS Catalyst Snippets
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
