cmake_minimum_required(VERSION 3.3)

add_library(imgui STATIC 
    imgui.cpp
    imgui_demo.cpp
    imgui_draw.cpp
    backends/imgui_impl_glfw.cpp
    backends/imgui_impl_opengl3.cpp
    misc/cpp/imgui_stdlib.cpp
    imgui_tables.cpp
    imgui_widgets.cpp
)


target_include_directories(imgui PUBLIC
${CMAKE_CURRENT_SOURCE_DIR}
)
