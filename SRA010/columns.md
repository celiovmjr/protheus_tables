| COLUMN_NAME | TYPE              | DESCRIPTION                            |
| ------------ | ----------------- | -------------------------------------- |
| RA_FILIAL   | varchar(4)        | Código da filial                       |
| RA_BITMAP   | varchar(20)       | Bitmap de controle interno             |
| RA_MAT      | varchar(6)        | Matrícula do funcionário               |
| RA_NOME     | varchar(30)       | Nome do funcionário                    |
| RA_NOMECMP  | varchar(70)       | Nome completo do funcionário           |
| RA_MAE      | varchar(40)       | Nome da mãe                            |
| RA_PAI      | varchar(40)       | Nome do pai                            |
| RA_SEXO     | varchar(1)        | Sexo (M/F)                             |
| RA_NSOCIAL  | varchar(70)       | Nome social                            |
| RA_HOJORVA  | varchar(1)        | Horário de jornada variável (S/N)      |
| RA_RACACOR  | varchar(1)        | Raça/cor                               |
| RA_NASC     | varchar(8)        | Data de nascimento (AAAAMMDD)          |
| RA_ALTNASC  | varchar(1)        | Indicador de data alternativa          |
| RA_ESTCIVI  | varchar(1)        | Estado civil                           |
| RA_CPAISOR  | varchar(5)        | Código do país de origem               |
| RA_NACIONA  | varchar(2)        | Nacionalidade                          |
| RA_NACIONC  | varchar(5)        | Código de nacionalidade                |
| RA_BRNASEX  | varchar(1)        | Nacionalidade brasileira (S/N)         |
| RA_NATURAL  | varchar(2)        | Naturalidade                           |
| RA_CODMUNN  | varchar(5)        | Código do município de nascimento      |
| RA_MUNNASC  | varchar(30)       | Nome do município de nascimento        |
| RA_APELIDO  | varchar(15)       | Apelido                                |
| RA_GRINRAI  | varchar(2)        | Grau de instrução (RAIS)               |
| RA_EMAIL    | varchar(50)       | Email principal                        |
| RA_EMAIL2   | varchar(60)       | Email secundário                       |
| RA_RECMAIL  | varchar(1)        | Recebe email (S/N)                     |
| RA_TPMAIL   | varchar(1)        | Tipo de email                          |
| RA_DEFIFIS  | varchar(1)        | Deficiência física (S/N)               |
| RA_BRPDH    | varchar(1)        | Benefício Previdenciário (S/N)         |
| RA_TPDEFFI  | varchar(1)        | Tipo de deficiência física             |
| RA_PORTDEF  | varchar(6)        | Portador de deficiência (código)       |
| RA_OBSDEFI  | image(2147483647) | Observações sobre deficiência          |
| RA_CC       | varchar(11)       | Centro de custo                        |
| RA_CLVL     | varchar(11)       | Classificação do nível                 |
| RA_ITEM     | varchar(9)        | Código do item                         |
| RA_ADMISSA  | varchar(8)        | Data de admissão (AAAAMMDD)            |
| RA_ALTADM   | varchar(1)        | Alteração na admissão (S/N)            |
| RA_DEPIR    | varchar(2)        | Departamento interno                   |
| RA_TIPOADM  | varchar(2)        | Tipo de admissão                       |
| RA_DEPSF    | varchar(2)        | Departamento setor financeiro          |
| RA_DEMISSA  | varchar(8)        | Data de demissão (AAAAMMDD)            |
| RA_OPCAO    | varchar(8)        | Opção de benefício                     |
| RA_ALTOPC   | varchar(1)        | Alteração da opção (S/N)               |
| RA_BCDPFGT  | varchar(8)        | Base de cálculo FGTS                   |
| RA_CTDPFGT  | varchar(12)       | Conta do FGTS                          |
| RA_CHAPA    | varchar(5)        | Número da chapa                        |
| RA_PERFGTS  | float             | Percentual FGTS                        |
| RA_LOCBNF   | varchar(4)        | Local de benefício                     |
| RA_TNOTRAB  | varchar(3)        | Tipo de nota de trabalho               |
| RA_BCDEPSA  | varchar(8)        | Base de cálculo de Pensão              |
| RA_TPCTSAL  | varchar(1)        | Tipo de contrato salarial              |
| RA_CTDEPSA  | varchar(12)       | Conta da pensão alimentícia            |
| RA_TPPREVI  | varchar(1)        | Tipo de previdência                    |
| RA_SITFOLH  | varchar(1)        | Situação na folha                      |
| RA_PROCES   | varchar(5)        | Processo interno                       |
| RA_HRSMES   | float             | Horas mensais                          |
| RA_HRSEMAN  | float             | Horas semanais                         |
| RA_CATFUNC  | varchar(1)        | Categoria funcional                    |
| RA_HRSDIA   | float             | Horas diárias                          |
| RA_CODFUNC  | varchar(5)        | Código funcional                       |
| RA_SALARIO  | float             | Salário                                |
| RA_ANTEAUM  | float             | Antecipação de aumento                 |
| RA_PGCTSIN  | varchar(1)        | Pagamento CTPS (S/N)                   |
| RA_ADCPERI  | varchar(1)        | Adicional de periculosidade            |
| RA_CESTAB   | varchar(1)        | Cesta básica (S/N)                     |
| RA_TPCONTR  | varchar(1)        | Tipo de contrato                       |
| RA_DTFIMCT  | varchar(8)        | Data fim do contrato (AAAAMMDD)        |
| RA_VALEREF  | varchar(3)        | Vale refeição                          |
| RA_VALEALI  | varchar(3)        | Vale alimentação                       |
| RA_HOPARC   | varchar(1)        | Horário parcial (S/N)                  |
| RA_SEGUROV  | varchar(2)        | Código do seguro de vida               |
| RA_CLAURES  | varchar(1)        | Classificação de usuário               |
| RA_PERCADT  | float             | Percentual adicional noturno           |
| RA_PENSALI  | float             | Percentual de pensão alimentícia       |
| RA_SINDICA  | varchar(2)        | Código do sindicato                    |
| RA_CBO      | varchar(5)        | Código CBO                             |
| RA_ALTCBO   | varchar(1)        | Alteração de CBO (S/N)                 |
| RA_TIPOPGT  | varchar(1)        | Tipo de pagamento                      |
| RA_VIEMRAI  | varchar(2)        | Código de regime de trabalho           |
| RA_CATEG    | varchar(2)        | Categoria                              |
| RA_CATEFD   | varchar(3)        | Categoria do funcionário               |
| RA_PERICUL  | float             | Adicional de periculosidade            |
| RA_VCTOEXP  | varchar(8)        | Data de vencimento do exame            |
| RA_INSMIN   | float             | Insalubridade mínima                   |
| RA_VCTEXP2  | varchar(8)        | Segunda data de vencimento do exame    |
| RA_INSMED   | float             | Insalubridade média                    |
| RA_EXAMEDI  | varchar(8)        | Data do exame médico                   |
| RA_DTVTEST  | varchar(8)        | Data de teste                          |
| RA_ADCINS   | varchar(1)        | Adicional de insalubridade (S/N)       |
| RA_AFASFGT  | varchar(2)        | Afaste FGTS                            |
| RA_ASSIST   | varchar(1)        | Assistência (S/N)                      |
| RA_CONFED   | varchar(1)        | Confederação (S/N)                     |
| RA_MENSIND  | varchar(1)        | Mensalidade sindical                   |
| RA_RESCRAI  | varchar(2)        | Reserva de cargo                       |
| RA_MESESAN  | float             | Meses de serviço                       |
| RA_FTINSAL  | float             | Fator insalubridade                    |
| RA_MESTRAB  | varchar(2)        | Meses trabalhados                      |
| RA_CLASSEC  | varchar(2)        | Classificação sindical                 |
| RA_OCORREN  | varchar(2)        | Ocorrência                             |
| RA_PERCSAT  | float             | Percentual adicional noturno           |
| RA_CARGO    | varchar(5)        | Código do cargo                        |
| RA_CODTIT   | varchar(2)        | Código do título                       |
| RA_POSTO    | varchar(9)        | Posto                                  |
| RA_DEPTO    | varchar(9)        | Departamento                           |
| RA_ALTNOME  | varchar(1)        | Nome alternativo (S/N)                 |
| RA_CODRET   | varchar(4)        | Código do retorno                      |
| RA_FECREI   | varchar(8)        | Data de fechamento                     |
| RA_CRACHA   | varchar(10)       | Número do crachá                       |
| RA_DEMIANT  | varchar(8)        | Data de demissão anterior              |
| RA_REGRA    | varchar(2)        | Código da regra                        |
| RA_MOLEST   | varchar(8)        | Motivo de afastamento                  |
| RA_COMPSAB  | varchar(1)        | Computa sábado (S/N)                   |
| RA_EAPOSEN  | varchar(1)        | Data aposentadoria                     |
| RA_NJUD14   | varchar(20)       | Número judicial                        |
| RA_TPREINT  | varchar(1)        | Tipo de reintegração                   |
| RA_SEQTURN  | varchar(2)        | Sequência do turno                     |
| RA_NRPROC   | varchar(20)       | Número do processo                     |
| RA_SENHA    | varchar(6)        | Senha                                  |
| RA_NRLEIAN  | varchar(14)       | Número de carteira de lei              |
| RA_DTEFRET  | varchar(8)        | Data efetiva retorno                   |
| RA_DTEFRTN  | varchar(8)        | Data efetiva retorno                   |
| RA_CIC      | varchar(11)       | Código de identificação civil          |
| RA_NIVEL    | varchar(2)        | Nível hierárquico                      |
| RA_PIS      | varchar(12)       | Número do PIS                          |
| RA_TPRCBT   | varchar(1)        | Tipo de recolhimento                   |
| RA_ALTPIS   | varchar(1)        | Alteração do PIS (S/N)                 |
| RA_TCFMSG   | varchar(6)        | Código de mensagem                     |
| RA_RG       | varchar(15)       | Registro Geral (RG)                    |
| RA_INSSSC   | varchar(1)        | INSS contribuinte (S/N)                |
| RA_DTRGEXP  | varchar(8)        | Data de expedição do RG                |
| RA_RGUF     | varchar(2)        | Unidade federativa do RG               |
| RA_RGORG    | varchar(3)        | Órgão expedidor do RG                  |
| RA_RGEXP    | varchar(6)        | Código de expedição RG                 |
| RA_DISTSN   | varchar(1)        | Distinção sindical (S/N)               |
| RA_ORGEMRG  | varchar(5)        | Código do órgão expedidor RG           |
| RA_COMPLRG  | varchar(20)       | Complemento do RG                      |
| RA_NUMCP    | varchar(8)        | Número do CPF                          |
| RA_BHFOL    | varchar(1)        | Beneficiário na folha (S/N)            |
| RA_SERCP    | varchar(5)        | Série do CPF                           |
| RA_UFCP     | varchar(2)        | Unidade federativa CPF                 |
| RA_ACUMBH   | varchar(1)        | Acúmulo de benefícios (S/N)            |
| RA_OKTRANS  | varchar(2)        | OK na transferência                    |
| RA_DTCPEXP  | varchar(8)        | Data de expiração do CPF               |
| RA_ALTCP    | varchar(1)        | Alteração CPF (S/N)                    |
| RA_TABELA   | varchar(3)        | Código da tabela                       |
| RA_TABNIVE  | varchar(2)        | Nível da tabela                        |
| RA_HABILIT  | varchar(11)       | Habilitação                            |
| RA_TABFAIX  | varchar(2)        | Faixa da tabela                        |
| RA_CNHORG   | varchar(20)       | CNH - número                           |
| RA_DTEMCNH  | varchar(8)        | Data de emissão da CNH                 |
| RA_DTVCCNH  | varchar(8)        | Data de vencimento da CNH              |
| RA_RECPFNC  | varchar(1)        | Recebe pensão (S/N)                    |
| RA_CATCNH   | varchar(1)        | Categoria da CNH                       |
| RA_UFCNH    | varchar(2)        | UF da CNH                              |
| RA_TIPENDE  | varchar(1)        | Tipo de endereço                       |
| RA_RESERVI  | varchar(12)       | Reservista                             |
| RA_TITULOE  | varchar(12)       | Título de eleitor                      |
| RA_RESEXT   | varchar(1)        | Reserva externa (S/N)                  |
| RA_PAISEXT  | varchar(5)        | País de origem externa                 |
| RA_ZONASEC  | varchar(8)        | Zona eleitoral                         |
| RA_SECAO    | varchar(4)        | Seção eleitoral                        |
| RA_LOGRTP   | varchar(4)        | Tipo de logradouro                     |
| RA_REGISTR  | varchar(6)        | Registro                               |
| RA_FICHA    | varchar(8)        | Ficha                                  |
| RA_LOGRDSC  | varchar(80)       | Descrição do logradouro                |
| RA_SERVENT  | varchar(6)        | Serventia                              |
| RA_CODACER  | varchar(2)        | Código do acesso                       |
| RA_LOGRNUM  | varchar(10)       | Número do logradouro                   |
| RA_REGCIVI  | varchar(2)        | Registro civil                         |
| RA_ENDEREC  | varchar(30)       | Endereço                               |
| RA_TPLIVRO  | varchar(1)        | Tipo de livro                          |
| RA_CLASEST  | varchar(2)        | Classe de estado                       |
| RA_NUMENDE  | varchar(6)        | Número do endereço                     |
| RA_MSBLQL   | varchar(1)        | Código de bloqueio                     |
| RA_TIPCERT  | varchar(1)        | Tipo de certificado                    |
| RA_COMPLEM  | varchar(15)       | Complemento do endereço                |
| RA_EMICERT  | varchar(8)        | Data de emissão do certificado         |
| RA_BAIRRO   | varchar(15)       | Bairro                                 |
| RA_MATCERT  | varchar(32)       | Matrícula do certificado               |
| RA_ESTADO   | varchar(2)        | Estado                                 |
| RA_LIVCERT  | varchar(8)        | Livro do certificado                   |
| RA_CODMUN   | varchar(5)        | Código do município                    |
| RA_FOLCERT  | varchar(4)        | Folha do certificado                   |
| RA_CARCERT  | varchar(30)       | Cargo no certificado                   |
| RA_MUNICIP  | varchar(20)       | Município                              |
| RA_UFCERT   | varchar(2)        | UF do certificado                      |
| RA_CEP      | varchar(8)        | CEP                                    |
| RA_CPOSTAL  | varchar(9)        | Código postal                          |
| RA_CDMUCER  | varchar(5)        | Código do município do certificado     |
| RA_CEPCXPO  | varchar(8)        | CEP do comprovante postal              |
| RA_NUMEPAS  | varchar(15)       | Número do passaporte                   |
| RA_ALTEND   | varchar(1)        | Alteração de endereço (S/N)            |
| RA_EMISPAS  | varchar(15)       | Emissor do passaporte                  |
| RA_DDDFONE  | varchar(2)        | Código DDD telefone                    |
| RA_TIPAMED  | varchar(1)        | Tipo de atendimento médico             |
| RA_UFPAS    | varchar(2)        | UF do passaporte                       |
| RA_ASMEDIC  | varchar(2)        | Assistência médica                     |
| RA_TELEFON  | varchar(20)       | Telefone                               |
| RA_DDDCELU  | varchar(2)        | Código DDD celular                     |
| RA_DEMIPAS  | varchar(8)        | Data de emissão do passaporte          |
| RA_DPASSME  | varchar(2)        | Data de passaporte médica              |
| RA_DVALPAS  | varchar(8)        | Data de validade do passaporte         |
| RA_NUMCELU  | varchar(10)       | Número do celular                      |
| RA_TPASODO  | varchar(1)        | Tipo de associado odontológico         |
| RA_ASODONT  | varchar(2)        | Assistência odontológica               |
| RA_CHIDENT  | varchar(25)       | Chave de identificação                 |
| RA_CODPAIS  | varchar(5)        | Código do país                         |
| RA_NUMRIC   | varchar(12)       | Número do registro de receita          |
| RA_EMISRIC  | varchar(10)       | Data de emissão do registro de receita |
| RA_UFRIC    | varchar(2)        | UF do registro de                      |


