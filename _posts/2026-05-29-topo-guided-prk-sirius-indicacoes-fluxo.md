---
title: "Topography-guided PRK com Sirius (CSO): indicações, fluxo e planejamento"
date: 2026-05-29 08:05:00 -0300
categories: [refrativa]
tags: [topo-guided, Sirius, CSO, PRK, astigmatismo irregular, Athens Protocol, refrativa, SCHWIND, AMARIS]
tipo: aula
tempo_leitura: "15 min"
---

## Caso clínico

Paciente masculino, 34 anos, retorna à consulta cinco anos após LASIK em OD para correção de −5,25 −1,00 × 15°. A queixa principal é diplopia monocular em OD, com halos e ghosting noturnos progressivos desde os 18 meses de pós-operatório. A AV sem correção é 20/30, com refração residual de −0,25 −0,50 × 20° que não melhora além de 20/25 com a melhor correção possível.

**Pentacam HR (OD):**
- Kmax: 41,2 D; K1: 39,8 D; K2: 41,0 D
- Elevação anterior máxima: +4 µm (BFS 8 mm) — dentro da normalidade
- Elevação posterior máxima: +6 µm — dentro da normalidade
- Paquimetria central: 487 µm; paquimetria mínima: 479 µm
- BAD-D: 1,4 (normal; limiar diagnóstico de ectasia: ≥ 1,6)
- ART-Max: 390 µm (normal; < 300 µm indica risco de ectasia)

**Corvis ST (OD):**
- SP-A1: 81 m/s (normal: > 70 m/s)
- CBI (Corvis Biomechanical Index): 0,05 (normal: < 0,5)
- TBI (Tomographic Biomechanical Index): 0,11 (normal: < 0,29)

**Topografia Sirius (OD):** mapa de curvatura tangencial mostra assimetria infero-nasal com ilha de aplanamento superior de 2,8 mm de diâmetro, indicando zona de ablação descentrada ~0,65 mm temporal em relação ao ápice corneal. Coma vertical Z(3,−1): +0,68 µm (6 mm); HOA total (RMS): 0,87 µm. Diferença de AV entre zonas de medição confirma origen corneal das queixas.

**Pergunta clínica:** como planejar o retratamento? Qual é o fluxo com Sirius e SCHWIND AMARIS? Que parâmetros definem o sucesso e os limites da ablação?

---

## Contexto e definição

Topography-guided (TG), ou ablação guiada por topografia, é a modalidade de cirurgia refrativa a laser que utiliza o mapa topográfico individual da córnea — e não apenas o erro refrativo esférico e cilíndrico — para calcular o perfil de ablação. Em vez de pressupor uma superfície corneal regular e ablacionar de forma simétrica, o sistema calcula uma ablação assimétrica ponto a ponto que transforma a córnea real em uma superfície-alvo matematicamente regular.

**Diferença fundamental em relação a wavefront-guided:**
- *Wavefront-guided:* guiada pelas aberrações ópticas totais do olho (corneais + internas + lenticulares), medidas por aberrômetro tipo Hartmann-Shack ou Tscherning.
- *Topo-guided:* guiada pela forma da córnea (topografia/elevação); corrige as irregularidades da superfície corneal sem levar em conta as aberrações internas do sistema óptico.

A indicação clínica define qual abordagem é superior: quando as aberrações são predominantemente de origem corneal (pós-LASIK com ablação descentrada, pós-ceratoplastia, pós-RK, ceratocone parcialmente regularizável), a TG é mais eficaz porque atua diretamente na fonte do problema. Quando as aberrações são de origem interna (cristaliniana, vítreo), a TG não oferece vantagem e pode ser contraproducente ao remover tecido corneal sem abordar a causa.

