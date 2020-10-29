# Amazon Chime iOS SDK CocoaPods Implementation

This is an S12 custom CocoaPods implementation of the Amazon Chime iOS SDK and is no way affiliated with Amazon, AWS or Amazon Chime. Any issues relating to Amazon Chime must be reported directly to the [Amazon Chime iOS SDK repository](https://github.com/aws/amazon-chime-sdk-ios).

## Updating the Project

In theory this should be relatively stable, but in the event that an update is required there is one major prerequisite. git-lfs.

git-lfs is required to manage the AmazonChimeSDK/AmazonChimeSDKMedia.framework/AmazonChimeSDKMedia binary as it is larger than the 100mb GitHub limit.

To install git-lfs, follow the instructions on [their website](https://git-lfs.github.com/).

## Cloning the Project

This project should ideally be cloned next to the base s12 app root directory. This would allow you to test any developments locally by updating the podfile in the s12 app.

Once cloned, run `git lfs fetch` and the tracked binary will be downloaded from git-lfs.
