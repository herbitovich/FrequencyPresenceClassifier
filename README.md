# FrequencyPresenceClassifier
**A PyTorch binary classifier model identifying frequencies presence in audio signals.**
Классификатор, предсказывающий наличие частот определенного диапазона в изначальном сигнале, базируясь на фичах отфильтрованного по этому диапазону сигнала: спектрального центроида и ширины спектра.  
Список необходимых библиотек этого notebook'а включает, но, возможно, не ограничивается на:
- scipy 1.15.2
- numpy 2.2.2
- torch 2.6.0
- scikit-learn 1.6.1
- matplotlib 3.10.0

Использованная версия Python: 3.12.9  
При возникновении конфликта версий можно обратиться к списку всех зависимостей:
```bash
pip install -r requirements.txt
```