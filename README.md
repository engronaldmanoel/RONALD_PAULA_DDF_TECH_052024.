# RONALD_PAULA_DDF_TECH_052024.
- [Link para o vídeo no youtube](https://youtu.be/XrwcjtNjl3M) </br>

## Item 0 - Sobre Agilidade e Planejamento
Olá que todos estejam tendo um excelente dia! Bom aqui está o meu projeto técnico e logo abaixo se encontra um Gráfico de Gantt para gestão de tempo
e gerenciamento das tarefas.
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/23f20efc-be52-4b6b-b16b-e7da579d86f6" alt="matriz1" width="600px" />
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
Para analisar a interdependência do projeto é interessante observar o gráfico de gantt no qual é entendível que uma tarefa depende da outra para se iniciar logo:
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
Com isso é necessário se desenhar uma estratégia de como aplicar o modelo em produção e para isso segue o fluxograma abaixo que possui algumas etapas para implementação do 
algoritmo (Random Forest):
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/ddb7a449-9a76-401d-bf4c-1b85fe936bd1" alt="matriz1" width="500px" />
</div> </br>
O objetivo com o modelo de Machine Learning (Random Forest) é obter previsões de menor tempo de entrega em horas dado novas informações colocadas ao modelo. E com isso implementar uma lógica no qual valorizem menor tempo e maior urgência.

## Item  2.1 - Sobre a Dadosfera - Integrar
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/f264e4d4-dc91-4d3a-8859-ad11f4abb45e" alt="matriz1" width="500px" />
</div> </br>
- [Link para o pipeline dadosfera](https://app.dadosfera.ai/pt-BR/catalog/data-assets/66f4c806-3b85-4ccb-8308-104a85f88b1a) </br>

## Item  3 - Sobre a Dadosfera - Explorar </br>
Uma série de informações sobre o dataset pode ser retirada através da plataforma Dadosfera, abaixo se encontra links e prints de etapas no qual foi necessário fazer o uploud.
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/d3fceacc-2642-43d4-b897-15f3cda83cf6" alt="matriz1" width="500px" />
</div> </br>
- [Link para o pipeline dadosfera](https://app.dadosfera.ai/pt-BR/catalog/data-assets) </br>
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/183d36ef-aa1a-4010-a5a7-e8d1f2d19570" alt="matriz1" width="500px" />
</div> </br>
- [Link para o dashboard MetaBase](https://metabase-treinamentos.dadosfera.ai/auto/dashboard/table/582) </br>


## Item 4 - Sobre Data Quality
<div align="center">
    <img src="https://github.com/engronaldmanoel/RONALD_PAULA_DDF_TECH_052024./assets/100495133/cdc5a106-505c-4216-b17a-1edfd51c1da6" alt="matriz1" width="500px" />
</div> </br>

Vamos analisar o output:

- run_id: Identifica a execução, incluindo informações de tempo. </br>


- run_results: Contém os resultados das expectativas aplicadas aos dados. Cada expectativa tem um conjunto de resultados associados. </br>


- statistics: Fornece estatísticas gerais sobre as expectativas avaliadas, incluindo o número total de expectativas, quantas foram bem-sucedidas e a porcentagem de sucesso. </br>

- meta: Inclui informações adicionais sobre a execução, como a versão do Great Expectations utilizada, a suíte de expectativas, informações sobre os dados de entrada e detalhes temporais da execução. </br>


- checkpoint_config: Contém a configuração do checkpoint que foi executado. Um checkpoint é um conjunto de expectativas que são aplicadas regularmente aos dados para monitorar a qualidade dos mesmos ao longo do tempo. </br>


- success: Indica se a execução foi bem-sucedida ou não. Neste caso, parece que algumas expectativas falharam (success: false). </br>


Agora, vamos olhar mais de perto para as expectativas que falharam:

Expectativa: expect_column_values_to_not_be_null para a coluna "ID_Cliente".
Resultado: 19,822 valores nulos encontrados.
Expectativa: expect_column_values_to_not_be_null para a coluna "Preco_Unitario ($)".
Resultado: 10,033 valores nulos encontrados.
Estas falhas indicam que há valores nulos nessas colunas, o que pode afetar a qualidade e integridade dos dados. Essas expectativas são importantes para garantir que os dados estejam completos e prontos para análise ou processamento posterior.

Além dessas soluções específicas, é importante considerar a implementação de processos de monitoramento contínuo e de garantia de qualidade de dados para identificar e resolver problemas semelhantes no futuro. Isso pode incluir a configuração de pipelines de dados automatizados com testes regulares usando ferramentas como o Great Expectations, que ajudam a garantir a integridade e a qualidade dos dados ao longo do tempo.
