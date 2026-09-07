# 05. Linkage / Сцепка

## English

The linkage is the mechanism that records connections between blocks and maintains an immutable history of those connections.

In the present concept the linkage is realised through blockchain-like principles (hashing, sequential ordering, cryptographic continuity).

### Responsibilities

1. Recording the fact of a connection  
2. Maintaining sequence  
3. Guaranteeing immutability of history  
4. Enabling cryptographic proof of origin  

### Explicit Non-Responsibilities

- Performing analysis  
- Generating interpretation  
- Making business or consensus decisions  
- Acting as an execution orchestrator  

### Attachment Principle

Interpretation resides inside the block.  
After formation it is **attached** to the linkage.

Consequently:

- the block remains autonomous  
- the history of connections becomes verifiable  
- any interpretation can be traced back to the exact analysis that produced it  

---

## Русский

Сцепка — механизм, который фиксирует связи между блоками и поддерживает неизменяемую историю этих связей.

В настоящей концепции сцепка реализуется на основе блокчейн-подобных принципов (хэширование, упорядоченная последовательность, криптографическая непрерывность).

### Ответственности

1. Фиксация факта связи  
2. Поддержание последовательности  
3. Гарантия неизменяемости истории  
4. Обеспечение возможности криптографического доказательства происхождения  

### Явные не-ответственности

- Выполнение анализа  
- Формирование интерпретации  
- Принятие бизнес-решений или решений консенсуса  
- Функционирование в качестве оркестратора исполнения  

### Принцип пристёгивания

Интерпретация находится внутри блока.  
После формирования она **пристёгивается** к сцепке.

Следствия:

- блок остаётся автономным  
- история связей становится верифицируемой  
- любая интерпретация может быть прослежена до точного анализа, который её породил
