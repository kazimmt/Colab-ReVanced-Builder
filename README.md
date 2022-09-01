# Re-Vanced

Google colab Re-Vanced Builder.<br>
## 4 simple steps that's it.
⭐ The project if it works. 
   Follow me for updates.

1. Open `.ipynb` in Google [Colab](https://colab.research.google.com/github/kazimmt/Colab-ReVanced-Builder/blob/music-builder/Re-Vanced.ipynb)
2. Upload and copy id for `youtubemusic.apk` from drive.
    * Run the script, more info there.
3. Wait for the script to build, once you start it. 
4. Download your Revanced-Music..!

<hr>

You could manually provide compilation commands.
 but by default it uses non-root method from official [docs](https://github.com/revanced/revanced-documentation/wiki/Using-the-ReVanced-CLI-and-installing-ReVanced)
with `-d device-name` omitted.
``` # Non-Root
java -jar revanced-cli-all.jar -a some.apk -c -d device-name -o revanced.apk -b revanced-patches.jar 
```
``` # Root
java -jar revanced-cli-all.jar -a some.apk -c -d device-name -o revanced.apk -b revanced-patches.jar -e music-microg-support
```
<hr>

⚠️ This is not official revanced page. 
You can find it [here](https://github.com/revanced/)
