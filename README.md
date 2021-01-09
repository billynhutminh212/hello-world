import GoogleMobileAds
import UIKit

class ViewController: UIViewController {

  var interstitial: GADInterstitial!

  override func viewDidLoad() {
    super.viewDidLoad()
    interstitial = GADInterstitial(adUnitID: "ca-app-pub-8894503345925579~3555022468")
  }
}
