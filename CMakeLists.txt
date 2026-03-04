cmake_minimum_required(VERSION 3.10)  

# Define the project name  
project(ShootingGame)  

# Find SFML  
find_package(SFML 2.5 COMPONENTS graphics window system REQUIRED)  

# Add the executable  
add_executable(ShootingGame main.cpp)  

# Link the SFML libraries  
target_link_libraries(ShootingGame sfml-graphics sfml-window sfml-system)  
