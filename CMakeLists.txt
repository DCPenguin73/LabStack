cmake_minimum_required(VERSION 3.10) # Adjust if needed

project(LabStack)

# Set include directories
include_directories(
    . 
)

# Source files
set(SOURCE_FILES
    testStack.cpp
)

# Add executable
add_executable(LabStack ${SOURCE_FILES})

# Target-specific options (optional)
target_compile_options(LabStack PRIVATE
    # Add compiler flags here if needed
    # e.g., -std=c++17 
)

# Find and link libraries (if any)
# find_package(Boost COMPONENTS system REQUIRED)
# target_link_libraries(LabStack ${Boost_LIBRARIES})
