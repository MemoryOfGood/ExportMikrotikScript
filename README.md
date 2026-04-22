# ExportMikrotikScript
>[!TIP]
> Сделанно на примере HQ-RTR, но также применяется для BR-RTR

>[!Warning]
> Обязательно добавьте и используйте третий адаптер "Только локальный"/"Host-only" для этого

Подготавлиеваем ВМ, чтобы обязательно был адаптер "Только локальный"/"Host-only"
<img width="377" height="407" alt="изображение" src="https://github.com/user-attachments/assets/d5101871-93a1-463b-860f-ac7f0a109886" />
**Рисунок 1**

Заходим в **Edit virtual machine settings** > **Network manager 3** > **Advanced** и запоминаем Mac-адрес
<img width="330" height="523" alt="изображение" src="https://github.com/user-attachments/assets/040a0f67-83fe-4fe0-b220-f004b89f4ba5" />
**Рисунок 2**

Подключаемся через Winbox
<img width="1920" height="1020" alt="изображение" src="https://github.com/user-attachments/assets/34920487-0112-4154-910b-f526e0d8cbe2" />
**Рисунок 3**

Копируем конфиг в файлы
<img width="1920" height="1020" alt="изображение" src="https://github.com/user-attachments/assets/5d642baf-42f4-4c29-86d0-660251cd6add" />
**Рисунок 4**

После чего в консоле прописываем команду
```
import file-name=config.rsc
```

<img width="505" height="72" alt="изображение" src="https://github.com/user-attachments/assets/5f6eb11b-15ad-4085-bdf8-0a2af6277a69" />
**Рисунок 5**

Конфигурация удачно импортирована
