# locker


1. Простой кодовый замок
2. модуль логики, модуль вывода, модуль ввода.
3.Механика

3.1 сейф помнит пароль пока закрыт

4. При неправильном вводе пароля следующий ввод допускается через t=f(n),n= к-во неверных попыток ввода подряд 
5. Реализация :
5.1 модуль логики на базе ATMEGA328P

https://www.aliexpress.com/item/32973635527.html?spm=a2g0o.productlist.0.0.7b11451enDFufJ&algo_pvid=87a675d7-a477-4900-87ff-595f0187a72f&algo_expid=87a675d7-a477-4900-87ff-595f0187a72f-1&btsid=0b0a182b15997579032113882e8e4e&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_


Устройство ввода - энкодер с кнопкой
https://www.aliexpress.com/item/32873198060.html?spm=a2g0o.detail.1000014.12.510477c372MVRX&gps-id=pcDetailBottomMoreOtherSeller&scm=1007.14976.185483.0&scm_id=1007.14976.185483.0&scm-url=1007.14976.185483.0&pvid=9f25c2fc-4988-424e-bdd0-d4ac86002cac&_t=gps-id:pcDetailBottomMoreOtherSeller,scm-url:1007.14976.185483.0,pvid:9f25c2fc-4988-424e-bdd0-d4ac86002cac,tpp_buckets:668%230%23131923%2363_668%23808%233772%23435_668%23888%233325%2315_4976%230%23185483%230_4976%232711%237538%23231_4976%233104%239653%233_4976%233141%239887%231_668%232846%238110%23302_668%232717%237566%23886_668%231000022185%231000066058%230_668%233422%2315392%23817_4452%230%23184418%230_4452%233474%2316498%23543_4452%233098%239599%23413_4452%233564%2316062%23561

Устройство вывода - i2c oled ekran
https://www.aliexpress.com/item/32798439084.html?spm=a2g0o.productlist.0.0.3b5447c3yqdc2J&algo_pvid=860cc909-ad99-47cf-86a1-0f9543fe4a9e&algo_expid=860cc909-ad99-47cf-86a1-0f9543fe4a9e-3&btsid=0b8b034a15993363725637756eda0f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

Исполняющий механизм AT TINY13A + RGB LED
https://www.aliexpress.com/item/4000308024481.html?spm=a2g0o.productlist.0.0.4f11388an9K2BH&algo_pvid=63000d88-9282-48c2-9b09-25888cdf4dd8&algo_expid=63000d88-9282-48c2-9b09-25888cdf4dd8-5&btsid=0b0a182b15997560662908398e8f1c&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

+
https://www.aliexpress.com/item/32809489418.html?spm=a2g0o.productlist.0.0.532a6ebdWFh2ZW&algo_pvid=bdd2e66d-4373-4706-b9d6-4d355ef5b15c&algo_expid=bdd2e66d-4373-4706-b9d6-4d355ef5b15c-1&btsid=0b0a182b15997574252674237e8e54&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

Общение с исполняющим механизмом - SOFTWARE SERIAL

Cостояния 
 Открыт - горит зеленый светодиод 
 Открываюсь - мигает зеленый светодиод
 Закрыт - мигает синий светодиод
 Закрываюсь - мигает красный светодиод 
 Неверный пароль - горит красный 
 
Eagle Cad 
ATMEGA328P - https://www.diymodules.org/eagle-search?text=ATMEGA&desc=1

Encoder - https://www.snapeda.com/parts/PEC12R-4025F-S0024/Bourns/view-part/?ref=search&t=encoder

i2c oled - https://www.diymodules.org/eagle-show-object?type=dm&file=diy-modules.lbr&device=DISPLAY-OLED-128X32#variant-DISPLAY-OLED-128X32

AT TINY13A - https://www.diymodules.org/eagle-show-object?type=usr&id=2486&device=ATTINY13-20%2A


 
