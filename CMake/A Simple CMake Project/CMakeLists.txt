CMAKE_MINIMUM_REQUIRED(VERSION 2.8)      
 
PROJECT(server_project)                                          
 
MESSAGE(STATUS "Project: SERVER")               
MESSAGE(STATUS "Project Directory: ${PROJECT_SOURCE_DIR}")
 
SET(CMAKE_BUILE_TYPE RELEASE)               
 
 
SET(CMAKE_C_FLAGS_DEBUG "-g -Wall")          
ADD_SUBDIRECTORY(utility)                    
ADD_SUBDIRECTORY(server)
