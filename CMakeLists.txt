idf_component_register(SRCS "sqlite3.c" "esp32.cpp" "shox96_0_2.cpp"
                       INCLUDE_DIRS "include"
                       PRIV_INCLUDE_DIRS "private_include"
                       REQUIRES spi_flash)