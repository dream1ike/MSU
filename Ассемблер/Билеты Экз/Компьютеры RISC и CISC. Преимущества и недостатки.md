Связи: [[_Навигатор Билеты Ассемблер]]
Теги: #Ассемблер #Теория 

# Содержание:
- [[#**RISC (Reduced Instruction Set Computer)**]]
- [[#**CISC (Complex Instruction Set Computer)**]]

# **RISC (Reduced Instruction Set Computer)**

RISC – это архитектура компьютера, которая использует набор простых команд. Каждая из этих команд выполняется за один цикл тракта данных, производя арифметическую или логическую операцию над парой регистров и помещая результат обратно в регистр.

- **Преимущества RISC**:
  - RISC-системы могут быть более быстрыми, потому что их простые команды выполняются в десять раз быстрее, так как они не требуют интерпретации.
  - Поскольку скорость основной памяти приблизилась к скорости специальных командных ПЗУ, очевидны недостатки интерпретации.

- **Недостатки RISC**:
  - Несмотря на преимущество в производительности, RISC-системы могут быть менее совместимыми по сравнению с CISC-системами.
  - Компьютеры RISC обычно не совместимы с другими моделями.

# **CISC (Complex Instruction Set Computer)**

CISC – это архитектура компьютера, которая использует полный набор команд. Начиная с процессора Intel 486, процессоры CISC содержат RISC-ядра, которые выполняют самые простые и распространенные команды за один цикл тракта данных, в то время как более сложные команды интерпретируются по обычной технологии CISC.

- **Преимущества CISC**:
  - CISC позволяет использовать старое программное обеспечение без изменений.
  - Обычные команды выполняются быстро, а более сложные и редкие - медленно.

- **Недостатки CISC**:
  - Несмотря на "гибридный" подход, производительность процессоров CISC может быть ниже, чем у процессоров с архитектурой RISC.

**Общие замечания**

Команды ADD и SUB не делают разницы между знаковыми и беззнаковыми величинами, они просто складывают и вычитают биты.