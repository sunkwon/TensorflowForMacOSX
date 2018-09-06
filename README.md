This page for ones who want to use nvidia GPU cards in his/her own mac.
Because I love to do research/develop on MacOSX but the frameworks to handle AI are operating with Nvidia Cuda,
So I have been starting to find how to operate the frameworks on MacOSX.
I will write about the success and fails of the works in here.
If you want to share the idea or works, please share with us.

======= in MacOS High Sierra, 10.13.6 =======
0. (Failed) CUDA 9.2 + cudnn 7.2.1.38 + XCode 9.4.1 + Compiling Tensorflow r1.10 from sources
1. (Failed) CUDA 9.2 + cudnn 7.2.1 + XCode 8.3.3 + Compiling Tensorflow r1.10 from sources

======= How to install the previous versions of XCode (legacy)  =====
0. Download the previous version of Xcode
1. Move to the location where you download the xcode in terminal
2. Rename it (Xcode.app) to another one. for example, if you downloaded XCode 8.3.3, then:  mv XCode.app XCode-8.3.3.app
3. Copy the renamed XCode folder to /Applications/  , (ex) mv XCode-8.3.3.app /Applications
4. Change the default path of XCode command line tools to the legacy Xcode. (ex) sudo xcode-select -s /Applications/XCode-8.3.3.app/Contents/Developer
5. If you want to roll back to the newest XCode, enter the command like this. (ex) sudo Xcode-select -s /Applications/Xcode.app/Contents/Developer


 
