- **Disable list of apps:**  
```
xargs -a packages.txt -n1 adb shell pm disable-user --user 0
```

- **Clear Data for list of apps:**  
```
xargs -a packages.txt -n1 adb shell pm clear
```

- **List of privacy-invading apps that are safe to disable on Nothing OS:**
```
com.android.chrome
com.android.hotwordenrollment.okgoogle
com.android.hotwordenrollment.xgoogle
com.google.ambient.streaming
com.google.android.apps.bard
com.google.android.apps.docs
com.google.android.apps.maps
com.google.android.apps.nbu.files
com.google.android.apps.photos
com.google.android.apps.restore
com.google.android.apps.safetyhub
com.google.android.apps.tachyon
com.google.android.apps.turbo
com.google.android.apps.wellbeing
com.google.android.apps.youtube.music
com.google.android.as
com.google.android.as.oss
com.google.android.calendar
com.google.android.contacts
com.google.android.googlequicksearchbox
com.google.android.keep
com.google.android.odad
com.google.android.projection.gearhead
com.google.android.verifier
com.google.android.videos
com.google.android.youtube
com.nothing.ai.service
com.nothing.aiwidget
com.nothing.essentialintelligence
com.nothing.gallery
com.nothing.logkit
com.nothing.ntessentialrecorder
com.nothing.ntessentialspace
com.nothing.smartcenter
com.nothing.universal.search
com.nothing.user.center
com.nothing.userguide
```

- **Disable if present:**
```
com.aura.oobe.solutions
```
