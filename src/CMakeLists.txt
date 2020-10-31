include_directories(
        ${PROJECT_SOURCE_DIR}/include
)
add_library (db db.cc)
add_executable (main main.cc)
target_link_libraries (main db)

