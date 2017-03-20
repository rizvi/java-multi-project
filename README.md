# java-multi-project
gradle multiple project with ivy

mat@My-PC:~/Desktop/gradleproject/java-multi-project$ gradle clean
:project1:clean UP-TO-DATE
:project2:clean UP-TO-DATE

BUILD SUCCESSFUL

Total time: 22.284 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.10/userguide/gradle_daemon.html
mat@My-PC:~/Desktop/gradleproject/java-multi-project$ gradle build
:project2:compileJava UP-TO-DATE
:project2:processResources UP-TO-DATE
:project2:classes UP-TO-DATE
:project2:jar
:project1:compileJava UP-TO-DATE
:project1:processResources UP-TO-DATE
:project1:classes UP-TO-DATE
:project1:jar
:project1:assemble
:project1:compileTestJava UP-TO-DATE
:project1:processTestResources UP-TO-DATE
:project1:testClasses UP-TO-DATE
:project1:test UP-TO-DATE
:project1:check UP-TO-DATE
:project1:build
:project2:assemble
:project2:compileTestJava UP-TO-DATE
:project2:processTestResources UP-TO-DATE
:project2:testClasses UP-TO-DATE
:project2:test UP-TO-DATE
:project2:check UP-TO-DATE
:project2:build

BUILD SUCCESSFUL

Total time: 12.745 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.10/userguide/gradle_daemon.html
mat@My-PC:~/Desktop/gradleproject/java-multi-project$ 

