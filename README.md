# Домашнее задание 2 по курсу CV в MADE
Щербаков Игорь

## Поиск номера на фото
Для обнаружения номера на фото использовалась Mask RCNN из pytorch. 
Пробовал менять в ней backbone
Использовал различные трансформации для данных: ColorJitter, RandomGrayscale

## Чтение номера
Для распознавания номера в пределах найденного региона использовал RCNN на основе resnet
Изначально учился на том, что было в трейне, затем дообучал сеть на сгенерированных номерах
