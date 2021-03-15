cmake_minimum_required(VERSION 3.17)
project(C___2)

set(CMAKE_CXX_STANDARD 14)

add_executable(c++-1 cmake-build-debug/2020.12.0/c++-1.cpp )
add_executable(c++-2 cmake-build-debug/2020.12.0/c++-2.cpp)
add_executable(c++-3 cmake-build-debug/2020.12.0/c++-3.cpp)

add_executable(angle cmake-build-debug/2021.1.14/angle.cpp)
add_executable(windows1 cmake-build-debug/windows/windows1.cpp)
add_executable(text1 cmake-build-debug/2021.3.8/text1.cpp)
add_executable(text2 cmake-build-debug/2021.3.8/text2.cpp)
add_executable(Employee cmake-build-debug/3.16/Employee/Employee.cpp)

add_executable(main1 cmake-build-debug/3.16/Employee/main1.cpp)
add_executable(main2 cmake-build-debug/3.16/3.2/main2.cpp)
add_executable(student cmake-build-debug/3.16/3.2/student.cpp)
add_executable(Date cmake-build-debug/3.16/Date/Date.cpp)