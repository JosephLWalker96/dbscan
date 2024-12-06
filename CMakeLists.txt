# libs/dbscan/CMakeLists.txt

# Create a static library for dbscan
add_library(dbscan STATIC dbscan.cpp)

# Include directories for the dbscan library
target_include_directories(dbscan PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
    ${CMAKE_CURRENT_SOURCE_DIR}/vendor   # Add this line
)