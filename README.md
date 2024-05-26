# goit-algo-hw-09 
Т 9 HW 



### Висновки
Алгоритм динамічного програмування є ефективним методом для вирішення задачі про мінімальну кількість монет. Основні висновки:
1. **Оптимальність**: Алгоритм завжди знаходить мінімальну кількість монет для будь-якого набору номіналів монет, гарантуючи оптимальне рішення.
2. **Універсальність**: Алгоритм працює для будь-яких наборів номіналів монет, включаючи випадки, коли жадібний алгоритм не може знайти оптимальне рішення.
3. **Часова і просторова складність**: Часова складність алгоритму O(n * amount), де n — кількість номіналів монет, а amount — сума. Просторова складність O(amount), оскільки потрібно зберігати проміжні результати для всіх можливих сум до заданої суми.
#### Порівняння з жадібним алгоритмом
- **Жадібний алгоритм**: Має меншу часову складність (O(n)) та просторову складність (O(1)). Він ефективний і простий у реалізації, але не завжди гарантує оптимальне рішення.
- **Алгоритм динамічного програмування**: Гарантує оптимальне рішення для будь-якого набору номіналів монет, але має вищу часову (O(n * amount)) та просторову (O(amount)) складність.
Для малих сум і стандартних наборів номіналів обидва алгоритми працюють швидко і ефективно. Однак для великих сум або нестандартних наборів номіналів алгоритм динамічного програмування є кращим вибором, оскільки він гарантує оптимальне рішення.
