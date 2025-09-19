# DebiutApp
plugins { id("com.android.application") version "8.6.0" apply false; id("org.jetbrains.kotlin.android") version "2.0.0" apply false }


org.gradle.jvmargs=-Xmx2048m -Dfile.encoding=UTF-8
android.useAndroidX=true
kotlin.code.style=official


pluginManagement { repositories { google(); mavenCentral(); gradlePluginPortal() } }
dependencyResolutionManagement { repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS); repositories { google(); mavenCentral() } }
rootProject.name = "DebiutOfflineApp"
include(":app")
