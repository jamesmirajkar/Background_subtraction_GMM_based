cmake_minimum_required(VERSION 3.10)

project(your_project_name)

# Find OpenCV
find_package(OpenCV REQUIRED)

# Add executable
add_executable(main main.cpp)

# Link against OpenCV
target_link_libraries(main PRIVATE ${OpenCV_LIBS})