receita    |
| RA_CDMURIC  | varchar(5)      | Código do município da receita|
| RA_NUMINSC  | varchar(11)     | Número de inscrição          |
| RA_SERVICO  | varchar(60)     | Serviço                     |
| RA_DEXPRIC  | varchar(8)      | Data de expiração do registro |
| RA_CODIGO   | varchar(14)     | Código                      |
| RA_OCEMIS   | varchar(20)     | Código de emissão            |
| RA_OCDTEXP  | varchar(8)      | Data de expedição           |
| RA_OCDTVAL  | varchar(8)      | Data de validade            |
| RA_CODUNIC  | varchar(30)     | Código da unidade           |
| RA_PRCFCH   | varchar(5)      | Código do fechamento        |
| RA_PERFCH   | varchar(6)      | Período de fechamento       |
| RA_ROTFCH   | varchar(3)      | Roteiro de fechamento       |
| RA_NUPFCH   | varchar(2)      | Número do fechamento        |
| RA_RNE      | varchar(14)     | Registro Nacional de Estrangeiro|
| RA_RNEORG   | varchar(20)     | Órgão emissor do RNE         |
| RA_RNEDEXP  | varchar(8)      | Data de expedição do RNE     |
| RA_DATCHEG  | varchar(8)      | Data de chegada             |
| RA_ANOCHEG  | varchar(2)      | Ano da chegada              |
| RA_NUMNATU  | varchar(10)     | Número de naturalização      |
| RA_DATNATU  | varchar(8)      | Data da naturalização        |
| RA_CASADBR  | varchar(1)      | Casado no Brasil (S/N)       |
| RA_FILHOBR  | varchar(1)      | Filhos no Brasil (S/N)       |
| RA_INSSAUT  | varchar(1)      | INSS autorizado (S/N)         |
| RA_REGIME   | varchar(1)      | Regime de trabalho           |
| RA_FWIDM    | varchar(34)     | ID de funcionário            |
| RA_INSMAX   | float           | Insalubridade máxima          |
| RA_ADCCONF  | float           | Adicional de confusão         |
| RA_ADCTRF   | float           | Adicional de transferência    |
| RA_PLSAUDE  | varchar(1)      | Plano de saúde (S/N)          |
| RA_RHEXP    | varchar(6)      | Registro de horas extras      |
| RA_ADTPOSE  | varchar(6)      | Data adicional de posse       |
| RA_TPJORNA  | varchar(1)      | Tipo de jornada              |
| RA_FITIPEN  | varchar(4)      | Tipo de filiação previdenciária|
| RA_MATIPEN  | varchar(6)      | Matrícula previdenciária      |
| RA_TIPOPEN  | varchar(1)      | Tipo de pensão              |
| RA_APOSENT  | varchar(8)      | Data de aposentadoria         |
| RA_SUBCARR  | float           | Subcarreira                  |
| RA_DTNOMEA  | varchar(8)      | Data de nomeação alternativa  |
| RA_DEFETIV  | varchar(8)      | Deficiência efetiva          |
| RA_CODCON   | varchar(4)      | Código do contrato           |
| RA_ADICEDI  | varchar(1)      | Adicional de dedicação        |
| RA_JORNRED  | float           | Jornada reduzida             |
| RA_TPSBCOM  | varchar(1)      | Tipo de base de cálculo      |
| RA_DTHREST  | varchar(8)      | Data do último descanso      |
| RA_TPCUEST  | varchar(1)      | Tipo de custeio             |
| RA_ANOSEME  | float           | Anos de serviço semestrais   |
| RA_PERESTU  | varchar(1)      | Percentual de estudo         |
| RA_DTCAGED  | varchar(8)      | Data do caged               |
| RA_CTRLEMA  | float           | Controle de emendas           |
| RA_MATMIG   | varchar(20)     | Matrícula de migração        |
| RA_AUTMEI   | varchar(1)      | Autorização MEI (S/N)         |
| D_E_L_E_T_  | varchar(1)      | Indicador de exclusão lógica  |
| R_E_C_N_O_  | int             | Número de registro interno    |
| R_E_C_D_E_L_| int             | Número de exclusão lógica     |
| RA_USRADM   | varchar(6)      | Usuário administrador         |
| RA_YSERRES  | varchar(1)      | Indicador de série reserva    |
| RA_YDTRESE  | varchar(8)      | Data de reserva              |
| RA_YCODCNV  | varchar(12)     | Código de convênio           |
| RA_YDATCUR  | varchar(8)      | Data de curso                |
| RA_YVENCUR  | varchar(8)      | Data de vencimento do curso  |
| RA_YAVAPSI  | varchar(8)      | Data de avaliação psicológica |
| RA_YVENCNV  | varchar(8)      | Data de vencimento do convênio|
| RA_YVENAVA  | varchar(8)      | Data de validade do aviso    |
| RA_YAPUR    | varchar(1)      | Apuração (S/N)                |
| RA_DESEPS   | varchar(254)    | Descrição do benefício        |
| RA_PLAPRE   | varchar(14)     | Plano de aposentadoria       |
| RA_DTINCON  | varchar(8)      | Data de início do contrato    |
| RA_HABILMT  | varchar(1)      | Habilitação para multa        |
| RA_TIPCTA   | varchar(1)      | Tipo de conta                |
| RA_CTPCD    | varchar(1)      | Código de conta              |
| RA_KEYLOC   | varchar(4)      | Chave do local               |
| RA_BLOQADM  | varchar(1)      | Bloqueio administrativo (S/N)|
| RA_TIPOCON  | varchar(1)      | Tipo de contratação          |
| RA_YSUPERV  | varchar(40)     | Usuário supervisor           |
| RA_YEMAILS  | varchar(60)     | Email supervisor             |
| RA_YCARTAL  | varchar(16)     | Cartão alimentação           |
| RA_YCARTCO  | varchar(16)     | Cartão convênio              |
| RA_YMOTADM  | varchar(2)      | Motivo administrativo       |
| RA_YDESCVT  | varchar(1)      | Desconto VT (S/N)            |
| RA_DESCEP   | varchar(1)      | Desconto CEP (S/N)           |
| RA_TIPOVIA  | varchar(1)      | Tipo de via                 |
| S_T_A_M_P_  | datetime        | Timestamp do registro         |
| I_N_S_D_T_  | datetime        | Data de inserção             |
| RA_DTENTRA  | varchar(8)      | Data de entrada             |
| RA_TIPINF   | varchar(1)      | Tipo de informação           |
| RA_DTREC    | varchar(8)      | Data de recebimento          |
| RA_USERLGI  | varchar(17)     | Usuário que logou            |
| RA_USERLGA  | varchar(17)     | Último usuário que alterou   |