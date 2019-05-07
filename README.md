# ES235 - Processamento de Imagem (CTG)
Repositório com exemplos e materiais de aula da disciplina **ES235 - Processamento de Imagem do curso de Engenharia Eletrônica (CTG)**.

### Para usar este repositório

**Requisitos**:
1. Para Windows: [[Git]](https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe) [[Python]](https://www.python.org/downloads/release/python-352/) *(**obs**: lembrar de marcar "add python to PATH")*
2. Para Ubuntu: `sudo apt-get install git python3 python3-pip jupyter-core jupyter-notebook`

Esse repositório irá armazenar códigos de exemplo para o material da disciplina. A maioria dos códigos serão disponibilizados em [**Python**](https://www.python.org/), testados na versão 3.5, no formato de Notebooks Jupyter. 

Ainda será necessário ter instalado as seguintes dependências:

```
matplotlib
opencv-python
Pillow
scikit-image
scikit-learn
jupyter
numpy
scipy
ipywidgets
```

Você poderá instalá-las de uma só vez usando o comando `pip install -r requirements.txt` **após** ter clonado o repositório. Por último, execute o Jupyter Notebook no seu computador e navegue até a pasta onde o repositório está clonado para abrir os arquivos de exemplo. Esses arquivos também estarão disponíveis aqui no github, porém **não** podem ser alterados.

### Ementa
1. Apresentação da disciplina e setup do ambiente;
2. [Representação de imagens, quantização, sistemas de cores, conversão colorido-escala de cinza](2_representacao);
3. [Histogramas](3_histogramas);
4. [Filtragem espacial *(pt. 1)*](4_filtragem_pt1);
5. [Filtragem espacial *(pt. 2)*](5_filtragem_pt2);
6. [Gradientes de imagens](6_gradientes);
7. [Segmentação por cor](7_segmentacao);
8. **Projeto 0**: controle de robô seguidor de linha
9. Acompanhamento de projeto;
10. [Transformações geométricas](10_transformacoes);
11. [**Projeto 1**: mapeamento projetivo](11_mapeamento);
12. Acompanhamento de projeto;
13. [Processamento morfológico](13_morfologico);
14. [Transformada de Hough *(detecção de linhas)*](14_hough_linhas);
15. [Transformada de Hough *(detecção de círculos)*](15_hough_circulos);
16. [Detecção de contornos e aproximação poligonal](16_contornos_aproximacao);
17. [Detecção de faces usando classificadores Haar *(pt. 1)*](17_haar);
18. [Detecção de faces usando classificadores Haar *(pt. 2)*](18_haar_pt2);
19. [Técnicas de Inpaint *(pt. 1)*](19_inpaint_pt1);
20. [Técnicas de Inpaint *(pt. 2)*](20_inpaint_pt2);
21. [**Projeto 2**: remover o logotipo de um vídeo usando Inpaint](21_miniprojeto2);
22. Acompanhamento de projeto;
23. Wavelets *(pt. 1)*;
24. Wavelets *(pt. 2)*;
25. Reconhecimento de caracteres;
26. Reconhecimento de marcadores;
27. **Projeto 3**: sistema de alerta de escaninho ocupado;
28. Acompanhamento de projeto.
