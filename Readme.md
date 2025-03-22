# Classificador de Propagandas de Jogos de Azar

Este projeto tem como objetivo desenvolver um sistema capaz de identificar e classificar propagandas online que promovem jogos de azar, utilizando técnicas de visão computacional e aprendizado de máquina.

## Motivação

Com o crescimento das atividades de jogos de azar na internet, é essencial monitorar e regular as propagandas relacionadas a esse setor, visando proteger públicos vulneráveis e assegurar a conformidade com as regulamentações vigentes. Este projeto busca automatizar a identificação dessas propagandas, facilitando a detecção de conteúdos potencialmente problemáticos.

## Funcionalidades

- **Captura de Propagandas:** Coleta e armazenamento de imagens, GIFs e vídeos curtos (até 10 segundos) de propagandas online.
- **Análise de Conteúdo:** Utilização de redes neurais convolucionais para identificar elementos presentes nas propagandas.
- **Classificação de Risco:** Avaliação do potencial das propagandas promoverem jogos de azar, classificando-as como problemáticas ou não.

## Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas Principais:**
  - TensorFlow/Keras | pytorch : para construção e treinamento de redes neurais
  - OpenCV para processamento de imagens e vídeos
- **Ferramentas Adicionais:**
  - Amazon Rekognition ou Google Cloud Video Intelligence para análise de conteúdo pré-treinada
  - Roboflow para gerenciamento e aprimoramento contínuo do modelo

## Estrutura do Projeto

- `data/`: Contém as propagandas coletadas para análise.
- `notebooks/`: Notebooks Jupyter para experimentação e desenvolvimento de modelos.
- `models/`: Modelos de redes neurais treinados.
- `scripts/`: Scripts para processamento de dados e treinamento de modelos.
- `results/`: Relatórios e métricas de desempenho dos modelos.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas alterações (`git commit -m 'Adiciona nova feature'`).
4. Envie para o branch principal (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