**O Sirius (CSO Italia)** é um topógrafo de dupla tecnologia — câmera Scheimpflug rotatória combinada com disco de Placido de 22 anéis. Gera simultaneamente:
- Mapas de curvatura axial, tangencial e de elevação (anterior e posterior) da córnea
- Mapas paquimétricos ponto a ponto
- Mapas de aberração corneana (Zernike até 7ª ordem)
- Câmera Scheimpflug do segmento anterior completo, incluindo câmara anterior, cristalino e ângulo iridocorneano

O Sirius oferece integração nativa com a plataforma de excímer laser **SCHWIND AMARIS** (750S e 1050RS) para exportação do mapa topográfico em formato proprietário CSO-SCHWIND, que o software de planejamento AMARIS converte diretamente em perfil de ablação topo-guided. Esse é o fluxo de referência para cirurgiões que utilizam ambos os equipamentos.

---

## Mecanismo / Princípio

### Ablação por "subtração de forma"

O conceito central é comparar a forma real da córnea com uma superfície-alvo ideal e calcular a diferença ponto a ponto. A superfície-alvo é construída a partir de dois componentes:

1. **Componente refrativo:** define a refração desejada (ex: plano, leve miopia residual para dominância), calculada a partir do erro refrativo pré-operatório e da zona óptica escolhida.
2. **Componente de regularização:** o algoritmo identifica os desvios locais da topografia real em relação a um esferoide regular com o mesmo equivalente esférico. A ablação adicional necessária para corrigir esses desvios é somada à ablação refrativa.

O perfil resultante é, na prática, uma ablação assimétrica: maior onde a córnea é mais íngreme do que o esperado para a superfície-alvo, menor (ou zero) onde está mais aplanada. O laser excímer (ArF, 193 nm) remove o tecido com precisão de ~0,25 µm por pulso, seguindo o mapa calculado.

### Por que a TG reduz aberrações de alta ordem

As HOA — predominantemente coma (Z3), trefoil (Z3) e aberração esférica (Z4) — surgem quando a superfície refratora (córnea) tem assimetrias locais. Uma ablação standard corrige a refração central mas não remove essas assimetrias. A TG, ao regularizar a forma corneal segundo o perfil calculado, redistribui a curvatura de forma que minimiza a diferença entre a frente de onda real e a ideal, reduzindo HOA diretamente.

Em olhos com coma de origem corneal — como no caso clínico apresentado, com ablação descentrada temporal —, a melhora pode ser dramática: reduções de HOA de 40–60% são descritas em séries de retratamento com TG-PRK.

---

## Avaliação / Diagnóstico pré-operatório

### 1. Qualidade topográfica — o fator limitante mais crítico

A qualidade do mapa topográfico determina diretamente a qualidade do perfil de ablação. Mapas contaminados por filme lacrimal irregular, artefatos de piscar, lentes de contato não removidas ou superfície ocular comprometida geram ablações irregulares — "garbage in, garbage out."

**Protocolo de aquisição no Sirius:**
- Remover lentes de contato gelatinosas por ≥ 1 semana antes da aquisição; lentes RGP por ≥ 3 semanas
- Instalar lubrificante sem conservante 5 minutos antes e solicitar piscar completo imediatamente antes da captura
- Adquirir ≥ 3 mapas consecutivos; aceitar apenas quando a diferença de Kmax entre os mapas for < 0,5 D
- No Sirius, o QS (Quality Score) deve ser ≥ 80 para o mapa ser válido para exportação topo-guided
- Olho seco severo é contraindicação relativa: otimizar superfície antes de qualquer aquisição de referência

### 2. Confirmar origem corneal das aberrações

Antes de indicar TG-PRK, confirmar que as HOA e os sintomas são de origem corneal e não interna:

- **Subtração topográfica:** comparar o mapa de curvatura do fronte de onda corneano (derivado do Sirius) com o aberrômetro total. Se a aberração corneana e a aberração total coincidirem em magnitude e direção, a origem é corneal — TG tem alta probabilidade de sucesso.
- **Teste da lente rígida de prova (hard contact lens override test):** se a AV melhora significativamente com lente rígida, as irregularidades são corneais e TG-guided é indicada.

