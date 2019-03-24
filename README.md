# marlin-tevo-flash

Marlin Configuration for Tevo Flash 3D printer. This configuration is tested on my stock printer, but i don't guarantee that it will work well for you.

After flashing firmware you will need to run auto PID configuration with commands: M303 S210 C10 E1 U1 - for hotend M303 S70 C10 E-1 U1 - for bed

--------------

Конфигурация Marlin под Tevo Flash. Несмотря на то, что этот конфиг был протестирован на моём стоковом принтере, я не гарантирую что он будет стабильно работать на вашем.

После прошивки обязательно надо будет откалибровать PID: M303 S210 C10 E1 U1 - для хотэнда M303 S70 C10 E-1 U1 - для стола
