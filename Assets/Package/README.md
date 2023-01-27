# Unity LevelPlay SDK (unnofficial mirror)

Unity NPM version of Unity Levelplay SDK! This repository applies the same license terms of the original version.
Original Source Location: https://developers.is.com/download-ironsource-sdk/.

# How to install

At package.json, add these lines of code:
```json
"com.gameworkstore.ulevelplay": "https://github.com/GameWorkstore/ulevelplaysdk.git#7.2.7"
"com.google.external-dependency-manager":"https://github.com/GameWorkstore/com.google.external-dependency-manager.git#1.2.175",
```

And wait for unity to download and compile the package.

you can upgrade your version by including the release version at end of the link:
```json
"com.gameworkstore.ulevelplay": "https://github.com/GameWorkstore/ulevelplaysdk.git#7.2.7"
```

Copy \IronSource\Plugins\Android\ and all it's contents to your assets folder (Path Included).
Include IronSource.plugin (on this repo, it's set excluded to not conflict with your copy).
otherwise you are not gonna be able to compile for android;
(original IronSourceSDK looks into this path to find the android manifest at this project library).

# Contributions

If you are using this library and want to submit a change, go ahead! Overall, this project accepts contributions if:
- Is a bug fix;
- Or, is a generalization of a well-known issue;
- Or is performance improvement;
- Or is an improvement to already supported feature.

Also, you can donate to allow us to drink coffee while we improve it for you!