### 3. Screening de ectasia — obrigatório

Nenhuma ablação corneal é segura em ectasia ativa ou subclínica não tratada.

**Protocolo integrado:**
- **Pentacam HR — BAD-D:** limiar ≥ 1,6 para suspeita de ectasia; limiar ≥ 3,0 como contraindicação formal a qualquer ablação sem CXL protetor. No caso clínico: BAD-D 1,4 (normal).
- **Pentacam HR — ART-Max:** < 300 µm associado a risco aumentado. No caso: 390 µm (normal).
- **Corvis ST — CBI:** > 0,5 indica biomecânica comprometida. No caso: 0,05 (normal).
- **TBI:** > 0,29 é limiar de atenção; > 0,5 indica alto risco. No caso: 0,11 (normal).
- **PTA (Percent Tissue Altered):** calculado como (espessura do flap + profundidade de ablação prevista) / paquimetria central. Valores > 40% associados a risco de ectasia pós-LASIK; no retratamento PRK, o cálculo é mais direto: RSB previsto = paquimetria atual − ablação total prevista.

### 4. Paquimetria e RSB

- **RSB (Residual Stromal Bed):** mínimo ≥ 250 µm para PRK (valor conservador de consenso).
- No retratamento de superfície, toda a ablação prevista — componente refrativo + componente de regularização — deve ser somada.
- No caso apresentado: paquimetria 487 µm. Se ablação prevista = ~40 µm de regularização + correção refrativa residual (~15 µm) + PTK epitelial (45 µm): total ~100 µm estimado. RSB = 487 − 100 = 387 µm. Adequado.

---

## Conduta / Técnica — Fluxo Sirius (CSO) + SCHWIND AMARIS

O fluxo padrão para TG-PRK com Sirius e AMARIS envolve cinco etapas sequenciais.

### Etapa 1: Aquisição topográfica validada

Conforme protocolo de qualidade descrito acima. Ao final, o mapa aceito (QS ≥ 80, δKmax < 0,5 D entre as 3 capturas) é designado como mapa "de referência" para planejamento.

### Etapa 2: Exportação do Sirius para AMARIS

No Sirius:
1. Selecionar o paciente → mapa de referência → botão de exportação topography-guided
2. Selecionar o destino: "SCHWIND AMARIS" (gera arquivo `.cso` ou formato XML proprietário CSO-SCHWIND)
3. Verificar que a lateralidade (OD/OE) está correta no cabeçalho do arquivo — erros de lateralidade são a causa mais comum de ablação espelhada

No AMARIS:
1. Importar o arquivo topográfico
2. Verificar a correspondência de dados: nome, data de captura, OU/OE, e que os mapas de curvatura aparecem visualmente coerentes com o mapa impresso do Sirius
3. Conferir o alinhamento do eixo de referência (vertex corneal vs. centro pupilar)

### Etapa 3: Planejamento da ablação

**3.1 — Definição da refração-alvo**

A refração-alvo é inserida manualmente. Para retratamento de erro residual:
- Utilizar a refração cicloplegiada mais recente, não a refração manifesta (que pode ser influenciada por aberrações)
- Em miopia alta com ametropia residual pequena, o componente de regularização já ocupa parte considerável da ablação — o residual refrativo pode ser corrigido dentro da mesma sessão, desde que o RSB permita

**3.2 — Seleção da zona óptica**

Em TG-PRK para regularização, a zona óptica mínima recomendada é 6,0 mm; 6,5 mm é preferível quando a paquimetria permite, pois evita criação de bordas abruptas na periferia da ablação (que podem gerar novas irregularidades ou halos). Zona óptica menor que 6,0 mm é aceitável apenas em casos de ablação extremamente conservadora para preservar estroma.

