# Установка необходимого ПО

В этом руководстве описаны шаги по установке следующих компонентов:

- [Microsoft Edge](#microsoft-edge)  
- [Telegram (Tg)](#telegram)  
- [VPN (Amnezia)](#vpn)  
- [CUDA Toolkit](#cuda-toolkit)  
- [Anaconda (Conda)](#anaconda-conda)  
- [PyTorch](#pytorch)  

---

## Microsoft Edge

1. Перейдите на официальный сайт:
   [https://www.microsoft.com/ru-ru/edge/?form=MA13FJ](https://www.microsoft.com/ru-ru/edge/?form=MA13FJ)  
2. Скачайте установочный файл для вашей системы.  
3. Дважды щёлкните по скачанному файлу и следуйте инструкциям установщика через App Store.

---

## Telegram (Tg)

1. Откройте App Store (или Google Play).  
2. Найдите приложение **Telegram**.  
3. Нажмите **Установить**.

---

## VPN (Amnezia)

1. Перейдите на официальный сайт:
   [https://amnezia.org/en/downloads/](https://amnezia.org/en/downloads/)  
2. Скачайте версию для вашей операционной системы.  
3. Установите VPN-клиент.  
4. Конфигурационные файлы в тг

---

## CUDA Toolkit

1. Перейдите на сайт NVIDIA:
   [CUDA Downloads for Linux (Ubuntu 24.04, x86_64, deb_local)](https://developer.nvidia.com/cuda-downloads?target_os=Linux&target_arch=x86_64&Distribution=Ubuntu&target_version=24.04&target_type=deb_local)  
2. Выберите нужную версию и следуйте официальным инструкциям по установке.

---

## Anaconda (Conda)

1. Скачайте установщик с официального сайта:
   [https://www.anaconda.com/download/success](https://www.anaconda.com/download/success)  
2. Откройте терминал и выполните:
   ```bash
   bash <путь_к_скачанному_файлу>.sh```
3. На этапе You can undo this by running conda init --reverse $SHELL? [yes|no] - yes
4. ```bash 
    conda create -n ENVNAME python=3.12
    conda activate ENVNAME 
    pip install ipykernel
    pip install numpy pandas matplotlib
5.  pytorch: 
    [https://pytorch.org/get-started/locally/](https://pytorch.org/get-started/locally/) следуй инструкции на сайте 