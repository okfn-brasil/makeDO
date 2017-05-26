# makeDO
Make DiarioOficial, buscando uma plataforma plug-and-play baseada em wordpress

Estamos estudando... A **proposta metodológica** por hora é:

 1. Criar perfil padronizado da organização-usuário, com base em classificações básicas:
 
    1.1. Classificar a organização (tipicamente prefeituras mas podem ser outras inclusive ONGs).
    
    1.2. Classificar o "grau de maturidade em informática" da organização.

 2. Preparar *gradualmente* o portal da organização e sua equipe, para lidar com os requisitos mínimos:
 
    2.1. Ter suas leis, portarias, contratos, etc. no LexML, mesmo que apenas citando a página do PDF oficial.
    
    2.2. Ter identificadores por matéria (ID baseado em fascículo-contador), explicitando nas matérias que não apresentam identificação natural (leis e decretos apresentam ID natural, extratos de contrato e informes em geral não apresentam).
    
    2.3. Implementar recursos para a publicação (opcional) das matérias isoladas, e com identificadores consistentes na sua URL.
    
 3. Oferecer recursos mais sofisticados (pode ser um simples Wordpress) para a gestão dos conteúdos do DO, ou seja, implantar um CMS dedicado ao DO.
 
 4. Automatizar gradualmente o que for possível no CMS:
 
     4.1. no controle terminológico nos nomes de seção, nos títulos de matéria, nas assinaturas, etc.
     
     4.2. na geração do PDF caso ainda seja obrigatório (pode ser EPUB da matéria e/ou EPUB do fascículo).
   
   
# Subsídios aleatórios

* [LexML produzido por MEI, Oportunidades para trabalho com digitalização e adequação de documentos legislativos](https://docs.google.com/document/d/1Ll0anj85DV8r66whfBQgn0s183ZLHGc_lWJSSmt3h1U/).

* Wordpress, e cia: [CMSs](https://en.wikipedia.org/wiki/Content_management_system) mais simples e pupulares.

* [Padrão CSS-break](https://www.w3.org/TR/css-break-3/) para a geração de mídia paginada em HTML ou XML. HTML, EPUB, PDF, todos se beneficiam do novo padrão... E provavelmente EPUB substitua PDF.

* [A morte do XSL-FO](https://stackoverflow.com/a/21345708/287948) como padrão editorial. Não faz mais sentido ter uma cadeia de produço editorial fora do ecossistema de padrões abertos e HTML/XML/CSS.

* Exemplos de custo de mercado para as Prefeituras (não pode ser mais caro!). https://pressbooks.com/pricing/