**3.3 — Análise do relatório de ablação**

O software AMARIS gera um relatório pré-cirúrgico com:
- **Mapa de ablação em µm:** visualiza a distribuição assimétrica da profundidade de ablação sobre a superfície corneal. Confirmar que o ponto de máxima ablação está sobre a região de maior irregularidade.
- **Profundidade máxima de ablação:** verificar que o RSB previsto é ≥ 250 µm em qualquer ponto do mapa, não apenas no centro.
- **Análise de coma pós-ablação prevista:** o software estima a HOA residual após a ablação. Um coma previsto < 0,3 µm (6 mm) indica boa probabilidade de sucesso clínico.

**3.4 — Centração: vertex corneal vs. centro pupilar**

Este é o ponto técnico mais crítico em TG-guided:

- O mapa topográfico é adquirido com referência ao **vertex corneal** (ponto de reflexão do anel central do Placido no ápice da córnea), não ao centro da pupila.
- Intraoperatório, o sistema de eye-tracking do AMARIS rastreia o **centro pupilar**.
- Se houver angle kappa (distância entre eixo visual e eixo pupilar) ou angle alpha relevante, o ponto de referência intraoperatório deve ser ajustado manualmente para coincidir com o vertex do mapa topográfico.
- No AMARIS, a ferramenta de "PRISM compensation" ou "vertex alignment" permite inserir o deslocamento entre vertex e pupila para que a ablação seja centrada corretamente.
- Erros de centração > 0,3 mm no retratamento TG podem criar novas irregularidades secundárias à ablação desalinhada.

### Etapa 4: Intraoperatório

**Remoção epitelial:**
- PRK convencional: álcool isopropílico 20% por 30 segundos, lavagem abundante, remoção com espátula.
- PRK transepitelial (se a plataforma AMARIS tiver o módulo Trans-PRK): remoção epitelial e ablação do estroma ocorrem em um único passo, sem contato com álcool. O perfil epitelial é calculado automaticamente pelo software com base na espessura epitelial média (padrão: 55 µm no centro, perfil de espessamento periférico).

**Centração intraoperatória:**
1. Marcar o limbo em dois meridianos com marcador de gentiana violeta antes da instilação de qualquer líquido
2. Posicionar o microscópio para que o reflexo pupilar e o vertex corneal sejam identificáveis no monitor
3. Se angle kappa relevante (> 0,3 mm): deslocar o ponto de rastreio conforme calculado no planejamento
4. Ativar o eye-tracker antes do primeiro pulso de laser

**Mitomicina C (MMC):**
- Indicação obrigatória em retratamentos PRK com ablação > 50 µm, paquimetria < 500 µm pré-op, ou casos com histórico de haze anterior.
- Protocolo padrão: esponja embebida em MMC 0,02% aplicada por 20–40 segundos sobre o leito estromal, seguida de lavagem copiosa com BSS.
- Em TG-PRK para ceratocone (Athens Protocol), incidência de haze é alta (66,7% em Dai 2024); MMC é mandatória com tempo de exposição de 30–45 segundos.

### Etapa 5: Pós-operatório

- Lente de contato terapêutica (LCT) descartável de baixa Dk por 4–5 dias até re-epitelização completa.
- Fluormetolona 0,1% 4×/dia por 30 dias, 3×/dia por mais 30 dias, 2×/dia por 30 dias — protocolo reduzido padrão para PRK sem ceratocone subjacente.
- Em casos com ceratocone associado ou suspeita de tendência a haze: fluormetolona estendida por 3–4 meses, com desmame lento.
- Lubrificação preservative-free intensa (mínimo 6×/dia) durante toda a fase de cicatrização.
- Revisões com topografia Sirius a 1, 3 e 6 meses para documentar regularização e estabilidade.

---

## Pontos de atenção

**1. Qualidade topográfica é o ponto crítico — e o mais frequentemente negligenciado**

