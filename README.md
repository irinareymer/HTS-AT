# Исследование работы HTS-AT на данных UrbanSound8K. 

Для выполнения работы использовался исходный код 
[HTS-Audio-Transformer](https://github.com/RetroCirce/HTS-Audio-Transformer).

## Технические требования

Необходимые зависимости представлены в ```requirements.txt```.

Дополнительно нужно установить ```PyTorch``` и ```CUDA Toolkit``` для поддержки GPU вычислений.
Также для работы потребуются утилиты ```SOX``` и ```FFmpeg```. 
Установите необходимые компоненты в соответствии с вашей конфигурацией.

Необходимо настроить параметры в ```config.py``` в соответствии с используемым набором данных и его расположением.


## UrbanSound8K
Исследование структуры датасета UrbanSound8K представлено в ```UrbanSound8k.ipynb```.

Для обучения модели  воспользуйтесь ```htsat_urbansound8k.ipynb```.

Для тестирования модели запустите в ```main.py``` команду ```CUDA_VISIBLE_DEVICES=0 python main.py test```.
