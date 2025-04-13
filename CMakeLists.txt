idf_component_register(
    SRCS "src/tinyxml2.cpp"
    INCLUDE_DIRS "include"
    # Optionally, add any necessary compile definitions:
    # COMPILE_DEFINITIONS $<$<CONFIG:Debug>:TINYXML2_DEBUG> _FILE_OFFSET_BITS=64
)
