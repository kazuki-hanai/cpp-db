# find_package
include_directories(
        ${PROJECT_SOURCE_DIR}/include
)
add_executable(dbtest test.cc)
target_link_libraries (dbtest db)
add_test (NAME DBTest COMMAND ${PROJECT_SOURCE_DIR}/test/dbtest)
