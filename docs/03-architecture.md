# 03. Architecture / Архитектура

## English

### Two Contours

**Internal Contour (inside the block)**  
Transmission → Analysis → Interpretation

- Transmission — reception of input data  
- Analysis — computation according to analytical parameters  
- Interpretation — formation of a meaningful conclusion  

**External Contour (between blocks)**  
Structure → Linkage → Transport

- Structure — schema and types of blocks  
- Linkage — cryptographic fixation of connections  
- Transport — delivery of data and results  

### Layer Responsibilities

| Layer          | Location       | Responsibility                     |
|----------------|----------------|------------------------------------|
| Analysis       | Inside block   | Computation                        |
| Interpretation | Inside block   | Assignment of meaning              |
| Linkage        | Outside        | Recording of connections & history |
| Transport      | Outside        | Movement of data                   |

### High-level Execution Flow

1. Data enters the block  
2. The block performs analysis  
3. The block produces an interpretation  
4. The result (analysis + interpretation) is attached to the linkage  
5. The linkage records the connection  
6. Transport delivers the result further if required  

---

## Русский

### Два контура

**Внутренний контур (внутри блока)**  
Передача → Анализ → Интерпретация

- Передача — получение входных данных  
- Анализ — вычисление по аналитическим параметрам  
- Интерпретация — формирование смыслового вывода  

**Внешний контур (между блоками)**  
Структура → Сцепка → Транспорт

- Структура — схема и типы блоков  
- Сцепка — криптографическая фиксация связей  
- Транспорт — доставка данных и результатов  

### Ответственность слоёв

| Слой           | Расположение   | Ответственность                    |
|----------------|----------------|------------------------------------|
| Анализ         | Внутри блока   | Вычисление                         |
| Интерпретация  | Внутри блока   | Придание смысла                    |
| Сцепка         | Снаружи        | Фиксация связей и истории          |
| Транспорт      | Снаружи        | Перемещение данных                 |

### Высокоуровневый поток выполнения

1. Данные поступают в блок  
2. Блок выполняет анализ  
3. Блок формирует интерпретацию  
4. Результат (анализ + интерпретация) пристёгивается к сцепке  
5. Сцепка фиксирует связь  
6. Транспорт доставляет результат дальше при необходимости
