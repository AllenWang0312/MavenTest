
### how to import 
   1. add  repository to your build.gradle(project)
    allprojects {
  
        repositories {
            maven { url "https://raw.githubusercontent.com/OoswantoO/MavenTest/master" }
        }
    }
   2. import like this in you app
    dependencies {
        ...
        implementation 'com.github.OoswantoO:kbaselib:1.1.2'
   
    }