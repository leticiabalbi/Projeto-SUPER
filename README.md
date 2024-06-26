# Projeto-SUPER

### CBIS2020_Classificação_de_doenças_respiratórias_em_auscultas_pulmonares_com_crepitações.ipynb
  * **Descricão**: código da metodologia realizada no pôster submetido no CBIS 2020. Este experimento compreende à classificação de condições respiratórias Crônicas, Não Crônicas e Saudáveis utilizando extração de características manuais e Máquina de Vetores de Suporte. 
  
  * **Técnicas de pré-processamento**: reamostragem de frequência, segmentação por ciclo respiratório e fase inspiratória, filtro Butterworth, Hamming Window e normalização da amplitude;
  
  * **Extração de características**: Decomposição do modo empírico; foram extraídas 40 características de cada IMF gerada;
  
  * **Técnicas de de balanceamento e aumentação de dados**: Mudança de tom, undersampling aleatório;
  
  * **Classificador**: SVM.

  * Caso utilize esse código, cite: **SILVA, L. B. ; QUISPE, K. G. M. ; COLONNA, JUAN G. . Classificação de doenças respiratórias em auscultas pulmonares com crepitações. In: XVII Congresso Brasileiro de Informática em Saúde, 2020, Foz do Iguaçu. Anais do XVII Congresso Brasileiro de Informática em Saúde**.


### Classificação de doenças respiratórias em auscultas pulmonares.ipynb
   * **Descricão**: este experimento compreende à classificação de Bronquiectasia, Bronquiolite, Doença pulmonar obstrutiva crônica, Pneumonia, Infeccção do trato respiratório superior e paciente Saudável utilizando rede siamesa com triplet loss como extrator de características e K-nn como classificador.
   
   * **Técnicas de pré-processamento**: reamostragem de frequência, filtro Butterworth, normalização da amplitude, segmentação e preenchimento inteligente;
   
   * **Extração de características**: Espectrogramas Mel;
   
   * **Técnica de aumentação de dados**: SpecAugment;
   
   * **Modelo extrator de características**: Rede siamesa com triplet loss online semi-hard e Rede siamesa com triplet loss offline;
   
   * **Classificador**: K-nn.
