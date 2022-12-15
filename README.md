# hse22_hw5
## Ссылка на Google Colab
https://colab.research.google.com/drive/1DPikcUloBETFEZVF3S4XB-9GXanDDCHz?usp=sharing
## Описание метода нормализации данных
Используем метод TPM:
TPM означает количество транскриптов на миллион, и сумма всех значений TPM одинакова во всех образцах, так что значение TPM представляет собой относительный уровень экспрессии, который должен быть сопоставим между образцами.
$TPM{i}$ = $q_{i}/l_{i} \over ∑_{j}(q_{i}/l_{i})$ * $10^6$

Пренебрегая длиной:

$TPM{i}$ = $q_{i} \over ∑_{j}q_{i}$ * $10^6$
## Heatmap для экспрессии маркерных генов
![image](https://user-images.githubusercontent.com/99398496/207884190-9fd143c0-1beb-4276-8f6f-4c4cc5f9766e.png)

## Полученные визуализации UMAP и PCA
![image](https://user-images.githubusercontent.com/99398496/207885076-fae660c3-3020-431f-a975-49e7d2873d08.png)
![image](https://user-images.githubusercontent.com/99398496/207885113-2de8b499-0e98-4a00-a5f6-600cc2e7dab0.png)
