
 Sistema de Recomendação por Similaridade de Imagens

Este é um sistema de recomendação que sugere imagens similares com base em características visuais, utilizando **Deep Learning** e **Redes Neurais Convolucionais**. Ele emprega a **ResNet50**, um modelo pré-treinado, para extrair embeddings das imagens e calcular a similaridade entre elas.

  Recursos Principais
- Carregamento de imagens diretamente no Google Colab.
- Extração de características visuais usando **ResNet50**.
- Cálculo da similaridade entre imagens com **similaridade do cosseno**.
- Exibição das imagens recomendadas usando **Matplotlib**.

 Como Usar:

  1 Instalar dependências
Certifique-se de que todas as dependências estão instaladas (caso esteja rodando fora do Colab):

  2 Executar o código
  
No Google Colab:
Faça upload das imagens.
O modelo analisará a similaridade entre elas.
As imagens mais semelhantes serão exibidas junto com a pontuação de similaridade.

   3 Saída esperada
O código exibirá:
A imagem de entrada.
Uma lista de imagens similares (se houver).
A similaridade entre elas.

   Tecnologias Utilizadas:
Python 3
TensorFlow / Keras
Scikit-Learn
Matplotlib
Google Colab (para execução online)

   Exemplo de Uso:
   
O usuário faz o upload de imagens (relógios, roupas, sapatos, etc.).
O modelo extrai características visuais de cada imagem.
A similaridade é calculada entre todas as imagens carregadas.
As imagens similares são exibidas como recomendação.
   Observações:
   
A recomendação se baseia apenas em características visuais, ignorando aspectos como marca ou preço.
O sistema pode ser ajustado para considerar diferentes faixas de similaridade.

 Contato
Caso tenha dúvidas ou sugestões, fique à vontade para entrar em contato! 
https://www.linkedin.com/in/sidney-santos-analista-de-dados/
