    Wed Nov 22 09:33:05 AM EST 2023

    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 
    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 

    Spring Initializr
    https://start.spring.io/

    Group:         ashburncode
    Artifact:      sbapp2717m
    Name:          sbapp2717mvnjarj17
    Package name:  ashburncode.sbapp2717m
    Description:   spring boot 2.7.17, maven project, jar packaging, java 17
    Dependencies:
      Spring Web Web
        Build web, including RESTful, applications using Spring MVC. Uses Apache Tomcat as the default embedded container.
      Spring Data JPA SQL
        Persist data in SQL stores with Java Persistence API using Spring Data and Hibernate.
      Rest Repositories Web
        Exposing Spring Data repositories over REST via Spring Data REST.
      MySQL Driver SQL
        MySQL JDBC driver.    

    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 
    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 

    -rw-rw-r-- 1 davidho davidho 70937 Nov 17 08:18 sbapp2717g.zip
    -rw-rw-r-- 1 davidho davidho 67641 Nov 17 08:19 sbapp2717m.zip
    -rw-rw-r-- 1 davidho davidho 70927 Nov 17 08:20 sbapp3012g.zip
    -rw-rw-r-- 1 davidho davidho 67642 Nov 17 08:22 sbapp3012m.zip
    -rw-rw-r-- 1 davidho davidho 70861 Nov 17 08:23 sbapp315g.zip
    -rw-rw-r-- 1 davidho davidho 70270 Nov 17 08:24 sbapp315m.zip

    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 
    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 

    cp -p ~/Downloads/sbapp2717g.zip ~/sbootprojs
    cd ~/sbootprojs
    java -version
    7z l sbapp2717g.zip
    7z x sbapp2717g.zip
    cd ~/sbootprojs/sbapp2717g
    java -version
    grep version build.gradle
    ls -latr
    tree
    ./gradlew --version
    ./gradlew dependencies > sbapp2717g.dependencies.txt
    ./gradlew tasks > sbapp2717g.tasks.txt
    git init
    ./gradlew bootJar
    find . -name *.jar -print
    find . -name *.jar -print -exec ls -la {} \;
    find . -name *.jar -print -exec jar tvf {} \;


    davidho@dphxps17:~/sbootprojs$ 
    davidho@dphxps17:~/sbootprojs$ date
    Wed Nov 22 10:19:53 AM EST 2023
    davidho@dphxps17:~/sbootprojs$ 
    davidho@dphxps17:~/sbootprojs$ 
    cp -p ~/Downloads/sbapp2717g.zip ~/sbootprojs
    cd ~/sbootprojs
    java -version
    7z l sbapp2717g.zip
    7z x sbapp2717g.zip
    cd ~/sbootprojs/sbapp2717g
    java -version
    grep version build.gradle
    ls -latr
    tree
    ./gradlew --version
    ./gradlew dependencies > sbapp2717g.dependencies.txt
    ./gradlew tasks > sbapp2717g.tasks.txt
    git init
    ./gradlew bootJar
    find . -name *.jar -print
    find . -name *.jar -print -exec ls -la {} \;
    find . -name *.jar -print -exec jar tvf {} \;
    openjdk version "17.0.8.1" 2023-08-24 LTS
    OpenJDK Runtime Environment Zulu17.44+53-CA (build 17.0.8.1+1-LTS)
    OpenJDK 64-Bit Server VM Zulu17.44+53-CA (build 17.0.8.1+1-LTS, mixed mode, sharing)

    7-Zip [64] 16.02 : Copyright (c) 1999-2016 Igor Pavlov : 2016-05-21
    p7zip Version 16.02 (locale=en_US.UTF-8,Utf16=on,HugeFiles=on,64 bits,16 CPUs 11th Gen Intel(R) Core(TM) i7-11800H @ 2.30GHz (806D1),ASM,AES-NI)

    Scanning the drive for archives:
    1 file, 70937 bytes (70 KiB)

    Listing archive: sbapp2717g.zip

    --
    Path = sbapp2717g.zip
    Type = zip
    Physical Size = 70937

      Date      Time    Attr         Size   Compressed  Name
    ------------------- ----- ------------ ------------  ------------------------
    2023-11-17 08:18:44 D....            0            2  sbapp2717g
    2023-11-17 08:18:44 .....         1724          607  sbapp2717g/HELP.md
    2023-11-17 08:18:44 .....         2868         1211  sbapp2717g/gradlew.bat
    2023-11-17 08:18:44 .....          444          242  sbapp2717g/.gitignore
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/java
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/java/ashburncode
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/java/ashburncode/sbapp2717g
    2023-11-17 08:18:44 .....          339          180  sbapp2717g/src/main/java/ashburncode/sbapp2717g/Sbapp2717grajarj17Application.java
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/resources
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/resources/templates
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/main/resources/static
    2023-11-17 08:18:44 .....            1            3  sbapp2717g/src/main/resources/application.properties
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/test
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/test/java
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/test/java/ashburncode
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/src/test/java/ashburncode/sbapp2717g
    2023-11-17 08:18:44 .....          226          161  sbapp2717g/src/test/java/ashburncode/sbapp2717g/Sbapp2717grajarj17ApplicationTests.java
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/gradle
    2023-11-17 08:18:44 D....            0            2  sbapp2717g/gradle/wrapper
    2023-11-17 08:18:44 .....          250          152  sbapp2717g/gradle/wrapper/gradle-wrapper.properties
    2023-11-17 08:18:44 .....        63721        57558  sbapp2717g/gradle/wrapper/gradle-wrapper.jar
    2023-11-17 08:18:44 .....           32           34  sbapp2717g/settings.gradle
    2023-11-17 08:18:44 .....          737          347  sbapp2717g/build.gradle
    2023-11-17 08:18:44 .....         8692         3688  sbapp2717g/gradlew
    ------------------- ----- ------------ ------------  ------------------------
    2023-11-17 08:18:44              79034        64213  11 files, 15 folders

    7-Zip [64] 16.02 : Copyright (c) 1999-2016 Igor Pavlov : 2016-05-21
    p7zip Version 16.02 (locale=en_US.UTF-8,Utf16=on,HugeFiles=on,64 bits,16 CPUs 11th Gen Intel(R) Core(TM) i7-11800H @ 2.30GHz (806D1),ASM,AES-NI)

    Scanning the drive for archives:
    1 file, 70937 bytes (70 KiB)

    Extracting archive: sbapp2717g.zip
    --
    Path = sbapp2717g.zip
    Type = zip
    Physical Size = 70937

    Everything is Ok

    Folders: 15
    Files: 11
    Size:       79034
    Compressed: 70937
    openjdk version "17.0.8.1" 2023-08-24 LTS
    OpenJDK Runtime Environment Zulu17.44+53-CA (build 17.0.8.1+1-LTS)
    OpenJDK 64-Bit Server VM Zulu17.44+53-CA (build 17.0.8.1+1-LTS, mixed mode, sharing)
      id 'org.springframework.boot' version '2.7.17'
      id 'io.spring.dependency-management' version '1.0.15.RELEASE'
    version = '0.0.1-SNAPSHOT'
    total 48
    drwxr-xr-x  4 davidho davidho 4096 Nov 17 08:18 src
    -rw-r--r--  1 davidho davidho   32 Nov 17 08:18 settings.gradle
    -rw-r--r--  1 davidho davidho 1724 Nov 17 08:18 HELP.md
    -rw-r--r--  1 davidho davidho 2868 Nov 17 08:18 gradlew.bat
    -rwxr-xr-x  1 davidho davidho 8692 Nov 17 08:18 gradlew
    drwxr-xr-x  3 davidho davidho 4096 Nov 17 08:18 gradle
    -rw-r--r--  1 davidho davidho  444 Nov 17 08:18 .gitignore
    -rw-r--r--  1 davidho davidho  737 Nov 17 08:18 build.gradle
    drwxr-xr-x  4 davidho davidho 4096 Nov 17 08:18 .
    drwxrwxr-x 29 davidho davidho 4096 Nov 22 10:20 ..
    .
    ├── build.gradle
    ├── gradle
    │   └── wrapper
    │       ├── gradle-wrapper.jar
    │       └── gradle-wrapper.properties
    ├── gradlew
    ├── gradlew.bat
    ├── HELP.md
    ├── settings.gradle
    └── src
        ├── main
        │   ├── java
        │   │   └── ashburncode
        │   │       └── sbapp2717g
        │   │           └── Sbapp2717grajarj17Application.java
        │   └── resources
        │       ├── application.properties
        │       ├── static
        │       └── templates
        └── test
            └── java
                └── ashburncode
                    └── sbapp2717g
                        └── Sbapp2717grajarj17ApplicationTests.java

    14 directories, 10 files

    ------------------------------------------------------------
    Gradle 8.4
    ------------------------------------------------------------

    Build time:   2023-10-04 20:52:13 UTC
    Revision:     e9251e572c9bd1d01e503a0dfdf43aedaeecdc3f

    Kotlin:       1.9.10
    Groovy:       3.0.17
    Ant:          Apache Ant(TM) version 1.10.13 compiled on January 4 2023
    JVM:          17.0.8.1 (Azul Systems, Inc. 17.0.8.1+1-LTS)
    OS:           Linux 6.2.0-36-generic amd64

    hint: Using 'master' as the name for the initial branch. This default branch name
    hint: is subject to change. To configure the initial branch name to use in all
    hint: of your new repositories, which will suppress this warning, call:
    hint: 
    hint: 	git config --global init.defaultBranch <name>
    hint: 
    hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
    hint: 'development'. The just-created branch can be renamed via this command:
    hint: 
    hint: 	git branch -m <name>
    Initialized empty Git repository in /home/davidho/sbootprojs/sbapp2717g/.git/

    BUILD SUCCESSFUL in 746ms
    4 actionable tasks: 4 executed
    ./gradle/wrapper/gradle-wrapper.jar
    ./build/libs/sbapp2717g-0.0.1-SNAPSHOT.jar
    ./gradle/wrapper/gradle-wrapper.jar
    -rw-r--r-- 1 davidho davidho 63721 Nov 17 08:18 ./gradle/wrapper/gradle-wrapper.jar
    ./build/libs/sbapp2717g-0.0.1-SNAPSHOT.jar
    -rw-rw-r-- 1 davidho davidho 40761580 Nov 22 10:20 ./build/libs/sbapp2717g-0.0.1-SNAPSHOT.jar
    ./gradle/wrapper/gradle-wrapper.jar
        0 Fri Feb 01 00:00:00 EST 1980 META-INF/
        63 Fri Feb 01 00:00:00 EST 1980 META-INF/MANIFEST.MF
        0 Fri Feb 01 00:00:00 EST 1980 org/
        0 Fri Feb 01 00:00:00 EST 1980 org/gradle/
        0 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/
      5982 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/GradleWrapperMain.class
        51 Fri Feb 01 00:00:00 EST 1980 gradle-wrapper-classpath.properties
        0 Fri Feb 01 00:00:00 EST 1980 gradle-wrapper-parameter-names.properties
        0 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/
      1363 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/AbstractCommandLineConverter.class
      2796 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/AbstractPropertiesCommandLineConverter.class
      587 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineArgumentException.class
      615 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineConverter.class
      3687 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineOption.class
      229 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$1.class
      2495 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$AfterFirstSubCommand.class
      1830 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$AfterOptions.class
      2933 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$BeforeFirstSubCommand.class
      1263 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$CaseInsensitiveStringComparator.class
      4472 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$KnownOptionParserState.class
      1780 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$MissingOptionArgState.class
      1732 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$OptionAwareParserState.class
      2121 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$OptionComparator.class
      931 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$OptionParserState.class
      1462 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$OptionString.class
      1400 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$OptionStringComparator.class
      1208 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$ParserState.class
      1899 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser$UnknownOptionParserState.class
    10794 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/CommandLineParser.class
      4608 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/ParsedCommandLine.class
      1349 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/ParsedCommandLineOption.class
      779 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/ProjectPropertiesCommandLineConverter.class
      764 Fri Feb 01 00:00:00 EST 1980 org/gradle/cli/SystemPropertiesCommandLineConverter.class
        0 Fri Feb 01 00:00:00 EST 1980 org/gradle/util/
        0 Fri Feb 01 00:00:00 EST 1980 org/gradle/util/internal/
      1673 Fri Feb 01 00:00:00 EST 1980 org/gradle/util/internal/PathTraversalChecker.class
      1049 Fri Feb 01 00:00:00 EST 1980 org/gradle/util/internal/WrapperDistributionUrlConverter.class
      793 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/BootstrapMainStarter$1.class
      2572 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/BootstrapMainStarter.class
      210 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Download$1.class
      2008 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Download$DefaultDownloadProgressListener.class
      1918 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Download$ProxyAuthenticator.class
    11316 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Download.class
      202 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/DownloadProgressListener.class
      3204 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/ExclusiveFileAccessManager.class
      1158 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/GradleUserHomeLookup.class
      219 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/IDownload.class
      2988 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Install$1.class
      1559 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Install$InstallCheck.class
    13902 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Install.class
      1332 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/Logger.class
      751 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/PathAssembler$LocalDistribution.class
      3648 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/PathAssembler.class
      2428 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/SystemPropertiesHandler.class
      2393 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/WrapperConfiguration.class
      5769 Fri Feb 01 00:00:00 EST 1980 org/gradle/wrapper/WrapperExecutor.class
    ./build/libs/sbapp2717g-0.0.1-SNAPSHOT.jar
        0 Wed Nov 22 15:20:18 EST 2023 META-INF/
      350 Wed Nov 22 15:20:18 EST 2023 META-INF/MANIFEST.MF
        0 Fri Feb 01 00:00:00 EST 1980 org/
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/
      5871 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/ClassPathIndexFile.class
      7675 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/ExecutableArchiveLauncher.class
      2551 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/JarLauncher.class
      1483 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/LaunchedURLClassLoader$DefinePackageCallType.class
      1535 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/LaunchedURLClassLoader$UseFastConnectionExceptionsEnumeration.class
    11154 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/LaunchedURLClassLoader.class
      5932 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/Launcher.class
      1536 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/MainMethodRunner.class
      266 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/PropertiesLauncher$1.class
      1484 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/PropertiesLauncher$ArchiveEntryFilter.class
      8128 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/PropertiesLauncher$ClassPathArchives.class
      1953 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/PropertiesLauncher$PrefixMatchingArchiveFilter.class
    18267 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/PropertiesLauncher.class
      1728 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/WarLauncher.class
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/
      302 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/Archive$Entry.class
      511 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/Archive$EntryFilter.class
      4745 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/Archive.class
      6093 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive$AbstractIterator.class
      2180 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive$ArchiveIterator.class
      1857 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive$EntryIterator.class
      1269 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive$FileEntry.class
      2527 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive$SimpleJarFileArchive.class
      5346 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/ExplodedArchive.class
      2884 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/JarFileArchive$AbstractIterator.class
      1981 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/JarFileArchive$EntryIterator.class
      1081 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/JarFileArchive$JarFileEntry.class
      2528 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/JarFileArchive$NestedArchiveIterator.class
    10349 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/archive/JarFileArchive.class
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/
      485 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/RandomAccessData.class
      282 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/RandomAccessDataFile$1.class
      2772 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/RandomAccessDataFile$DataInputStream.class
      3259 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/RandomAccessDataFile$FileAccess.class
      4015 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/data/RandomAccessDataFile.class
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/
      1438 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/AbstractJarFile$JarFileType.class
      878 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/AbstractJarFile.class
      4976 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/AsciiBytes.class
      616 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/Bytes.class
      295 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryEndRecord$1.class
      3319 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryEndRecord$Zip64End.class
      2029 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryEndRecord$Zip64Locator.class
      5029 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryEndRecord.class
      6897 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryFileHeader.class
      4624 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryParser.class
      540 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/CentralDirectoryVisitor.class
      345 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/FileHeader.class
    13641 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/Handler.class
      3885 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarEntry.class
      1458 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarEntryCertification.class
      299 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarEntryFilter.class
      2299 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFile$1.class
      1299 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFile$JarEntryEnumeration.class
    16660 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFile.class
      1368 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries$1.class
      2258 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries$EntryIterator.class
      1281 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries$Offsets.class
      1338 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries$Zip64Offsets.class
      1334 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries$ZipOffsets.class
    17280 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileEntries.class
      3512 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarFileWrapper.class
      702 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarURLConnection$1.class
      4302 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarURLConnection$JarEntryName.class
      9399 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/JarURLConnection.class
      3559 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/StringSequence.class
      1813 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jar/ZipInflaterInputStream.class
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jarmode/
      293 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jarmode/JarMode.class
      2201 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jarmode/JarModeLauncher.class
      1292 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/jarmode/TestJarMode.class
        0 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/util/
      5174 Fri Feb 01 00:00:00 EST 1980 org/springframework/boot/loader/util/SystemPropertyUtils.class
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/ashburncode/
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/ashburncode/sbapp2717g/
      787 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/ashburncode/sbapp2717g/Sbapp2717grajarj17Application.class
        1 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/application.properties
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/lib/
    2481560 Wed Aug 16 12:36:20 EDT 2023 BOOT-INF/lib/mysql-connector-j-8.0.33.jar
    15392 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jakarta.transaction-api-1.3.3.jar
    164392 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jakarta.persistence-api-2.2.3.jar
    7503554 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/hibernate-core-5.6.15.Final.jar
    389909 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-data-jpa-2.7.17.jar
    47235 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-aspects-5.3.30.jar
    371189 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-data-rest-webmvc-3.7.17.jar
    1029877 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-webmvc-5.3.30.jar
    146499 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-data-rest-core-3.7.17.jar
    594957 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/spring-hateoas-1.5.5.jar
    1642659 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-web-5.3.30.jar
    1690219 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-boot-autoconfigure-2.7.17.jar
    1466649 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-boot-2.7.17.jar
    28823 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/spring-plugin-core-2.0.0.RELEASE.jar
    1275641 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-context-5.3.30.jar
    384533 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-aop-5.3.30.jar
    2087074 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/aspectjweaver-1.9.7.jar
    159222 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/HikariCP-4.0.3.jar
    204553 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-orm-5.3.30.jar
    428651 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-jdbc-5.3.30.jar
    78948 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/hibernate-commons-annotations-5.1.2.Final.jar
    60782 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jboss-logging-3.4.3.Final.jar
    3948911 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/byte-buddy-1.12.23.jar
    445288 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/antlr-2.7.7.jar
    230776 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jandex-2.4.2.Final.jar
    67815 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/classmate-1.5.1.jar
    1019438 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jaxb-runtime-2.3.8.jar
    1348943 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/spring-data-commons-2.7.17.jar
    333487 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-tx-5.3.30.jar
    706239 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-beans-5.3.30.jar
    293172 Sun Oct 15 15:39:36 EDT 2023 BOOT-INF/lib/spring-expression-5.3.30.jar
    1489327 Sun Oct 15 15:39:32 EDT 2023 BOOT-INF/lib/spring-core-5.3.30.jar
    231811 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/logback-classic-1.2.12.jar
    18010 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/log4j-to-slf4j-2.17.2.jar
      4519 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jul-to-slf4j-1.7.36.jar
    271159 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/json-path-2.7.0.jar
    41125 Wed Mar 15 11:07:52 EDT 2023 BOOT-INF/lib/slf4j-api-1.7.36.jar
    121206 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jackson-datatype-jsr310-2.13.5.jar
    75718 Wed Aug 16 12:36:12 EDT 2023 BOOT-INF/lib/jackson-annotations-2.13.5.jar
      9513 Wed Aug 16 12:36:12 EDT 2023 BOOT-INF/lib/jackson-module-parameter-names-2.13.5.jar
    375186 Wed Aug 16 12:36:12 EDT 2023 BOOT-INF/lib/jackson-core-2.13.5.jar
    34800 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jackson-datatype-jdk8-2.13.5.jar
    1537543 Wed Aug 16 12:36:12 EDT 2023 BOOT-INF/lib/jackson-databind-2.13.5.jar
    25058 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jakarta.annotation-api-1.3.5.jar
    331605 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/snakeyaml-1.30.jar
    279973 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/tomcat-embed-websocket-9.0.82.jar
    3499047 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/tomcat-embed-core-9.0.82.jar
    256207 Fri Nov 17 14:53:10 EST 2023 BOOT-INF/lib/tomcat-embed-el-9.0.82.jar
    115638 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/jakarta.xml.bind-api-2.3.3.jar
    72007 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/txw2-2.3.8.jar
    29807 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/istack-commons-runtime-3.0.12.jar
    68453 Wed Aug 16 12:36:20 EDT 2023 BOOT-INF/lib/jakarta.activation-1.2.2.jar
    25081 Sun Oct 15 15:39:32 EDT 2023 BOOT-INF/lib/spring-jcl-5.3.30.jar
    11986 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/evo-inflector-1.3.jar
    448860 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/logback-core-1.2.12.jar
    302511 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/log4j-api-2.17.2.jar
    120205 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/json-smart-2.4.11.jar
    29904 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/accessors-smart-2.4.11.jar
    122176 Wed Aug 16 12:36:16 EDT 2023 BOOT-INF/lib/asm-9.3.jar
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/static/
        0 Wed Nov 22 15:20:18 EST 2023 BOOT-INF/classes/templates/
    29514 Wed Nov 22 10:20:18 EST 2023 BOOT-INF/lib/spring-boot-jarmode-layertools-2.7.17.jar
      2579 Wed Nov 22 10:20:18 EST 2023 BOOT-INF/classpath.idx
      212 Wed Nov 22 10:20:18 EST 2023 BOOT-INF/layers.idx
    davidho@dphxps17:~/sbootprojs/sbapp2717g$ 
    davidho@dphxps17:~/sbootprojs/sbapp2717g$ ./gradlew bootRun

    > Task :bootRun FAILED

      .   ____          _            __ _ _
    /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
    ( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
    \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
      '  |____| .__|_| |_|_| |_\__, | / / / /
    =========|_|==============|___/=/_/_/_/
    :: Spring Boot ::               (v2.7.17)

    2023-11-22 10:20:54.219  INFO 118954 --- [           main] a.s.Sbapp2717grajarj17Application        : Starting Sbapp2717grajarj17Application using Java 17.0.8.1 on dphxps17 with PID 118954 (/home/davidho/sbootprojs/sbapp2717g/build/classes/java/main started by davidho in /home/davidho/sbootprojs/sbapp2717g)
    2023-11-22 10:20:54.220  INFO 118954 --- [           main] a.s.Sbapp2717grajarj17Application        : No active profile set, falling back to 1 default profile: "default"
    2023-11-22 10:20:54.454  INFO 118954 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
    2023-11-22 10:20:54.460  INFO 118954 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 2 ms. Found 0 JPA repository interfaces.
    2023-11-22 10:20:54.704  INFO 118954 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
    2023-11-22 10:20:54.709  INFO 118954 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
    2023-11-22 10:20:54.709  INFO 118954 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.82]
    2023-11-22 10:20:54.752  INFO 118954 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
    2023-11-22 10:20:54.752  INFO 118954 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 510 ms
    2023-11-22 10:20:54.786  WARN 118954 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'dataSourceScriptDatabaseInitializer' defined in class path resource [org/springframework/boot/autoconfigure/sql/init/DataSourceInitializationConfiguration.class]: Unsatisfied dependency expressed through method 'dataSourceScriptDatabaseInitializer' parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in class path resource [org/springframework/boot/autoconfigure/jdbc/DataSourceConfiguration$Hikari.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is org.springframework.boot.autoconfigure.jdbc.DataSourceProperties$DataSourceBeanCreationException: Failed to determine a suitable driver class
    2023-11-22 10:20:54.787  INFO 118954 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
    2023-11-22 10:20:54.795  INFO 118954 --- [           main] ConditionEvaluationReportLoggingListener : 

    Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
    2023-11-22 10:20:54.801 ERROR 118954 --- [           main] o.s.b.d.LoggingFailureAnalysisReporter   : 

    ***************************
    APPLICATION FAILED TO START
    ***************************

    Description:

    Failed to configure a DataSource: 'url' attribute is not specified and no embedded datasource could be configured.

    Reason: Failed to determine a suitable driver class


    Action:

    Consider the following:
            If you want an embedded database (H2, HSQL or Derby), please put it on the classpath.
            If you have database settings to be loaded from a particular profile you may need to activate it (no profiles are currently active).


    FAILURE: Build failed with an exception.

    * What went wrong:
    Execution failed for task ':bootRun'.
    > Process 'command '/home/davidho/.sdkman/candidates/java/17.0.8.1-zulu/bin/java'' finished with non-zero exit value 1

    * Try:
    > Run with --stacktrace option to get the stack trace.
    > Run with --info or --debug option to get more log output.
    > Run with --scan to get full insights.
    > Get more help at https://help.gradle.org.

    BUILD FAILED in 1s
    4 actionable tasks: 2 executed, 2 up-to-date
    davidho@dphxps17:~/sbootprojs/sbapp2717g$ 

    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 
    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 

    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/ashburncode_rsa

    git remote add origin git@github.com:ashburncode/sbapp2717g.git
    git branch -M main
    git push -u origin main

    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 
    = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = 


