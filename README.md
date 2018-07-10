# C
nodepad++添加vs编译环境命令

cmd /k call "C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise\VC\Auxiliary\Build\vcvarsall.bat" x86 & chdir /d "$(CURRENT_DIRECTORY)" & cl $(FILE_NAME) & del  "$(NAME_PART).obj" & echo Running: & "$(NAME_PART).exe" & PAUSE & EXIT 
