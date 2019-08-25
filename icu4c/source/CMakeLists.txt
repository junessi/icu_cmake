add_subdirectory(common)
add_subdirectory(i18n)
add_subdirectory(stubdata)
include_directories("common" "i18n")
add_definitions(-DU_COMMON_IMPLEMENTATION) # required by common components
add_definitions(-DU_I18N_IMPLEMENTATION) # required by i18n components
add_definitions(-DU_STUBDATA_IMPLEMENTATION) # required by studata components
add_library(icu ${COMMON_SRC} ${I18N_SRC} ${STUBDATA_SRC})
