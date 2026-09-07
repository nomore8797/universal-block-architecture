# 01. Principles / Принципы

## English

### First Principles

1. **Separation of Concerns**  
   Analysis and interpretation reside strictly inside the block.  
   Linkage and transport operate outside the block.  
   These layers never mix.

2. **Block Autonomy**  
   A block is a self-contained unit.  
   It can be executed, updated or replaced without compromising the integrity of the system.

3. **Interpretation as a Derivative of Analysis**  
   Interpretation is always computed from analytical parameters.  
   It is individual for each block, yet remains deterministic.

4. **Linkage as Pure Connection**  
   The linkage layer does not compute, interpret or make decisions.  
   Its sole purpose is to record connections, sequence and immutability.

5. **Flows over Global State**  
   The architecture prioritises verifiable data flows rather than a shared global state.

6. **Composability**  
   The system is designed as a constructor: blocks can be assembled into arbitrary configurations.

### Invariants

- A block has no direct knowledge of other blocks.
- The linkage layer has no knowledge of internal block computations.
- Every interpretation remains permanently attached to its originating block via the linkage.
- Any modification of a block creates a new version; previous interpretations remain valid.

### Explicit Non-Goals

- Mixing computation with consensus
- Maintaining a global shared state
- Dependence on any specific blockchain implementation
- Terminological overhead unrelated to the core architecture

---

## Русский

### Первые принципы

1. **Разделение ответственности**  
   Анализ и интерпретация находятся строго внутри блока.  
   Сцепка и транспорт работают вне блока.  
   Эти слои никогда не смешиваются.

2. **Автономность блока**  
   Блок является самостоятельной единицей.  
   Он может быть выполнен, обновлён или заменён без нарушения целостности системы.

3. **Интерпретация как производная анализа**  
   Интерпретация всегда вычисляется на основе аналитических параметров.  
   Она индивидуальна для каждого блока, но остаётся детерминированной.

4. **Сцепка как чистая связь**  
   Слой сцепки не выполняет вычислений, не интерпретирует и не принимает решений.  
   Его единственная задача — фиксировать связи, последовательность и неизменяемость.

5. **Потоки важнее глобального состояния**  
   Архитектура ориентирована на верифицируемые потоки данных, а не на общее глобальное состояние.

6. **Композируемость**  
   Система спроектирована как конструктор: блоки могут быть собраны в произвольные конфигурации.

### Инварианты

- Блок не обладает прямым знанием о других блоках.
- Слой сцепки не обладает знанием о внутренних вычислениях блока.
- Каждая интерпретация остаётся постоянно привязанной к своему исходному блоку через сцепку.
- Любое изменение блока создаёт новую версию; предыдущие интерпретации сохраняют силу.

### Явные не-цели

- Смешение вычислений и консенсуса
- Поддержание глобального разделяемого состояния
- Зависимость от конкретной реализации блокчейна
- Терминологическая избыточность, не связанная с ядром архитектуры