Mapas de baixa qualidade geram ablações irregulares que agravam o quadro ao invés de melhorá-lo. O QS Score do Sirius deve ser verificado antes de qualquer exportação. Cirurgias com mapas de qualidade limítrofe devem ser adiadas para nova aquisição.

**2. Olho seco interfere na topografia e no resultado cirúrgico**

Disfunção de glândulas de Meibomius, tempo de ruptura lacrimal (TBUT) < 5 segundos ou osmolaridade lacrimal elevada produzem mapas instáveis e desfechos visuais piores no pós-operatório. Otimizar a superfície ocular antes da aquisição do mapa de referência e antes da cirurgia.

**3. A ablação TG é sempre maior que a ablação refrativa pura**

O componente de regularização adiciona tecido removido. Em olhos com paquimetria limítrofe pós-LASIK anterior, calcular RSB considerando a ablação total (regularização + refração + PTK epitelial), não apenas a ablação refrativa. O relatório AMARIS exibe o RSB previsto — verificar antes de liberar o planejamento.

**4. Angle kappa/alpha elevado exige ajuste manual**

Se a distância vertex corneal → centro pupilar for > 0,3–0,4 mm, o centramento padrão pelo eye-tracker (centrado na pupila) deslocará a ablação em relação ao mapa topográfico. Corrigir com a ferramenta de PRISM compensation no AMARIS antes de iniciar.

**5. HOA de origem interna não respondem a TG-PRK**

Se a subtração topográfica mostrar que a aberração total é maior que a aberração corneana, há contribuição interna relevante (lenticular, vítreo). Nesses casos, TG-PRK reduzirá parcialmente as HOA mas não eliminará os sintomas. Wavefront-guided ou tratamento da causa interna são mais adequados.

**6. Athens Protocol: ablação conservadora + CXL obrigatório**

Em ceratocone estável, a indicação do Athens Protocol (TG-PRK parcial + CXL simultâneo) requer:
- Ceratocone documentado como estável por ≥ 12 meses (Kmax variação < 1 D)
- Paquimetria pós-ablação prevista ≥ 400 µm para CXL Dresden epi-off (protocolo clássico), ou ≥ 325 µm para Epioxa epi-on (aprovado 2025)
- Ablação máxima de regularização limitada a 50 µm (não corrigir a refração total — apenas regularizar a superfície)
- CXL sem ablação adicional de regularização é insuficiente para ganho visual; TG-PRK sem CXL em ceratocone causa progressão acelerada

No estudo de Dai et al. (Frontiers in Medicine, 2024), N = 45 olhos com seguimento médio de 44 meses: TG-PRK + ACXL reduziu Kmax em 3,06 ± 2,68 D vs. 0,95 ± 1,58 D no grupo ACXL isolado (p = 0,008), com melhora significativa de BCVA e redução de HOA no grupo combinado (p < 0,001); nenhuma progressão identificada a longo prazo. Haze foi observado em 66,7% do grupo TG-PRK + ACXL, com regressão completa em todos os casos no seguimento final.

---

## Resolução do caso

O paciente apresenta ablação descentrada ~0,65 mm temporal com coma vertical dominante (Z(3,−1) +0,68 µm) sem ectasia (BAD-D 1,4; TBI 0,11; RSB previsto ≥ 387 µm). É um candidato ideal para TG-PRK de regularização.

