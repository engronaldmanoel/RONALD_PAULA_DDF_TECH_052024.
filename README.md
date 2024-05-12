# RONALD_PAULA_DDF_TECH_052024.
## Item 0 - Sobre Agilidade e Planejamento
Olá que todos estejam tendo um excelente dia! Bom aqui está o meu projeto técnico e logo abaixo se encontra um Gráfico de Gannt para gestão de tempo
e gerenciamento das tarefas.
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/d6fc5edd-f271-47d3-b63e-8474958fbea4" alt="matriz1" width="600px" />
</div>
Abaixo está a análise de riscos que eu desenvolvi para o projeto, os critérios analisados foram impacto x Probabilidade (Qualitativa), Para a análise de impacto o principal
efeito analisado seria a não entrega do teste técnico que se revelaria um grau crítico. Relacionando com a probabilidade de ocorrer esse evento é crítico foi analisado que seria
baixo pois já está sendo desenvolvido um método de gestão de tempo no qual mitiga boa parte de acontecer (Analogamente). Com isso o resultado foi:

<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/3a3be34f-6e94-4226-a60e-fd2bfbcad3be" alt="matriz1" width="500px" />
</div>
O próximo passo foi desenvolver a estimativa de custos da atividade desenvolvida, no qual a planilha com as fórmulas irei disponibilizar abaixo:</br>
- [Link para a planilha](https://docs.google.com/spreadsheets/d/1FbZAzuVXrVRpRlqQ-e2RbC344WLyGq6k/edit?usp=sharing&ouid=108988535045727431629&rtpof=true&sd=true) </br>

<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/597244d3-74b4-45f9-ba0c-e39f66dbf20a" alt="matriz1" width="500px" />
</div>
O custo total da atividade ficou em em volta de 926,36 Reais.
Para analisar a interdependência do projeto é interessante observar o gráfico de gannt no qual é entendível que uma tarefa depende da outra para se iniciar logo:
Com excessão da primeira atividade todas vão ser: Inicio-Início (II): Uma atividade não pode começar até que outra atividade relacionada também comece.

E o ponto crítico do projeto foi na etapa data quality no qual foi necessário pesquisar bastante sobre a biblioteca (Great Expectations) para garantir a confiabilidade dos dados. </br>

## Item 1 - Sobre a Base de Dados
Para esse item foi gerado uma base de dados com GPT 3.5, no qual os dados descrevem rotas na entrega de produtos para ecommerce o código completo se encontra acima no formato .ipynb.
Com isso
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/ef01970c-2e9d-4971-885d-7e20bd6e1042" alt="matriz1" width="500px" />
</div>

- [Link para o .csv](https://drive.google.com/file/d/1pLK30J7WmVv6RYyNFK1ZlGkH3TNqrs0_/view?usp=sharing) </br>
  
A base de dados possui mais de 100.000 entradas assim como solicitado. </br>
Abaixo se encontram variáveis do dataset no qual será utilizado para propor as melhoria de otimização.
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/345dcd3b-6568-45b3-805a-c2b1aafafb18" alt="matriz1" width="500px" />
</div>
Com isso é necessário se desenhar uma estratégia de como aplicar o modelo em produção e para isso segue o fluxograma abaixo no qual foi necessário se decidir algumas etapas para implementação do 
algoritmo random forest:
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/ddb7a449-9a76-401d-bf4c-1b85fe936bd1" alt="matriz1" width="500px" />
</div> </br>

## Item  2.1 - Sobre a Dadosfera - Integrar
O objetivo do modelo de Machine Learning (Random Forest) é obter previsões de menor tempo de entrega em horas dado novas informações colocadas ao modelo. E com isso implementar uma lógica no qual valorizem menor tempo e maior urgência.
## Item  3 - Sobre a Dadosfera - Explorar
## Item 4 - Sobre Data Quality
