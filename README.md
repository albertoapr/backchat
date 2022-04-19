# Backchat

Backchat é um site que permite armazenar o histórico das suas conversas do whatsap 
## Motivação
 - Whatsapp tem se tornado uma importante ferramenta de passagem de conhecimento entre equipes de trabalho;
 - Um novo membro do grupo não tem acesso às conversas anteriores ao momento da sua inclusão no grupo;
 - Necessidade de um membro sair do grupo e continuar como observador;
 - Perda do histórico de conversas quando se migra entre celulares de sistemas diferentes (iOS,Android);
 - Necessidade de consultar conversas antigas direto no aparelho uma vez que o whatsapp web disponibiliza as conversas mais recentes;
 - Perda de conversas que não foram salvas na nuvem no caso de perda do aparelho;
 - Falta de opção de selecionar as conversas que estarão no backup da nuvem ;
 - Obrigatoriedade de se utilizar a nuvem do sistema do celular para salvar o backup das conversas;
 - Possível falta de espaço para armazenar as conversas em nuvem;
 - Necessidade de pertencer ao grupo para vizualizar as conversas;
 - Possibilidade de usar uma ferramenta de indexação. Ex.: slack.
#### As operações disponíveis são:
- Importar arquivo da conversa;
- Seleção dos items da conversa;
- Consulta às conversas;
- Compartilhamento do histórico da conversa .
- Categorização de assuntos;

#### Além disso, o Backchat disponibiliza:
- Visualização gráfica dos principais conversas;
- Lista de conversas favoritas;


## Arquitetura

Completamente baseado em micro-serviços, o Backchat é composto dos seguintes componentes:
- Site Backchat: desenvolvido em VueJS e Java.


## Ambiente
O sistema é hospedado num servidor Jboss e banco de dados mysql.



