import GoogleMobileAds
import UIKit

class ViewController: UIViewController {

  var interstitial: GADInterstitial!

  override func viewDidLoad() {
    super.viewDidLoad()
    interstitial = GADInterstitial(adUnitID: "ca-app-pub-3940256099942544/4411468910")
  }
}
