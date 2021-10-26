

Control Room is a macOS app that lets you control the simulators for iOS, tvOS, and watchOS – their UI appearance, status bar configuration, and more. It wraps Apple’s own **simctl** command-line tool, so you’ll need Xcode installed.

You’ll need Xcode 12.0 or later to build and use Control Room on your Mac.


## Installation

To try Control Room yourself, download the code and build it through Xcode. It’s built using SwiftUI, so you’ll need macOS Big Sur in order to run it. You will also need Xcode installed, because it relies on the **simctl** command being present – if you see an error that you’re missing the command line tools, go to Xcode's Preferences, choose the Locations tab, then make sure Xcode is selected for Command Line Tools.

**Warning:** SwiftUI on macOS is a little flaky at times, so I highly recommend you update to the very latest macOS version if you want to avoid any surprises.


## Contribution guide

Any help you can offer with this project is most welcome – there are opportunities big and small so that someone with only a small amount of Swift experience can help.

Some suggestions you might want to explore:

- Handle errors in a meaningful way.
- Handle blocking operations, such as recording video or launching an app.
- Add documentation in the code or here in the README.
- Did I mention handling errors in a meaningful way?

You’re also welcome to try adding some tests, although given our underlying use of simctl that might be tricky.

If you spot any errors please open an issue and let us know which macOS and Xcode versions you’re using.

**Please ensure that SwiftLint returns no errors or warnings before you send in changes.