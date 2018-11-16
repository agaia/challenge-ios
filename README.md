# iOS Challenge

## Coding Survey

Go to https://www.hackingwithswift.com/test and responds to intermediate swift coding test.
Send us the given url when you finished.

## Coding Test

#### *Brief*

We would like you to recreate the bank list in a brand new iOS Swift project.

API Bank List Endpoint Documentation link : **https://docs.bridgeapi.io/v2018-06-15/reference#list-banks**  
Please don’t use the documentation API url. Use the following instead : **https://sync-qa.bankin.com/banks**  
API client id:  
API client secret:  

When running, the application should list all banks, separated by countries. We would appreciate to see the current user local country section on top. You’re completely free to design your model based on API JSON data.

The code must be well architectured, and use some clean code best practice.  Regarding the design, you are free to do it however you want to. Don’t worry about the final execution, the most important is too check how you’re thinking and how you dive into new project. Keep in mind your best naming practices.

We are not really found of 100% coverage but well-written and well-placed unit tests would be really appreciated.

#### *Bonus*

The application can run offline which means all remote fetched data are saved locally.

#### *Technologies*

We don’t force to use any specific technology, framework or library but here are listed used one by layer:

- Dependency Management -> Cocoapods
- Networking -> AFNetworking/Alamofire
- UI -> Autolayout and programmatic NSLayoutConstraint
- Persistence -> CoreData, UserDefault, SAMKeychain
