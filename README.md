# censo-ufs

## Table of Contents

### Migração dos bancos de dados SIGAA e ADMINISTRATIVO
Antes de iniciar o processamento dos dados relacionados ao censo, é necessário fazer uma migração dos dados do banco sigaa de produção ou espelho para um banco separado, que fica na porta *5804*.

Os bancos que são utilizados são:
  *  sigaa (10.200.10.11:5804) [banco sigaa dedicado ao censo, não sofre atualização. Só por demanda]
  *  administrativo (10.200.10.11:5402) [Espelho]

### 1ª Passo: executar a migração dos dados para o banco SQLite
  * Aqui é executado scripts no notebook Jupyter para gerar as tabelas r42 e r41
 

