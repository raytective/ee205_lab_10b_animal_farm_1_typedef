cmake_minimum_required(VERSION 3.22)
project(ee205_lab_10b_animal_farm_1_typedef)

set(CMAKE_CXX_STANDARD 14)

add_executable(ee205_lab_10b_animal_farm_1_typedef main.cpp addCats.cpp addCats.h config.h catDatabase.cpp catDatabase.h deleteCats.cpp deleteCats.h reportCats.cpp reportCats.h updateCats.cpp updateCats.h convertCats.cpp convertCats.h)
