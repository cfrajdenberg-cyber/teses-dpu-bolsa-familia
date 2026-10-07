# Teses DPU — Bolsa Família

Playbook colaborativo de apoio à atuação de Defensores Públicos Federais em casos do Programa Bolsa Família (PBF) — concessão, restabelecimento, mora administrativa, entrevista domiciliar, fraude cadastral, cômputo do BPC na renda, e temas correlatos.

Produzido no 3º Ofício Cível da DPU/SP, no mesmo molde do [playbook de BPC/LOAS](https://github.com/jppicanco/teses-dpu/tree/main/areas/bpc-loas) já existente: cada cenário reúne tese, base legal, jurisprudência com texto oficial (sem paráfrase) e modelo de peça.

## Como usar

Cada cenário em [`cenarios/`](cenarios/) corresponde a uma situação fática recorrente. Identifique o cenário mais próximo do caso concreto e siga a tese, a base legal e os pedidos sugeridos — sempre conferindo o inteiro teor das decisões citadas antes de reproduzi-las em peça (nunca citar jurisprudência sem verificação primária).

| Cenário | Situação |
| --- | --- |
| [01 — Concessão unipessoal, fato anterior a 27/12/2024](cenarios/01-concessao-unipessoal-antes-27-12-2024/) | Trava de 16% prevista só em portaria; ilegalidade/irretroatividade (Tema 379 TNU *a contrario sensu*) |
| [02 — Concessão unipessoal, fato posterior a 27/12/2024](cenarios/02-concessao-unipessoal-depois-27-12-2024/) | Suspensão temporária da entrevista domiciliar até 01/07/2027; inconstitucionalidade incidental do art. 12-A |
| [03 — Restabelecimento por revisão cadastral](cenarios/03-restabelecimento-revisao-cadastral/) | Trava de 16% não se aplica a quem já era beneficiário |
| [04 — Restabelecimento por fraude no e-Social](cenarios/04-restabelecimento-fraude-esocial/) | Vínculo empregatício fraudulento cancela o benefício indevidamente; dano moral |
| [05 — Mora irrazoável na análise administrativa](cenarios/05-mora-irrazoavel/) | Pré-habilitação sem conclusão; parâmetros de 130/75 dias (Enunciado 119 CCR) |
| [06 — Extinção por falta de interesse de agir](cenarios/06-extincao-falta-interesse-agir/) | Sentença extintiva por entrevista domiciliar não realizada — reforma |
| [07 — Pessoa em situação de rua](cenarios/07-situacao-de-rua/) | Grupo excepcional à trava de 16%; dispensa de entrevista |
| [08 — Regra de Proteção (art. 6º, Lei 14.601/2023)](cenarios/08-regra-de-protecao/) | Renda per capita acima do limite; manutenção com 50% do benefício — **12 ou 24 meses conforme a data do enquadramento (Portaria MDS 1.084/2025)** |
| [09 — BPC computado na renda do PBF (pluripessoal)](cenarios/09-bpc-computado-renda-pbf-pluripessoal/) | Inconstitucionalidade do art. 4º, §2º, da Lei 14.601/2023 |
| [10 — PBF computado na renda para fins de BPC](cenarios/10-pbf-computado-renda-bpc-acordo-2-2026/) | Problema inverso do cenário 9; Acordo Extrajudicial MDS/INSS/AGU/DPU nº 2/2026 |
| [11 — Atrasados e retroativos](cenarios/11-atrasados-retroativos/) | Parcelas vencidas; teto administrativo x integralidade judicial |
| [12 — Legitimidade passiva da União e do Município](cenarios/12-legitimidade-passiva-uniao/) | Preliminar recorrente em praticamente todo processo |
| [13 — Contrarrazões](cenarios/13-contrarrazoes/) | Recurso da União/Município contra sentença favorável ao assistido |
| [14 — Descumprimento de tutela antecipada](cenarios/14-descumprimento-tutela-antecipada/) | Astreintes por não implantação do benefício no prazo |

## Estrutura do repositório

- **[`cenarios/`](cenarios/)** — os 14 cenários, cada um com tese, base legal, jurisprudência, pedidos e modelo de peça recomendado.
- **[`jurisprudencia/`](jurisprudencia/)** — banco de decisões favoráveis citadas nos cenários, uma por processo, com citação completa (processo, órgão, relator/juiz, data) e trechos literais de ementa/voto/dispositivo. Nunca paráfrase — sempre texto oficial, extraído por leitura direta do PDF.
- **[`modelos-ccr/`](modelos-ccr/)** — modelos institucionais em branco, curados pela CCR Cível da DPU: ofícios administrativos (`oficios/`) e petições padrão (`peticoes/`).
- **[`docs/`](docs/)** — orientações operacionais transversais (ex.: [como consultar o SIBEC](docs/consulta-sibec.md)).

## Regras de citação

- Sentença de juízo singular (1º grau) é **julgado**, nunca "precedente" ou "jurisprudência" — reservado a acórdãos de Turma Recursal, Tribunal ou TNU.
- Toda citação traz processo + órgão julgador + relator(a)/juiz(a) + data. Nunca citar sem essas informações.
- Evitar "pacífico", "uníssono", "consolidado" sem fonte primária específica — a jurisprudência sobre Bolsa Família ainda está em construção em vários pontos (ver especialmente o Tema 379 da TNU, cuja tese fixada é **favorável à legalidade** da trava de 16% a partir de dezembro/2024, e não à sua ilegalidade ampla — o voto que defendia a ilegalidade ampla foi vencido).
- Nenhum dado pessoal de assistido (CPF, endereço, contato) é incluído neste repositório. Nomes de partes em decisões judiciais são mantidos apenas quando fazem parte da citação oficial do julgado (prática normal de citação jurídica, autos públicos) — nunca em modelos de petição, que permanecem genéricos.

## Regras do Juizado Especial Federal

- **Honorários:** no JEF, o pedido de honorários só cabe nas **contrarrazões** a recurso inominado da parte contrária (art. 55 da Lei nº 9.099/95; Tema 1.002 do STF). Não incluir na petição inicial, na réplica, em manifestações nem em recurso inominado interposto pela DPU. Fora do rito dos Juizados, segue a regra geral do CPC.
- **Prazo em dobro:** no JEF, a peça não afirma prazo em dobro para a DPU, não cita o art. 186 do CPC e não abre capítulo de tempestividade apoiado em prazo em dobro. Réplica e manifestações não levam capítulo de tempestividade nem de prerrogativas.
- **Sobrestamento por tema pendente (Tema 1.472/STF):** reservado à hipótese em que a trava de 16% é o único obstáculo restante e a alternativa é a improcedência; não pedir enquanto houver tutela de urgência pendente ou providência que independe do tema (ex.: entrevista domiciliar ainda não realizada).
- Modelos e exemplos antigos que tragam pedido de honorários em primeiro grau ou “prazo em dobro” devem ter esses trechos retirados ao serem adaptados para o JEF.

## Regra de valor da causa

- **Regra geral** (art. 292, § 1º, do CPC — prestações vencidas e vincendas): soma de 12 (doze) parcelas vincendas (R$ 600,00 × 12 = R$ 7.200,00) **com** as parcelas vencidas/atrasados, quando houver. Aplica-se a qualquer pedido de concessão ou restabelecimento do benefício (cenários 1, 2, 3, 4, 6, 7, 8, 9, 10), pois há prestações futuras em discussão.
- **Exceção:** quando o assistido **já está recebendo** o benefício e o pedido se limita ao **pagamento de atrasados** — sem pedido de concessão/restabelecimento, logo sem vincendas em discussão (ver [cenário 11 — atrasados e retroativos](cenarios/11-atrasados-retroativos/)) —, o valor da causa é **só o montante dos atrasados**, sem somar as 12 parcelas vincendas.

## Fontes

Guia técnico de teses do 3º Ofício Cível da DPU/SP (atualizado conforme o Memorando Circular nº 8747849/2026-DPGU/CCRCIVEL), acervo de decisões favoráveis do 3º Ofício Cível, e o repositório oficial "Material Disponível — Bolsa Família" da CCR Cível da DPU (SharePoint institucional).

## Licença

[CC BY 4.0](LICENSE) — mesmo padrão do playbook de BPC/LOAS.
