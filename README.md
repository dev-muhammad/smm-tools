# SMM tools
Usifull SMM tools for authors

Example:
```
from smmtools import Instgaram

import PIL


text = """Почему данные новая нефть?
Данные, данные, данные окружают нас сегодня везде. Под данными подразумеваю информацию хранимый в цифровом виде и подлежащее обработке. 
Почему в друг ценность данных выросла? 
В принципе данные были всегда начиная когда появился речь и письменность, когда человечество начал хранить и передавать знания на бумаге. 
Данные вдруг начали приобретать ценность, когда люди нашли им применение (как это было с нефтью). И это было всего пол века назад, когда появились вычислительные мощности достаточные для выживания пользы от данных. 
В чём ценность данных?
Да, все говорят что историческая информация полезна тем, что передаёт знания предков чтобы не допустить ошибка прошлого в будущем и т.п. и т.д. 
Истинная ценность данных заключается в том что они помогают предсказать будущее. 
 """


res = Instgaram.text2carusel(text)

res[0].show()
```