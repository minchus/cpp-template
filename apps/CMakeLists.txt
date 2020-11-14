add_executable(main main.cpp ../include/ExampleClass.h)
target_link_libraries(main ${CONAN_LIBS})

target_include_directories(main PUBLIC ../include)
