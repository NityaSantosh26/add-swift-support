# add-swift-support
Solution for ITMS-90426: Invalid Swift Support - The SwiftSupport folder is missing. Rebuild your app using the current public (GM) version of Xcode and resubmit it.

# Usage:

Copy the script into a text editor and save it with no extension
Make it executable like so: chmod +x path/to/script
Run it from the Terminal in one of two ways:
path/to/script ipa_path="path/to/ipa" archive_path="path/to/xcarchive"
path/to/script ipa_path="path/to/ipa" toolchain_path="path/to/toolchain"
