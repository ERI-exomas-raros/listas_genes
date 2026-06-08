# Listas de genes no ambiente de análise Emedgene
Este repositório contém as listas de genes e seus níveis de evidência para doenças que podem ser encontradas nos ambientes de análise disponibilizados pela equipe de bioinformática do Instituto Nacional de Cardiologia para o projeto Exomas Raros.


A priorização de variantes é uma etapa fundamental na análise de dados de sequenciamento de exoma e genoma. Um único exoma pode conter dezenas de milhares de variantes, enquanto apenas uma pequena fração delas está relacionada ao fenótipo ou à condição clínica investigada. Nesse contexto, listas de genes representam uma estratégia eficiente para direcionar a análise para genes com associação conhecida a doenças humanas.

Este repositório reúne recursos curados de associação gene-doença utilizados para apoiar a priorização de variantes no âmbito da ação Exomas Raros. O objetivo é disponibilizar uma coleção transparente e periodicamente atualizada de evidências que possa ser incorporada a fluxos de interpretação de variantes para doenças que cursam com deficiência intelectual.

## O uso de listas de genes permite:

- Priorizar variantes em genes com relevância clínica conhecida;
- Reduzir o número de variantes candidatas que necessitam de revisão manual;
- Direcionar análises orientadas pelo fenótipo do paciente;
- Aumentar a consistência e a reprodutibilidade entre diferentes análises;
- Facilitar a identificação de achados diagnósticos;
- Possibilitar reanálises sistemáticas à medida que novos conhecimentos sobre pares genes-doenças são incorporados à literatura científica.


## Fontes de Dados

A criação de listas de genes do projeto Exomas Raros é baseada em pares genes-doença com relação clínica validada por iniciativas internacionais como GenCC (Gene Curation Coalition) e Panel APP do Genomics England. A restrição a genes com nível de evidência elevado visa garantir que os participantes da iniciativa receberão resultados pautados nas melhores evidências disponíveis na literatura e na clínica.

### GenCC (Gene Curation Coalition)

O GenCC reúne e harmoniza classificações de validade clínica de associações gene-doença produzidas por múltiplos grupos de curadoria especializados em todo o mundo. Seu objetivo é promover consistência na avaliação da evidência disponível e facilitar a utilização dessas informações em contextos clínicos e de pesquisa.

Website: [GenCC](https://thegencc.org/)

### Genomics England PanelApp

O PanelApp é uma plataforma de curadoria colaborativa e revisão especializada desenvolvida pela Genomics England. O recurso disponibiliza painéis diagnósticos de genes avaliados por especialistas e classificados conforme o nível de evidência para associação com doenças específicas.

Website: [PanelApp](https://panelapp.genomicsengland.co.uk/)

#### Conteúdo do Repositório
/data/genomics_england

Contém dados obtidos do PanelApp da Genomics England, incluindo:

Painéis diagnósticos curados;
Associações gene-painel;
Níveis de evidência atribuídos aos genes;
Metadados dos painéis e suas versões.

/data/gencc

Contém dados obtidos do GenCC, incluindo:

Associações gene-doença;
Classificações de validade clínica;
Instituições responsáveis pela curadoria;
Informações sobre doenças e fenótipos associados.

/project_gene_lists

Contém as listas de genes utilizadas e atualizadas no âmbito do projeto Exomas Raros. 

aggregated_gene_evidence.csv

Arquivo consolidado contendo informações agregadas das diferentes fontes de curadoria e das listas internas do projeto.


Os dados disponibilizados neste repositório podem ser utilizados em:

- Priorização de variantes em exomas e genomas;
- Fluxos de análise de doenças raras;
- Estudos de descoberta de genes;
- Reanálise de casos previamente negativos;
- Desenvolvimento de pipelines bioinformáticos;
- Integração com sistemas de interpretação clínica;
- Estudos de associação genótipo-fenótipo.

Embora listas de genes sejam ferramentas valiosas para direcionar análises, elas devem ser utilizadas em conjunto com outras evidências relevantes, incluindo informações fenotípicas, frequência populacional, segregação familiar, predições computacionais e evidências específicas da variante.



As informações disponibilizadas neste repositório têm como objetivo apoiar processos de priorização e investigação de variantes. A interpretação final deve seguir diretrizes reconhecidas internacionalmente e considerar todas as linhas de evidência disponíveis para cada caso.
