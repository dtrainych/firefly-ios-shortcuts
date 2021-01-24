# iOS Shortcuts for Firefly III
iOS Shortcut to create transactions in Firefly III
# Usage
### Setup
You have to import the following four shortcuts to your iOS device. The first three are function-like dependencies of the fourth one, which is used to add a transaction. 

To be able to import shortcuts from outside the app gallery, you have to go to _Settings_ > _Shortcuts_ and enable _Allow Untrusted Shortcuts_.

Click on Shortcut name to view it on Web or import it directly to iOS device via iCloud link.
-   [List Accounts](https://showcuts.app/share/view/fae3b077e3a1458bbd7307659c7f5260)  - [Import](https://www.icloud.com/shortcuts/fae3b077e3a1458bbd7307659c7f5260)
-   [List Categories](https://showcuts.app/share/view/842ba6e577ed415e9013e742db4d7137)  - [Import](https://www.icloud.com/shortcuts/865fbfcda1b140f78494d1f501647560)
- [List Budgets](https://showcuts.app/share/view/04898949709d4554b3c53047671ced1b)  - [Import](https://www.icloud.com/shortcuts/04898949709d4554b3c53047671ced1b)
-   [Add Transaction](https://showcuts.app/share/view/d9f7ac7208574a6dab2003a6de56e536)   - [Import](https://www.icloud.com/shortcuts/d9f7ac7208574a6dab2003a6de56e536)

While adding _Add Transaction_ shortcut, you’d be prompted to enter your Firefly URL and Personal Access Token. The URL is where you’ve hosted the app, complete with the protocol and without a trailing slash (like `https://demo.firefly-iii.org`). You can generate the token from Firefly by going to _Options_ > _Profile_ > scroll down to _Personal Access Tokens_ and click on _Create New Token_.
![Firefly III shortcuts folder](media/firefly-shortcut-folder.jpg)
### Creating a transaction
Run _Add Transaction_ shortcut and follow the steps.
You will be asked for following parameters: Transaction type, Source account, Destination account, Description, Amount, Budget and Category.
- Source and destination account can be asset, revenue or expense accounts based on transaction type.
- Budget and category parameters can be skipped.

![Demo gif](media/firelfy-shortcut-demo.gif).

# Acknowledgements
Based on Sid's Verma [post](https://sidverma.io/2019/12/06/firefly-iii-ios-shortcuts/).  
[Showcuts](https://showcuts.app/)
