# Cultura do Scroll e Déficit de Atenção Escolar

> Análise de dados sobre a correlação entre **cultura do scroll** (uso intenso de redes sociais e vídeos) e o **déficit de atenção escolar** entre crianças e adolescentes brasileiros, com base na pesquisa **TIC Kids Online Brasil 2024** (Cetic.br).

O projeto segue o método **DEILAS**: **D**efinir objetivos · **E**scolher métricas · **I**dentificar fontes · **L**impar dados · **A**nalisar dados · **S**ugerir ações.

---

## Sumário

1. [Visão geral](#1-visão-geral)
2. [D – Definir objetivos](#2-d--definir-objetivos)
3. [E – Escolher métricas](#3-e--escolher-métricas)
4. [I – Identificar fontes](#4-i--identificar-fontes)
5. [L – Limpar dados](#5-l--limpar-dados)
6. [A – Analisar dados](#6-a--analisar-dados)
7. [S – Sugerir ações](#7-s--sugerir-ações)
8. [Limitações e cuidados](#8-limitações-e-cuidados)
9. [Próximos passos](#9-próximos-passos)
10. [Referências](#10-referências)

---

## 1. Visão geral

| Item | Descrição |
|---|---|
| **Tema** | A correlação entre cultura do scroll e o déficit de atenção escolar |
| **Tipo de projeto** | Análise de dados (exploratória, descritiva, nível agregado) |
| **Fonte principal** | TIC Kids Online Brasil 2024 (Cetic.br) |
| **Fontes alternativas** | PeNSE 2024 (IBGE) e PISA 2022 (OCDE/Inep) |
| **Público analisado** | Crianças e adolescentes de 9 a 17 anos |
| **Recortes** | Total, área (rural/urbana), região, classe social, sexo, faixa etária e escolaridade dos responsáveis |
| **Método** | DEILAS |

### Resumo do fluxo

```
D  Definir objetivos   →  5 perguntas de negócio
E  Escolher métricas   →  indicadores por pergunta
I  Identificar fontes  →  TIC Kids 2024 (+ PeNSE e PISA como alternativas)
L  Limpar dados        →  base padronizada, em %, com 20 recortes
A  Analisar dados      →  padrões entre grupos (associação, não causa)
S  Sugerir ações       →  recomendações para famílias, escolas e políticas
```

---

## 2. D – Definir objetivos

O projeto busca responder a cinco perguntas de negócio.

| # | Pergunta |
|---|---|
| **1** | O uso intenso de redes sociais está associado à perda de tempo dedicado às tarefas escolares e ao sono? |
| **2** | Quais grupos de estudantes apresentam maior dificuldade para controlar o próprio uso da internet? |
| **3** | O consumo frequente de plataformas de vídeos e redes sociais está associado a menor frequência de pesquisas escolares online? |
| **4** | A supervisão e orientação familiar estão associadas a menores indicadores de uso problemático da internet? |
| **5** | Quais desigualdades socioeconômicas estão associadas a padrões de uso intenso de redes sociais e dificuldades de autorregulação? |

---

## 3. E – Escolher métricas

Cada pergunta tem métricas, valor analítico e fonte definidos.

### Pergunta 1 – Uso de redes, tarefas escolares e sono
- **Métricas:** frequência de uso das redes; % que relata prejuízo nas tarefas escolares, no sono ou na convivência; associação entre indicadores.
- **Valor analítico:** identificar padrões de uso problemático e grupos prioritários para prevenção.
- **Fonte:** TIC Kids Online Brasil 2024, indicadores **B2** e **G17**.

### Pergunta 2 – Grupos com maior dificuldade de controle
- **Métricas:** % que tentou reduzir o uso sem conseguir; % que navega sem interesse; diferenças por idade, região e classe social.
- **Valor analítico:** identificar populações mais vulneráveis e orientar ações de educação digital.
- **Fonte:** TIC Kids Online Brasil 2024, **G17** e microdados.

### Pergunta 3 – Vídeos, redes sociais e pesquisas escolares
- **Métricas:** frequência de uso de redes e vídeos; frequência de pesquisas para trabalhos escolares; diferenças entre grupos e associação estatística.
- **Valor analítico:** investigar se hábitos de entretenimento digital coexistem com menor uso educacional da internet.
- **Fonte:** TIC Kids Online Brasil 2024, **B2** e microdados.

### Pergunta 4 – Mediação familiar
- **Métricas:** indicadores de mediação familiar; % com dificuldade de reduzir o uso; diferenças entre grupos comparáveis.
- **Valor analítico:** avaliar onde estratégias de orientação familiar podem ser mais necessárias.
- **Fonte:** TIC Kids Online Brasil, microdados de crianças e responsáveis (verificar a compatibilidade das variáveis).

### Pergunta 5 – Desigualdades socioeconômicas
- **Métricas:** frequência de uso por classe social e região; % com indicadores de uso problemático; diferenças e razões entre grupos.
- **Valor analítico:** orientar políticas de inclusão e bem-estar digital **sem presumir que acesso à internet seja prejudicial**.
- **Fonte:** TIC Kids Online Brasil 2024, microdados.

---

## 4. I – Identificar fontes

### 4.1 Fonte principal: TIC Kids Online Brasil 2024

Pesquisa do **Cetic.br**. Documentos e tabelas de indicadores utilizados:

| Fonte | Uso no projeto |
|---|---|
| TIC Kids Online Brasil 2024 – Principais Resultados | Contexto e resultados gerais |
| TIC Kids Online Brasil 2024 – Resumo Executivo | Contexto e resultados gerais |
| Tabela **G17** | Uso excessivo e dificuldade de controle |
| Tabela **B2** | Atividades online, redes, vídeos e pesquisa escolar |
| Tabela **C7** | Mediação dos responsáveis |
| Tabela **E3A** | Mediação, segundo os próprios jovens |

### 4.2 Fontes alternativas

A melhor combinação de fontes alternativas é a **PeNSE 2024** (base principal) e o **PISA 2022** (atenção e desempenho). Nenhuma das duas mede "uso problemático da internet" tão diretamente quanto a TIC Kids, então as perguntas 2 e 3 dependem de **indicadores aproximados (proxies)**.

| Fonte | Descrição |
|---|---|
| **PeNSE 2024 (IBGE)** | Inquérito autoaplicável e anônimo com 12.359.709 escolares de 13 a 17 anos, de escolas públicas e privadas. Resultados por Brasil, Grandes Regiões, UFs e capitais, divulgados em 25/03/2026. Microdados no portal do IBGE. |
| **PISA 2022 (OCDE/Inep)** | Estudantes de 15 anos; no Brasil, 10.798 alunos de 599 escolas. Traz questionário sobre uso de dispositivos digitais e distração em aula, além de notas em matemática, leitura e ciências. |

### 4.3 Cobertura das 5 perguntas pelas fontes alternativas

| # | Pergunta | Fonte | Métricas disponíveis | Cobertura |
|---|---|---|---|---|
| 1 | Redes sociais, tarefas escolares e sono | PISA 2022 + PeNSE 2024 | PISA: horas por dia em dispositivos digitais, distração em aulas de matemática, nota em matemática. PeNSE: tempo de comportamento sedentário e indicadores de saúde mental (tristeza, preocupação). | Parcial |
| 2 | Grupos com maior dificuldade de controle | PISA 2022 | Distração por dispositivo próprio e de colegas; desligar notificações ao dormir; recortes por sexo, tipo de escola e nível socioeconômico. | Parcial (proxy) |
| 3 | Vídeos e redes sociais × pesquisas escolares | PISA 2022 | Horas de uso de dispositivos para lazer em comparação com uso para aprendizagem na escola. | Parcial |
| 4 | Mediação familiar e uso problemático | PeNSE 2024 | % de escolares que sentem que os pais entendem seus problemas e preocupações (63,4% em 2024; 66,6% em 2019), cruzado com saúde mental e tempo de tela. | Parcial (proxy) |
| 5 | Desigualdades socioeconômicas | PeNSE 2024 + PISA 2022 | Recortes por sexo, idade, rede pública ou privada, região, UF, escolaridade materna e posse de bens e serviços. | Boa nos recortes |

### 4.4 Limites das fontes alternativas
- O PISA mede só estudantes de 15 anos e não pergunta sobre tempo dedicado às tarefas escolares; a nota em matemática é usada como indicador de desempenho.
- PeNSE e PISA **não se cruzam por aluno**: a comparação fica no nível agregado (região, tipo de escola, sexo).
- Os dois são levantamentos de corte transversal: mostram **associação, não causa**.
- No relatório do PISA 2022, alunos que se distraem com dispositivos de colegas em quase todas as aulas de matemática tiveram 15 pontos a menos na prova. Esse dado vem de reportagem sobre o relatório, **não do relatório da OCDE**, e deve ser confirmado na fonte.

---

## 5. L – Limpar dados

### 5.1 Processo

1. Ferramentas de IA foram usadas para **estruturar** os dados.
2. Os dados relevantes foram **selecionados manualmente**: uso de redes e vídeos, pesquisa escolar, uso excessivo, mediação dos pais e recortes por região, classe social, idade e sexo.
3. Foram **descartados** temas fora do escopo: compras online, contato com desconhecidos e discriminação.
4. **Padronização:**
   - células marcadas com `-` nas tabelas originais foram deixadas **vazias**;
   - todos os valores estão em **%**;
   - indicado **quem respondeu** (criança/adolescente ou responsável).
5. **Validação:** os valores do PDF foram comparados com as tabelas oficiais do Cetic.br.
6. Respostas de pais e filhos **não foram misturadas**, pois divergem (ver [Análise](#pergunta-4--mediação-familiar)).

### 5.2 Estrutura da base tratada

A base tem **20 linhas (recortes)** e uma coluna `recorte_tipo` + `recorte`:

| Tipo de recorte | Categorias |
|---|---|
| Total | Total |
| Área | Rural, Urbana |
| Região | Centro-Oeste, Nordeste, Norte, Sudeste, Sul |
| Classe social | AB, C, DE |
| Sexo | Feminino, Masculino |
| Faixa etária | 9 a 10, 11 a 12, 13 a 14, 15 a 17 anos |
| Escolaridade dos responsáveis | Até Fundamental I, Fundamental II, Médio ou mais |

### 5.3 Dicionário de variáveis (valores em %, salvo indicação)

**Uso de redes e vídeos**

| Variável | Significado |
|---|---|
| `redes_diario` | Usa redes sociais todos os dias |
| `redes_mais1x_dia` | Usa redes sociais mais de uma vez por dia |
| `videos_diario` | Assiste a vídeos todos os dias |
| `videos_mais1x_dia` | Assiste a vídeos mais de uma vez por dia |
| `jogos_diario` | Joga todos os dias |
| `interesse_diario` | Atividades de interesse/entretenimento diárias |

**Pesquisa escolar**

| Variável | Significado |
|---|---|
| `escolar_diario` | Pesquisa para trabalhos escolares todos os dias |
| `escolar_semanal_ou_mais` | Pesquisa pelo menos semanalmente |
| `escolar_nao_realiza` | Não realiza pesquisa escolar |

**Plataformas**

| Variável | Significado |
|---|---|
| `tiktok_frequente`, `tiktok_varias_dia` | Uso frequente / várias vezes ao dia de TikTok |
| `instagram_frequente`, `instagram_varias_dia` | Uso frequente / várias vezes ao dia de Instagram |
| `youtube_frequente`, `youtube_varias_dia` | Uso frequente / várias vezes ao dia de YouTube |
| `whatsapp_frequente`, `whatsapp_varias_dia` | Uso frequente / várias vezes ao dia de WhatsApp |

**Uso excessivo (G17)**

| Variável | Significado |
|---|---|
| `g17_comer_dormir` | Deixou de comer ou dormir por causa da internet |
| `g17_sentiu_mal` | Sentiu-se mal por não poder usar a internet |
| `g17_sem_interesse` | Navegou sem estar realmente interessado |
| `g17_menos_tempo_licao` | Passou menos tempo com família, amigos ou lição de casa |
| `g17_nao_conseguiu_reduzir` | Tentou passar menos tempo e não conseguiu |
| `g17_nenhuma` | Nenhuma das situações |
| `g17_ns_nr` | Não sabe / não respondeu |
| `g17_indice_medio_5itens` | Índice médio dos 5 itens de uso excessivo (derivado) |
| `g17_ao_menos_uma_aprox` | Aproximação do % com ao menos uma situação (derivado) |

**Mediação familiar**

| Variável | Significado |
|---|---|
| `med_olham_celular` | Responsáveis olham o celular do filho |
| `med_regras_celular` | Há regras para uso do celular |
| `med_deixam_sem_celular` | Deixam o filho sem celular (restrição) |
| `med_ensinam_seguranca` | Ensinam a usar a internet com segurança |
| `med_conversam` | Conversam sobre o que o filho faz na internet |
| `med_sentam_junto` | Sentam junto enquanto o filho usa |
| `med_restritiva_media` | Média dos indicadores de mediação restritiva (derivado) |
| `med_ativa_media` | Média dos indicadores de mediação ativa (derivado) |

**Indicadores derivados (diferenças em pontos percentuais)**

| Variável | Cálculo |
|---|---|
| `gap_videos_menos_escolar` | `videos_diario` − `escolar_diario` |
| `gap_redes_menos_escolar` | `redes_diario` − `escolar_diario` |

> Exemplo de conferência: Total → 67 − 52 = **15** pontos de diferença entre uso diário de redes e pesquisa escolar diária.

---

## 6. A – Analisar dados

> **Aviso:** a análise mostra **padrões entre grupos**, mas **não prova causalidade**.

### Pergunta 1 – Uso de redes, tarefas escolares e sono
- **67%** das crianças e adolescentes usam redes sociais todos os dias.
- Entre jovens de 11 a 17 anos, **22%** passaram menos tempo com família, amigos ou lição de casa por causa da internet, e **15%** deixaram de comer ou dormir.
- O impacto **cresce com a idade**: entre 15 e 17 anos, **30%** deixaram a lição ou a família de lado.
- Grupos de maior destaque: **meninas (29%)**, **região Sul (34%)** e filhos de responsáveis com **até Ensino Fundamental I (36%)**.

### Pergunta 2 – Grupos com mais dificuldade de controle
- **24%** tentaram passar menos tempo na internet e não conseguiram; **22%** navegaram sem estar realmente interessados.
- Maior dificuldade entre: adolescentes de **13 a 14 anos (29%)**, **meninas (28%)**, **região Sul (27%)** e **classe AB (40%, o dobro da classe DE)**.

### Pergunta 3 – Vídeos, redes sociais e pesquisa escolar
- Com a idade, crescem **tanto** o uso de redes e vídeos **quanto** a pesquisa para trabalhos escolares: o entretenimento convive com o uso para estudo.
- Porém, os grupos que **mais usam redes pesquisam menos** para a escola. No **Sul**, 73% usam redes todos os dias, mas só **40%** pesquisam para trabalhos escolares todos os dias.
- Diferença (redes diárias − pesquisa escolar diária), calculada na base:

| Recorte | Diferença (p.p.) |
|---|---|
| Região Sul | **33** (maior) |
| 15 a 17 anos | 27 |
| 13 a 14 anos | 28 |
| Total | 15 |
| Classe AB | **−11** (pesquisa escolar maior que uso de redes) |
| 9 a 10 anos | −4 |

### Pergunta 4 – Mediação familiar
- O controle dos pais **diminui com a idade**: as regras para uso do celular caem de **71% (9 a 10 anos)** para **27% (15 a 17 anos)**, justamente na idade em que o uso excessivo aumenta.
- Pais e filhos **respondem diferente**: **70%** dos pais dizem que conversam sobre o que o filho faz na internet, mas só **45%** dos filhos afirmam o mesmo. Por isso as respostas dos dois grupos **não foram misturadas**.

### Pergunta 5 – Desigualdades socioeconômicas
- O uso problemático aparece em **todas as classes**, de formas diferentes:
  - **Classe AB:** mais dificuldade de controlar o uso (**40%**).
  - **Classes C e DE:** mais perda de sono e de refeições (**16%**, contra **8%** na AB).
- A classe AB também é a que mais usa a internet para pesquisa escolar (**69%**, contra **45%** na DE): **mais acesso não significou mais prejuízo**.

---

## 7. S – Sugerir ações

> As recomendações abaixo são **propostas derivadas dos padrões encontrados** e devem ser validadas com os microdados antes de virarem decisões.

| Público | Achado de base | Ação sugerida |
|---|---|---|
| **Famílias** | Regras de celular caem de 71% para 27% entre 9–10 e 15–17 anos; 70% dos pais × 45% dos filhos sobre conversas | Manter regras e **diálogo** durante a adolescência, não só na infância; alinhar com os filhos o que é "conversar" sobre a internet |
| **Escolas** | Uso excessivo cresce com a idade; entretenimento convive com estudo | Educação digital com foco em **autorregulação**, começando antes dos 13 anos |
| **Grupos prioritários** | Meninas, região Sul, 13–14 anos, filhos de responsáveis com menor escolaridade | Direcionar campanhas e materiais de prevenção a esses grupos |
| **Classe AB** | Maior dificuldade de controle (40%) | Ações centradas em **hábitos e autocontrole**, não em acesso |
| **Classes C e DE** | Maior perda de sono e refeições (16%) | Ações centradas em **rotina, sono e alimentação**; orientação aos responsáveis |
| **Políticas públicas** | Mais acesso não significou mais prejuízo (AB × DE) | Políticas de inclusão digital **sem tratar o acesso como o problema**; foco em bem-estar digital |
| **Pesquisa** | Limitação a dados agregados | Usar os microdados para testar associações (ver próximos passos) |

---

## 8. Limitações e cuidados

- **Correlação ≠ causalidade.** Os dados mostram padrões entre grupos.
- **Dados agregados:** a base tratada traz percentuais por recorte, não respostas individuais.
- **Pais × filhos:** as respostas dos responsáveis e dos jovens divergem e **não devem ser misturadas**.
- **Compatibilidade de variáveis** (pergunta 4): verificar nos microdados de crianças e responsáveis.
- **Fontes alternativas:** PeNSE e PISA não se cruzam por aluno e só oferecem proxies para as perguntas 2, 3 e 4.
- **Faixa etária:** alguns indicadores de uso excessivo (G17) valem apenas para 11 a 17 anos; por isso há células vazias na base.

---

## 9. Próximos passos

1. Usar os **microdados** do TIC Kids Online Brasil para testar as associações com métodos estatísticos.
2. Verificar a **compatibilidade** das variáveis entre os microdados de crianças e de responsáveis.
3. Incorporar **PeNSE 2024** e **PISA 2022** para comparação em nível agregado (região, tipo de escola, sexo).
4. Confirmar na fonte original (OCDE) o dado de **15 pontos a menos** no PISA 2022.

---

## 10. Referências

- Cetic.br – TIC Kids Online Brasil 2024, tabela G17: https://cetic.br/pt/tics/kidsonline/2024/criancas/G17/
- Cetic.br – tabela B2: https://cetic.br/pt/tics/kidsonline/2024/criancas/B2/
- Cetic.br – tabela C7: https://cetic.br/pt/tics/kidsonline/2024/criancas/C7/
- Cetic.br – tabela E3A: https://cetic.br/pt/tics/kidsonline/2024/criancas/E3A/
- TIC Kids Online Brasil 2024 – Principais Resultados: https://cetic.br/media/analises/tic_kids_online_brasil_2024_principais_resultados.pdf
- TIC Kids Online Brasil 2024 – Resumo Executivo: https://cetic.br/media/docs/publicacoes/2/20250512154015/tic_kids_online_2024_resumo_executivo.pdf
- PeNSE 2024 (IBGE) e PISA 2022 (OCDE/Inep): ver seção [4.2](#42-fontes-alternativas)
