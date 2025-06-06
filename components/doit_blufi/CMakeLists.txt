
list(APPEND srcs
        doit_blufi.c
        blufi_init.c
        )

list(APPEND incs
        .
        )

        

idf_component_register(SRCS "${srcs}"
                            INCLUDE_DIRS "${incs}"
                            EMBED_TXTFILES "${assets}"
                            REQUIRES driver esp_wifi bt nvs_flash json esp_timer)



