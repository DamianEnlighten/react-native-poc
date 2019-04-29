React Native POC

Dependencies- 
	
	Android:https://developer.android.com/studio
	iOS:Xcode

	Node:https://github.com/coreybutler/nvm-windows

	Python2: https://www.python.org/downloads/release/python-2715/

	JDK: https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
	Using JDK 12.0.1

	Configure Android studio/xcode:
	https://facebook.github.io/react-native/docs/getting-started

Setup-

	In terminal/cmd/git bash
	nvm install 8.11.3
	nvm use 8.11.3
	npm install -g react-native-cli
	react-native init <project name>
	cd <project name>

Deploy-

	Android-
		Start Android emulator
		then run: react-native run-android
	iOS-
		requires a mac
		react-native run-ios
				
Basic tutorials: https://facebook.github.io/react-native/docs/tutorial
