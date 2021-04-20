# Juniot IOS Developer

## Bocharov Philipp

### Contacts:
	* *email*: filins28@gmail.com
	* *phone number*: +375(29)302-13-10
	* *linkedIn*: https://www.linkedin.com/in/philip-bocharov-3331b1188/


### About me:
*I'm 25 y.o. I am a purposeful and demanding person. I perform tasks after I carefully study the materials that will help with its implementation.
Sociable, which helps me to work in a team.*

### About my skills:
#### Hard Skills:
	* Xcode
	* UIKit
	* Foundation
	* GCD
	* ARC
	* CocoaPods

#### Soft Skillls:
	* Understant the principles of OOP
	* SOLID

#### Languages:
	* Swift
	* Experience with objective-c

### Latest code examples:

class BankingTests: XCTestCase {

  var checkingAccount: CheckingAccount!
  
  override func setUp() {
    super.setUp()
    checkingAccount = CheckingAccount()
  }

  override func tearDown() {
    checkingAccount.withdraw(amount: checkingAccount.balance)
    super.tearDown()
  }

  func testNewAccountBalanceZero() {
    let checkingAccount = CheckingAccount()
    XCTAssertEqual(checkingAccount.balance, 0)
  }

  func testCheckOverBudgetFails() {
    let checkingAccount = CheckingAccount()
    let check = checkingAccount.writeCheck(amount: 100)
    XCTAssertNil(check)
  }
}

### About my experience:
	* made a simple app
	* work with another Apis such as Mapbox, FB, Google Singin
	* work with CoreData and CoreAnimation

### About education: 
2019 - BSUIR

### English level
	I train with mentor twice a week

