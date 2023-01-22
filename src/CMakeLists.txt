add_library(${LIB_NAME} cJSON.c)
target_include_directories(${LIB_NAME} PUBLIC "${PROJECT_SOURCE_DIR}/include")
