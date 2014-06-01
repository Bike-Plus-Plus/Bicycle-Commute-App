# cordova (phonegap) wrapper for Bike++ app

## setup

`npm install -g cordova`

- [Download the Android SDK](http://developer.android.com/sdk/index.html#download)
- run `/PATH/TO/adt-bundle-linux-x86_64-20140321/eclipse/eclipse`...then close
  it. (I'm not cerain that this step is required.)
- Add the SDK tools to your PATH
  ```
  # Add Android SDK tools
  export PATH="$PATH:/PATH/TO/adt-bundle-linux-x86_64-20140321/sdk/tools"
  export PATH="$PATH:/PATH/TO/adt-bundle-linux-x86_64-20140321/sdk/platform-tools"
  ```
- `cordova platform add android`
