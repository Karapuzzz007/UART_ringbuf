# UART_ringbuf
### Используемая плата: stm32f303vc
### Используемое программное обеспечение

1. arm-none-eabi-g++ --- кросс-компилятор.
1. make --- система сборки проекта.
1. cmake --- система управления проектом.
1. git --- система контроля версий.

- Настройка проекта: 
    cmake -B build
- Сборка проекта:
    cmake --build build     
- Прошивка МК:
    cmake --install build 

- Интерфейс UART : 
    - Зеленый - RxD
    - Белый - TxD
