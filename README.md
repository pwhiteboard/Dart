# Dart Installation
Install Homebrew and run following Commands

brew tap dart-lang/dart
brew install dart

To upgrade when a new release of Dart is available:

brew upgrade dart

To switch between locally installed Dart releases, first install the version you want to switch to if you haven’t. For example, to install Dart 2.12:

brew install dart@2.12

Then to switch between versions, unlink the current version and link the desired version.

brew unlink dart@<old> && brew unlink dart@<new> && brew link dart@<new>
  
 
  You can use the VS code for writting dart program.
  Dart program file extension is .dart
  You can run dart program using dart example.dart command in terminal.
