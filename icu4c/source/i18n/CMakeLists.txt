add_definitions(-DU_I18N_IMPLEMENTATION) # required by i18n components
file(GLOB SRC_FILES *.c *.cpp)
set(I18N_SRC ${SRC_FILES} PARENT_SCOPE)

