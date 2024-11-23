# Defines a variable for the executable name
set(EXECUTABLE_NAME cloud-storage)

add_executable(${EXECUTABLE_NAME}
    cloud-storage.cpp
)

# Include the directories where the .h files are located (headers)
target_include_directories(${EXECUTABLE_NAME} PUBLIC "${PROJECT_SOURCE_DIR}")
