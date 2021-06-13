# CryptoCurrencyApp
This is a sample app to highlight android MVVM architecture implemented for CryptoCurrency App

What is this App?
This is a crypto currency app for bitcoin, mainly showing 3 charts for different variants of bitcoin trade. Like transaction value, UsdPricing and total bitcoins mined.


What architechture it implements and How?
This uses android MVVM architecture, we have a MainActivity which is dependent on BlockChainViewModel which is dependent on Repository which is dependent on Rest Apis

Advantage is the entire principle of separation of concerns have been achieved following the above.

Which Chart library been used?
MPAndroidChart (free library)

What are remaining things you want to add to this?
More Ui Tests based on idling resource and network offline cases

How should we import this project and Open in Android Studio?
Download the zip attached, extract it. Now you can double click on build.gradle -> It will open project in Android Studio or From Android Studio go to File -> Open Project -> Choose build.gradle


