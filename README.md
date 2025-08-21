## Classificação de Dígitos Manuscritos com Regressão Logística

Esse script em Python demonstra como classificar dígitos manuscritos utilizando o modelo `LogisticRegression` da biblioteca scikit-learn. O fluxo inclui:

1. **Carregamento do Conjunto de Dados:**  
   O script utiliza o dataset `load_digits`, que contém imagens de dígitos manuscritos (0–9).

2. **Divisão dos Dados:**  
   O conjunto de dados é dividido em dados de treino e teste (80% treino, 20% teste) para avaliar o desempenho do modelo.

3. **Treinamento do Modelo:**  
   Um classificador de regressão logística é treinado com os dados de treino. O parâmetro `max_iter=1000` garante a convergência.

4. **Avaliação da Acurácia:**  
   A acurácia do modelo no conjunto de teste é exibida no console.

5. **Visualização da Predição:**  
   O script exibe uma das imagens de dígitos (índice 100) e mostra o rótulo previsto pelo modelo para essa imagem.

### Requisitos
- Python 3.x
- scikit-learn
- matplotlib

<img width="1920" height="1080" alt="Screenshot 2025-08-21 at 08 26 29" src="https://github.com/user-attachments/assets/c4e9a351-e041-4287-ac5c-a27055fd1a7a" />
