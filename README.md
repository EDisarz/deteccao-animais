#  Projeto YOLOv8 – Detecção de Bois e Cavalos em Laçadas

## Grupo

- Allan da Silva Davila, Daniel Bilibio, Eduardo Disarz e Pedro H. Fanton

---

## Descrição do Dataset

O dataset utilizado neste projeto foi composto por **cerca de 200 imagens** de cenas de laçadas em ambientes rurais. As imagens foram obtidas manualmente e posteriormente **anotadas no Roboflow**, utilizando duas classes principais:

- `boi`
- `cavalo`

As imagens foram divididas em:

- **70%** para treinamento (`train`)
- **20%** para validação (`val`)
- **10%** para teste (`test`)

O dataset foi exportado no formato YOLOv8, gerando um arquivo `data.yaml` com as configurações necessárias.

---

## Descrição da Atividade Realizada

Este projeto tem como objetivo a **detecção de objetos com Deep Learning**, utilizando o modelo **YOLOv8** (You Only Look Once), e foi desenvolvido como parte da disciplina de **Computação Gráfica** – Prof. Me. Fahad Kalil.

### Etapas do projeto:

1. **Anotação das imagens** no [Roboflow](https://roboflow.com)
2. **Download do dataset** já estruturado em `train`, `val` e `test`
3. **Treinamento do modelo** YOLOv8 no Google Colab, com 100 épocas
4. **Predição com 5 imagens inéditas**
5. **Salvamento automático dos resultados** em `runs/detect/predict`

### Métricas avaliadas:

- Matriz de Confusão (`confusion_matrix.png`)
- Precision e Recall (`results.png`)
- F1 Score (`F1_curve.png`)
- mAP50 e mAP50-95 (`results.png`)

