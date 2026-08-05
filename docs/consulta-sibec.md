# Como consultar o SIBEC e extrair o motivo do bloqueio/cancelamento

O SIBEC (Sistema de Benefícios ao Cidadão), operado pela CAIXA como agente operador do Programa Bolsa Família, é a fonte mais direta para identificar **por que** um benefício está bloqueado, suspenso ou cancelado — informação indispensável para instruir a maioria dos cenários deste playbook (ver a seção "Documentação mínima" de cada um).

Sem o motivo do SIBEC, a petição fica apoiada apenas na alegação do assistido; com ele, é possível apontar precisamente qual hipótese da Portaria MDS nº 897/2023 (ou norma correlata) foi aplicada pela Administração e refutá-la de forma específica.

## Acesso

- **URL do SIBEC:** https://www.beneficiossociais.caixa.gov.br/sibec2/sisgrSibec
- **Autenticação:** via https://login.caixa.gov.br, com credencial institucional (GERID/gov.br) habilitada para consulta a benefícios sociais. O acesso não é público — exige perfil autorizado.
- Consulta feita por **NIS** ou **CPF** do responsável familiar.

## O que extrair da tela de consulta

1. **Situação do benefício** (ativo, bloqueado, suspenso, cancelado) e a **data** do evento.
2. **Código e descrição do motivo** — é este campo que permite enquadrar o caso em uma das teses do playbook (ex.: "limite de unipessoais", "cadastro desatualizado há mais de 48 meses", "renda per capita acima do limite", "averiguação cadastral"). Comparar sempre o motivo apresentado com o rol do art. 6º, §3º, da Portaria MDS 897/2023 e com as demais hipóteses tratadas nos cenários deste repositório.
3. **Histórico de folhas de pagamento** (quando disponível), para determinar com precisão o mês do bloqueio/cessação — necessário para o pedido de retroativos (ver [cenário 11](../cenarios/11-atrasados-retroativos/README.md)).

## Registro nos autos

Salvar a tela de consulta como **print/PDF** e juntá-la à petição como documento de instrução — é o item "print da consulta SIBEC" citado na documentação mínima dos cenários de concessão e restabelecimento. Sempre que possível, extrair também o **código do motivo** em texto (não só a imagem), para citar literalmente na petição.

## Uso de ferramentas de leitura automatizada

Ferramentas de IA capazes de ler PDF e captura de tela (como o Claude Code) podem apoiar a extração do motivo do bloqueio a partir do print salvo, acelerando a triagem do caso — mas a leitura automatizada deve **sempre ser conferida** contra a tela original antes de ser citada em peça, seguindo a mesma regra de verificação aplicada a qualquer outra fonte primária neste playbook (nunca transcrever motivo, código ou data sem conferência).