**Plano:**
1. Otimizar superfície ocular por 4 semanas (TFOS DEWS II step 1-2): colírio lubrificante sem conservante 6×/dia + tampão lacrimal se hiposecreção
2. Re-adquirir 3 mapas Sirius com QS ≥ 80 e δKmax < 0,5 D — usar o mapa de melhor qualidade como referência
3. Exportar para SCHWIND AMARIS; planejar ablação com zona óptica 6,5 mm, refração-alvo plano, profundidade máxima prevista ≤ 45 µm de regularização + 15 µm residual refrativo + 45 µm PTK epitelial = ~105 µm total; RSB = 487 − 105 = 382 µm (adequado)
4. Verificar angle kappa: ajustar centração PRISM compensation se deslocamento vertex-pupila > 0,3 mm
5. PRK transepitelial ou com álcool 20%; MMC 0,02% por 30 segundos (ablação > 50 µm de tecido útil)
6. LCT + fluormetolona 0,1% por 3 meses desmame + lubrificação intensa
7. Topografia Sirius a 1, 3 e 6 meses; esperar redução de coma para < 0,35 µm e melhora subjetiva de halos e diplopia monocular

---

## Take-home

- TG-PRK é o tratamento de escolha para astigmatismo irregular de origem corneal com HOA predominantemente de coma — ablação descentrada pós-LASIK, pós-PK, pós-RK, ceratocone estável (com CXL simultâneo).
- A qualidade do mapa topográfico (QS ≥ 80 no Sirius, δKmax < 0,5 D entre capturas) é o fator limitante mais crítico — cirurgias com mapas de baixa qualidade devem ser adiadas.
- O fluxo Sirius (CSO) + SCHWIND AMARIS é nativo: exportação em formato CSO-SCHWIND, visualização de mapa de ablação, análise de RSB ponto a ponto e estimativa de HOA pós-ablação no planejamento pré-cirúrgico.
- A centração correta exige alinhamento entre o vertex corneal do mapa topográfico e o centro da ablação intraoperatório — o eye-tracker rastreia a pupila, não o vertex; corrigir com PRISM compensation quando angle kappa/alpha > 0,3 mm.
- RSB mínimo pós-ablação ≥ 250 µm em qualquer ponto do mapa; calcular sempre considerando a ablação total (regularização + refração + PTK epitelial).
- No Athens Protocol (ceratocone estável): ablação máxima 50 µm de regularização + CXL simultâneo obrigatório; paquimetria pós-ablação ≥ 400 µm para CXL epi-off Dresden ou ≥ 325 µm para Epioxa epi-on.
- HOA de origem interna (lenticular) não respondem a TG-PRK; confirmar origem corneal com subtração topográfica ou teste de lente rígida de prova antes de indicar.

---

## Referências

*Esta aula foi composta com base em conhecimento clínico consolidado e nas referências efetivamente acessadas e verificadas nesta execução. Parâmetros de instrumentação (Sirius QS Score, BAD-D, CBI, TBI, SP-A1) são valores de referência clínica de consenso das respectivas plataformas (Oculus Pentacam HR e Corvis ST; CSO Sirius).*

1. Dai Z, Chen Y. Topography-guided photorefractive keratectomy combined with accelerated corneal collagen cross-linking versus cross-linking alone for progressive keratoconus: a long-term prospective cohort study. Front Med. 2024;11:1420264. [https://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2024.1420264/full](https://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2024.1420264/full)

2. Jain R, Shuaib Y, Mohan N, Mittal V. Outcomes of topography-guided PRK/CXL in keratoconus using the NIDEK CXIII system — "Bharat Protocol" (pilot study). Indian J Ophthalmol. 2023;71(9):3203–3209. [https://pmc.ncbi.nlm.nih.gov/articles/PMC10565915/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10565915/)

3. Efficacy of Photorefractive Keratectomy vs. Topography-Guided Photorefractive Keratectomy for Refractive Errors and Aberrations Post-Penetrating Keratoplasty. J Clin Med. 2025. [https://pmc.ncbi.nlm.nih.gov/articles/PMC11856340/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11856340/)

4. Analysis of topographic corneal parameters in a large cohort of corneal refractive surgery candidates. Saudi J Ophthalmol. 2025. [https://pmc.ncbi.nlm.nih.gov/articles/PMC13082547/](https://pmc.ncbi.nlm.nih.gov/articles/PMC13082547/)
