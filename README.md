Эдуард Эмильевич, здравствуйте!

Стояла задача реализации менеджера памяти для эффективного управления памятью

Для этого были реализованы Fixed-Size Allocator (FSA) и Coalesce Allocator (CA)

FSA использовался для блоков памяти на 16, 32, 64, 128, 256, 512 байт

CA использовался для блоков памяти больших 512 байт и меньших 10 МБ

Если блок памяти оказывался больше 10 МБ, то управление передавалось ОС

Подпись: :) 
