set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(HelloWorld
    DESCRIPTION "A simple Hello World program"
    LANGUAGES CXX
)

add_executable(hello_world helloworld.cxx)