zephyr_sources_configure(app) # Ensures app target is configured for sources

zephyr_sources_define(app PRIVATE
    ${CMAKE_CURRENT_LIST_DIR}/mothbw.h
    ${CMAKE_CURRENT_LIST_DIR}/spbw.h
)
