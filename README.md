# DESAFIO-HACKATHON-MICROSOFT
Desafio proposto pelo Ânima para nomear 5 vencedores de vouchers 100% para o exame AI-100 da Microsoft

## DESAFIO 1

### QUESTIONAMENTO
BOM EM MATEMÁTICA	=	BOM EM CIÊNCIAS	?											
																		
MÉTODO UTILIZADO: REGRESSÃO																		
																		
FAZENDO O UPLOAD DO ARQUIVO DE MICRODADOS ENEM 2019 NO CONJUNTO DE DADOS DO AZURE ML																		
UM ARQUIVO TABULAR SEPARADO POR PONTO E VÍRGULA																		
ARQUIVO DE 3GB																		
																		
É NECESSÁRIO SELECIONAR OS SEGUINTES CAMPOS DA PROVA OBJETIVA:																		
NU_NOTA_CN																		
NU_NOTA_CH																		
NU_NOTA_LC																		
NU_NOTA_MT																		
																		
O MODELO QUE ESTOU DESENVOLVENDO IRÁ PREVER A NOTA DE CIÊNCIAS DA NATUREZA COM BASE NA NOTA DE MATEMÁTICA																		
![image](https://user-images.githubusercontent.com/75635093/122083450-45582780-cdd7-11eb-853e-39e663dc570d.png)
																		
MAE = 40,14																		
RMSE = 50,44																		
RSE = 0,44																		
RAE = 0,63																		
CD = 0,55																		

![image](https://user-images.githubusercontent.com/75635093/122083566-5b65e800-cdd7-11eb-92bb-6b763089c65f.png)

PODEMOS ANALISAR QUE O ERRO MÉDIO ABSOLUTO FOI DE 40,14 E SUA DISCREPÂNCIA COM A RAIZ DO ERRO QUADRÁTICO MÉDIO FOI DE 10,3 (PEQUENA)																		
O ERRO QUADRADO RELATIVO NÃO FOI TÃO BOM, MAS FICOU ABAIXO DE 0,5, SENDO ASSIM, UM MODELO COM MAIS PRECISÃO																		
O ERRO ABSOLUTO RELATIVO FICOU LEVEMENTE PIOR 																		
O R-QUADRADO FICOU ACIMA DE 0,5, TENDO ESPAÇO PARA MELHORIAS																		
																		
PRIMEIRA NOTA CN, SEGUNDA NOTA CH, TERCEIRA NOTA LC, QUARTA NOTA MT																		
																		
"NU_INSCRICAO;NU_ANO;CO_MUNICIPIO_RESIDENCIA;NO_MUNICIPIO_RESIDENCIA;CO_UF_RESIDENCIA;SG_UF_RESIDENCIA;NU_IDADE;TP_SEXO;TP_ESTADO_CIVIL;TP_COR_RACA;TP_NACIONALIDADE;CO_MUNICIPIO_NASCIMENTO;NO_MUNICIPIO_NASCIMENTO;CO_UF_NASCIMENTO;SG_UF_NASCIMENTO;TP_ST_CONCLUSAO;TP_ANO_CONCLUIU;TP_ESCOLA;TP_ENSINO;IN_TREINEIRO;CO_ESCOLA;CO_MUNICIPIO_ESC;NO_MUNICIPIO_ESC;CO_UF_ESC;SG_UF_ESC;TP_DEPENDENCIA_ADM_ESC;TP_LOCALIZACAO_ESC;TP_SIT_FUNC_ESC;IN_BAIXA_VISAO;IN_CEGUEIRA;IN_SURDEZ;IN_DEFICIENCIA_AUDITIVA;IN_SURDO_CEGUEIRA;IN_DEFICIENCIA_FISICA;IN_DEFICIENCIA_MENTAL;IN_DEFICIT_ATENCAO;IN_DISLEXIA;IN_DISCALCULIA;IN_AUTISMO;IN_VISAO_MONOCULAR;IN_OUTRA_DEF;IN_GESTANTE;IN_LACTANTE;IN_IDOSO;IN_ESTUDA_CLASSE_HOSPITALAR;IN_SEM_RECURSO;IN_BRAILLE;IN_AMPLIADA_24;IN_AMPLIADA_18;IN_LEDOR;IN_ACESSO;IN_TRANSCRICAO;IN_LIBRAS;IN_TEMPO_ADICIONAL;IN_LEITURA_LABIAL;IN_MESA_CADEIRA_RODAS;IN_MESA_CADEIRA_SEPARADA;IN_APOIO_PERNA;IN_GUIA_INTERPRETE;IN_COMPUTADOR;IN_CADEIRA_ESPECIAL;IN_CADEIRA_CANHOTO;IN_CADEIRA_ACOLCHOADA;IN_PROVA_DEITADO;IN_MOBILIARIO_OBESO;IN_LAMINA_OVERLAY;IN_PROTETOR_AURICULAR;IN_MEDIDOR_GLICOSE;IN_MAQUINA_BRAILE;IN_SOROBAN;IN_MARCA_PASSO;IN_SONDA;IN_MEDICAMENTOS;IN_SALA_INDIVIDUAL;IN_SALA_ESPECIAL;IN_SALA_ACOMPANHANTE;IN_MOBILIARIO_ESPECIFICO;IN_MATERIAL_ESPECIFICO;IN_NOME_SOCIAL;CO_MUNICIPIO_PROVA;NO_MUNICIPIO_PROVA;CO_UF_PROVA;SG_UF_PROVA;TP_PRESENCA_CN;TP_PRESENCA_CH;TP_PRESENCA_LC;TP_PRESENCA_MT;CO_PROVA_CN;CO_PROVA_CH;CO_PROVA_LC;CO_PROVA_MT;NU_NOTA_CN;NU_NOTA_CH;NU_NOTA_LC;NU_NOTA_MT;TX_RESPOSTAS_CN;TX_RESPOSTAS_CH;TX_RESPOSTAS_LC;TX_RESPOSTAS_MT;TP_LINGUA;TX_GABARITO_CN;TX_GABARITO_CH;TX_GABARITO_LC;TX_GABARITO_MT;TP_STATUS_REDACAO;NU_NOTA_COMP1;NU_NOTA_COMP2;NU_NOTA_COMP3;NU_NOTA_COMP4;NU_NOTA_COMP5;NU_NOTA_REDACAO;Q001;Q002;Q003;Q004;Q005;Q006;Q007;Q008;Q009;Q010;Q011;Q012;Q013;Q014;Q015;Q016;Q017;Q018;Q019;Q020;Q021;Q022;Q023;Q024;Q025 190001199383;2019;1721000;Palmas;17;TO;25;F;1;1;1;1721000;Palmas;17;TO;1;4;1;;0;;;;;;;;;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;1721000;Palmas;17;TO;1;1;1;1;504;510;513;516;483.8;503.6;537.3;392;BACCEEBEECDBEDDAEECDEDEADEBBCDBCAACADEEACCBBD;AECEDADAABAADBAADAEBACBAECCDAEADCDBBECCEDABCD;99999AAABEBBCCBDCAEECADBACAADAECCCDCCBAEBDEEEAEECA;DDBBBBCDCCDCAECCBBECDAEBADCD..CABCCECAEBDBBDA;1;BEEAAEBEEBADEADDADAEABCEDDDBCBCBCCACBCDADCCEB;EEBCEEDBADBBCBABCCADCEBACDBBACCACACBEADBBADCB;ADBBEDCABAABBCBCDAAECDDDBAAAECADECDCEBDEEAECBDBBCC;BEDEEEAADBEBACABCDBABECECACADCBDCCEDCDABECDDD;1;120;120;120;100;0;460;C;E;B;D;4;E;A;C;C;A;B;B;A;B;A;A;A;A;C;A;B;D;A;B;B
190001237802;2019;3118601;Contagem;31;MG;22;F;1;1;1;3118601;Contagem;31;MG;1;4;1;1;0;;;;;;;;;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;3118601;Contagem;31;MG;1;1;1;1;504;510;513;516;513.6;575.5;570.7;677;EEBEDEEEEEBDCEEBEEEEABEEBEEBAEDEECECCDBCECEAE;EEDCCEDDBCBEABAAABADCEDABDBBCBDCCCCDAEDEDBDCB;ABBBE99999ABBCACCCAEEEDCCDADCCAEDEDDEEDBBDECBDECCC;CDEEEEEAEECBABABCDCACEEEEEEDEEACEAEDEBEEECEDE;0;BEEAAEBEEBADEADDADAEABCEDDDBCBCBCCACBCDADCCEB;EEBCEEDBADBBCBABCCADCEBACDBBACCACACBEADBBADCB;ADBBEDCABAABBCBCDAAECDDDBAAAECADECDCEBDEEAECBDBBCC;BEDEEEAADBEBACABCDBABECECACADCBDCCEDCDABECDDD;1;160;120;180;200;200;860;E;E;C;C;3;G;A;C;D;B;A;B;B;B;A;B;A;A;B;A;A;C;B;B;B
190001782198;2019;5107602;Rondonópolis;51;MT;37;M;2;2;1;5107602;Rondonópolis;51;MT;1;13;1;;0;;;;;;;;;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;5107602;Rondonópolis;51;MT;1;1;1;1;505;508;512;518;563.7;644.9;564.2;675.3;DCDBDEDCDDBCBEADBEBBCDBDBDEBEBACABDBDADEDACAE;ABABADBECAEEBCBBDCBEEDBDEADBEACDBEEBAACABACEB;BBDDA99999ABACBECEAECECCDEAEDCDAEBDAEDEDECABCAADCD;DDCBADCBCDEABEACEBBCADEBEECEADBECDBADEAECACDD;0;DADCCEBBCCACBEEBEEBACBCDDDDADBCBBCEAEADEADAAE;CBABADBBCEEEBCBADCBEEDBBEADBBACDBBACCCCADACAC;BBEDABDACACBABAECBBCCADCEBDBBCDDEEAAADDBECDECAAECD;DBEBACABCDBABECEEEDCBDCCEDCDABEDAADDDECACAECB;1;160;200;180;180;80;800;B;B;C;B;7;E;A;B;D;A;C;B;A;B;A;B;A;A;B;A;A;E;A;B;B
190001421548;2019;2924009;Paulo Afonso;29;BA;22;F;1;3;1;2924009;Paulo Afonso;29;BA;1;5;1;1;0;;;;;;;;;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;0;2924009;Paulo Afonso;29;BA;1;1;1;1;505;508;512;518;484.6;488.4;507.2;594.7;BADEBCACADECAEAAAECCCDEACCEA.ECCDDCECBEBADAAC;AAAECDAACDAEDCDBDCBBDDAECBBECBDDDECCACCEDEACA;99999BEDAACECEACDCDEBECACBDDECAACDBACDCAECADEACEBD;ACBBAECECDBDDDCEDCEACDBCDCDDAAEAEDDCECDCBDECB;1;DADCCEBBCCACBEEBEEBACBCDDDDADBCBBCEAEADEADAAE;CBABADBBCEEEBCBADCBEEDBBEADBBACDBBACCCCADACAC;BBEDABDACACBABAECBBCCADCEBDBBCDDEEAAADDBECDECAAECD;DBEBACABCDBABECEEEDCBDCCEDCDABEDAADDDECACAECB;1;140;120;120;160;60;600;E;B;C;B;3;B;A;B;B;A;A;B;A;A;A;A;A;A;B;A;A;B;A;A;A"																															
INCLUI OS DADOS APENAS DAS COLUNAS DE NOTA CH, LC E MT PARA PREVISÃO DA NOTA DE CN																		
DECIDI TIRAR DUAS E DEIXAR APENAS AS NOTAS DE MT, POIS O DESAFIO PEDE PARA PREVER A NOTA DE CN COM BASE NA NOTA DE MT																		
DEU ERRADO																		
TENTANDO NOVAMENTE COM AS TRÊS NOTAS SÓ QUE COM A EXCLUSÃO DA COLUNA NU_NOTA_CN DO DATASET

### SITUAÇÃO ATUAL:
AINDA TENTANDO RESOLVER A QUESTÃO DA PREVISÃO DA NOTA

