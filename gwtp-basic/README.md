#GWTP Basic

This is a basic GWTP Archetype.

##Maven Archetype Usage

1. Goto directory you want the project.
2. Rename parameter below `com.projectname.project` to a package naming scheme you like.
3. Rename parameter `new-project-name` to a project title you like.
4. Rename parameter `-dmodule=Project` to a name that starts with a capital. Name it like `MyAppModule` or `Application`.
5. Run the mvn archetype generator below.

* This project Project.gwt.xml module name is hard coded and will will not be changed from the parameters below at this time.

```
mvn archetype:generate -DarchetypeGroupId=com.arcbees.archetypes \
-DarchetypeRepository=https://oss.sonatype.org/content/repositories/snapshots/ \
-DarchetypeArtifactId=gwtp-basic-archetype \
-DarchetypeVersion=1.5.1 \
-DgroupId=com.projectname.project \
-DartifactId=new-project-name \
-DmoduleName=Project
```

##Thanks to
[![Arcbees.com](http://arcbees-ads.appspot.com/ad.png)](http://arcbees.com)

[![IntelliJ](https://lh6.googleusercontent.com/--QIIJfKrjSk/UJJ6X-UohII/AAAAAAAAAVM/cOW7EjnH778/s800/banner_IDEA.png)](http://www.jetbrains.com/idea/index.html)
