# CMakeLists head

target_sources(vsfkernel INTERFACE
    __common.c
    dma.c
    flash.c
    io.c
    spi.c
    startup_gd32f3x0.c
    usart.c
)

add_subdirectory(usb)
