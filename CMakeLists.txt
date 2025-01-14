
idf_component_register(SRCS "src/PNGdec.cpp" "src/s3_simd_rgb565.S"
                    INCLUDE_DIRS "src"
                    REQUIRES "arduino-esp32" "esp-dsp"
                    )