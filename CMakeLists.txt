idf_component_register(SRCS "sqlite3.c" "esp32.c"
                       INCLUDE_DIRS "include"
                       PRIV_INCLUDE_DIRS "private_include"
                       REQUIRES spi_flash)