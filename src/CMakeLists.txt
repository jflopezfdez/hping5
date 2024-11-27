# Generate the header file for the current project configuration.
configure_file(Configuration.h.in Configuration.h NO_SOURCE_PERMISSIONS @ONLY)

# TODO: jflopezfernandez - Add remaining project subdirectories.
add_subdirectory(hping5)

