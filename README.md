# sigma-ios-boilerplate
This is a boilerplate for my team
## Features

### APIs
* [ ] GET object
* [ ] GET array
* [ ] POST object
* [ ] PUT object
* [ ] PATCH object
* [ ] DELETE object
* [ ] Login
* [ ] Logout
* [ ] Register
* [ ] Upload image
* [ ] Download file
* [ ] Pagination
* [ ] Make API descriptions separate with logic code
* [ ] Make base URLs configurable from plist
* [ ] Unit test APIs

### Data
* [ ] Caching image
* [ ] Caching file
* [ ] Offline mode and database synchronization
* [ ] Automatic object mapping
* [ ] Offline database with `Realm`
* [ ] Observer data changes with `RxRealm`

### Login
* [ ] Email login with `poland services` form
* [ ] Facebook login
* [ ] OTP login
* [ ] Register account with email using `Eureka` form
* [ ] Forget password

### UI
* [ ] UI binding with `RxSwift`
* [ ] TableView list with `RxDataSources`
* [ ] CollectionView list with `RxDataSources`
* [ ] Empty data state with `DZNEmptyDataSet`
* [ ] Preheat list data
* [ ] Refresh list data
* [ ] Alert with `Whisper`
* [ ] Setting form using `Eureka`
* [ ] Select location using `GoogleMaps`
* [ ] Walkthrough

### Notification
* [ ] Push notification to simple server
* [ ] Push notification using `OneSignal`
* [ ] Receive notification and navigate to appropriate scene

### Chat
* [ ] Firebase chat

### Crash report and Analytics
* [ ] Crashlytics
* [ ] Analytics with `Answer` or `GoogleAnalytics`
* [ ] BuddyBuild SDK

### Payment and InApp Purchase
* [ ] Stripe
* [ ] Apple InApp Purchase

### CI/CD
* [ ] Multi-target for multi environments: Development, Alpha, Beta, Production
* [x] Automatically check coding style and conventions using `SwiftLint`
* [x] Automatically generate resources code using `SwiftGen`
* [ ] Unit Testing using `Quick` and `Nimble`
* [ ] UI Testing
* [ ] Run unit tests with `scan`
* [ ] Automatically create and maintain iOS code signing, provision certificates using `cert` and `sigh`
* [ ] Automatically generate and renew your push notification profiles using `pem`
* [ ] Sync certificates and profiles across your team using `match`
* [ ] Automatically build all target using `gym`
* [ ] Use `fastlane` to connect all automation tools
* [ ] Connect `buddybuild` to project's Git to automatically build app
* [ ] Documentation for CI/CD which include `fastlane`, `buddybuild`, `SwiftGen`, `SwiftLint`, `Unit Testing`, `UI Testing`

## Documentation
* [ ] Architecture
* [ ] Project Structure
* [ ] CI
* [ ] UnitTest

## Technics

#### Code generator
1. R.Swift

#### Networking stack
1. Alamofire
2. Moya
3. ObjectMapper
4. Moya-ObjectMapper
5. RxSwift
6. RealmSwift
7. RxRealm

#### Image
1. Kingfisher

#### Caching
1. HanekeSwift
2. Nuke

#### UI
1. DZNEmptyDataSet
2. Whisper
3. Google Maps
4. SlideMenuControllerSwift
5. SnapKit
6. BWWalkthrough
7. ...

#### RFP
1. RxViewModel
2. RxDataSources
3. RxOptional
4. Action

#### Preheat and reload data
1. Preheat
2. PullToRefreshSwift

#### Analytics and Crash tracking
1. Crashlytics
2. Answer
