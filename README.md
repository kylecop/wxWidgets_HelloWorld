# wxWidgets_HelloWorld


1. download wxWidgets 3.1.2 zip file
2. extract it to c:\sdks\wx312\
3. in visual studion 2019, open the project "C:\sdks\wx312\build\msw\wx_vc15.sln"
4. repeat step 3 if there are any errors
5. compile the project
6. close visual studio
7. clone this github
8. compile as x86 and run


# alternative steps for configuring a new project


7. create new project in visual studio "c++ desktop application"
8. go to project properties
9. c/c++, set additional include directories = $(wxwin)\include;$(wxwin)\include\msvc
10. c/c++ -> precompiled headers -> set precompiled header = Not Using Precompiled Headers
11. Linker -> additionallibrary directories = $(wxwin)\lib\vc_lib
12. delete all files from the project under the header, source, and resource folders
13. copy cMain and cApp from this repository to your source and header folders
14. compile the project as x86 and run
