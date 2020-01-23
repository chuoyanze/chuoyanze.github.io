---
title: Android Error
categories: Android
date: 2019-12-29 12:30:00
---





`ERROR: The minSdk version should not be declared in the android manifest file. You can move the version from the manifest to the defaultConfig in the build.gradle file.`

注:此错误出现于高版本AS导入低版本AS项目的时候。高版本AS项目将minSdk 和targetSdk迁移到build.gradle中去了，只需要将AndroidManifest.xml中的删除即可。