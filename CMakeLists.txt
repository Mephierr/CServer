cmake_minimum_required(VERSION 3.10)

project(CServer)

# Укажите стандарт C++
set(CMAKE_CXX_STANDARD 11)


# Добавьте исполняемые файлы
add_executable(server server.c utils.h utils.c)

