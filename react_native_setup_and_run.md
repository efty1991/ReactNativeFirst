A)<H2> Before we go - install Java, Node js and python, from their respective websites</H2> 

1)Open command promt as administrator
check for the node js versions

2) instal react native command line tools.
		<br/><b>npm install -g react-native-cli  (npm means- node package manager)</b>
		
3) move to folder where u want to create a project.
	 <br/><b>then react-native init Albums</b>
	<br/>(it will create an react_native android project with name of album)
	
4) now after finished creating, there will appear two option (on my command prompt, it looks like bellow)
	To run your app on iOS:
		cd D:\react_native_projects\albums
		react-native run-ios
		- or -
		Open ios\albums.xcodeproj in Xcode
		Hit the Run button
   
	To run your app on Android:
		cd D:\react_native_projects\albums
		Have an Android emulator running (quickest way to get started), or a device connected
		react-native run-android
		
5) now start android studio
6) start an emulator
7) open (Open option from android option menu, do not use import)
8) install all missing sdk pluging or anythis appears at the time of opening that project
9) Now add or edit(in case already exits) two environmental variables named...
		-- JAVA_HOME (it is java JDK home directory for me it is, C:\Program Files\Java\jdk-10.0.1)
		-- Path , for the platform-tools of android sdk (it may already exists , please add your also, on my sytem it D:\sdk\sdk\platform-tools)
10) now restartd your commnad prompt as administrator again
11) now run above command for IOS or Android, accodingly urs, i m using mine 
		react-native run-android
12) Now project will run in emulator. to refress double press 'R' from keyboard. or press Ctr+M for developer menu, 
in developer menu there is reload option that we can select 
13) Now we are ready to do coding for react native, to again start this project use same step as strating emulator, using commant like 'react-native run-android' and refress or other options 

B)<H2>Now Install Atom and open the root module into atom (Atom is Editor for React Native), for managing the project configuration/syntax we uses linter and ES Linter forn the error/syntax/exception handling</H2> 
1) Now install Linter into atom then ESLint (There are many linter for managing error/eception for javascript)
	-- Open Atom->Packages->Setting View->Open->install->serach for linter-eslint
		-- select lint   -> click on install
		-- select eslint -> click on install
		
2) After finishing installation of the above, we will install a rules for eslint configuration, we can see the differnce by below image for the eslint syntax and config file.
<br/><b>npm install --save-dev eslint-config-rallycoding</b>

3) For project related setup and configuration create a new file in root directory .eslintrc
	-- 
	
	
	
	
	
	
	
	
	
	
	
	
	
	
<h2> C) React Native Guide--first install chocolaty <h2>
	@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
	
	
using chocolaty command install node.js, python2 and JDK
	<br/><b>choco install -y nodejs.install python2 jdk10</b>
