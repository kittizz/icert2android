# icert2android
> install ssl certificate (root,user) to your android device.

##### if cannot mount system partition read write , try this.
    /Users/kittiza/Library/Android/sdk/emulator/emulator  -avd TEST -show-kernel -verbose -writable-system
    adb root
    adb remount
