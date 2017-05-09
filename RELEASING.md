Releasing
=========

Note: This may vary based on your distribution mechanism.  Assuming CocoaPods:

 1. Change the version in `Name.podspec` to reflect a new version.
 2. Update the `CHANGELOG.md` for the impending release.
 3. Update the `README.md` with the new version.
 4. Verify formatting with swiftlint (swiftformat.sh)
 5. `git commit -am "Release X.Y.Z."` (where X.Y.Z is the new version)
 6. `git tag "X.Y.Z"` (where X.Y.Z is the new version)
 7. `git push --tags`
 8. `pod trunk push Name.podspec`
 