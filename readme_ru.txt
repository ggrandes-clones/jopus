﻿Java версия библиотек для работы с Opus
*****************************************************************************
Соответствие:

opus-1.3.0
opusfile-0.11
libopusenc-0.2.1
opus-tools-0.2
libogg-1.3.3
+ тесты
+ примеры
+ java spi интерфейс

*****************************************************************************
opus_demo и opus_compare перемещены в test.
*****************************************************************************
Использовалась java версии 1.6.

Для уменьшения объёма и ускорения работы рекомендуется обработать обфускатором.
При обработке обфускатором следует сохранить имена классов внутри пакета spi.
Оптимизацию обфускатора следует применять осторожно, это может снизить скорость работы
и увеличить нагрузку на процессор.
*****************************************************************************
#undef SMALL_FOOTPRINT
#undef NORM_ALIASING_HACK
#undef FUZZING
#undef RESYNTH
#undef CUSTOM_MODES
#undef FIXED_POINT
#undef DISABLE_FLOAT_API
Since v1.3:/* Disable bitstream fixes from RFC 8251 */

#undef DISABLE_UPDATE_DRAFT = Jopus_defines.DISABLE_UPDATE_DRAFT = false;
*****************************************************************************

Метки в исходных файлах:
FIXME - подозрительные места в исходном коде на Си.
XXX - метки, отмечающие отладочный код и комментарии.
TODO - java-код, возможно, требующий дополнительной проработки.

*****************************************************************************
Смотри также:
Opus, домашняя страница
http://opus-codec.org/
Сборки
http://downloads.xiph.org/releases/opus/
*****************************************************************************
email: dmilvdv@gmail.com
