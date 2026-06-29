if(MSVC)
    add_compile_options(/Zc:__cplusplus /permissive- /FS)
endif()
target_sources(${PROJECT_NAME} PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/codeeditortab.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/codeeditortab.h
)
