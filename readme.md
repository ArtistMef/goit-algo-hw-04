
| Algorithm            | Small                | Medium               | Large                |
| -------------------- | -------------------- | -------------------- | -------------------- |
| Insertion Sort       | 0.00288              | 0.32751              | 35.97809             |
| Merge Sort           | 0.00208              | 0.03098              | 0.42023              |
| Timsorted            | 0.00005              | 0.00117              | 0.01819              |
| Timsort              | 0.00004              | 0.00116              | 0.01814              |

Після 20-х запусків циклу сортування на списках різної величини, ми бачимо кардинальну різницю в швидкості сортування між алгоритмами.
Insertion Sort виявився найповільнішим, і зі збільшенням обсягу даних це відчувається суттєво.
Merge Sort показав набагато кращий результат, особливо в обробці більш великих даних.
Timsort, гібридний алгоритм між двлма попередніми, що використовується як рідна функція сортування в пайтоні, виявився найефективнішим серед усіх, з прекрасною швидкістю сортування різних величин даних. Тому не дивно, що ніхто не придумує колесо та пише власні алгоритми сортування, коли є такий доступний алгоритм під рукою.