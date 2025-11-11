# Relatório de Comparação de Bases

## CAMPOS QUE NÃO TEM CORRESPONDENCIA E SÃO CRITICOS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (AN) **Cidade Fornecedor** | N/A | Sem Contrapartida |
| (BE) **Descricao_cabine_trecho_unico_final** | N/A | Sem Contrapartida |
| (BL) **CidadeAeroportoDestino_completo** | (M) **Rota Completa/Cidades** | Correspondência Encontrada |
| (BR) **TOTAL** | N/A | Sem Contrapartida |

## CAMPOS QUE NÃO TEM CORRESPONDENCIA MAS PODEM SER NECESSÁRIOS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (G) **CNPJ** | N/A | Sem Contrapartida |
| (L) **Grupo Empresarial** | N/A | Sem Contrapartida |
| (N) **Produto_Aéreo** | N/A | Sem Contrapartida |
| (O) **Produto_Hotel** | N/A | Sem Contrapartida |
| (P) **Produto_Carro** | N/A | Sem Contrapartida |
| (AA) **Rede** | N/A | Sem Contrapartida |
| (AM) **Motivo** | N/A | Sem Contrapartida |
| (BK) **CidadeAeroportoOrigem_completo** | N/A | Sem Contrapartida |

## CAMPOS QUE TEM CORRESPONDENCIAS MAS OS DADOS ESTÃO COM BAIXA QUALIDADE

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (AP) **Local Retirada** | (N) **Local Retirada** | Correspondência Encontrada |
| (AQ) **Local Devolução** | (O) **Local Devolução** | Correspondência Encontrada |


## CAMPOS QUE TEM CORRESPONDENCIA MAS REQUEREM TRATATIVAS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (M) **Produto** | (L) **Produto** | Correspondência Encontrada |
| (AY) **Destino** | (L) **Produto** | Correspondência Encontrada |

## CAMPOS COM CORRESPONDENCIAS VIÁVEIS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (A) **Pedido** | (C) **Autorizador** | Correspondência Encontrada |
| (D) **Bilhete / Voucher** | (J) **Nº Confirmação** | Correspondência Encontrada |
| (H) **Data embarque / checkin** | (H) **Data Início do Serviço** | Correspondência Encontrada |
| (I) **Desembarque / Check out** | (I) **Data Término do Serviço** | Correspondência Encontrada |
| (J) **VALOR_DIARIA** | (R) **Valor Diária [Apartamento/Locação 1]** | Correspondência Encontrada |
| (K) **Cliente** | (B) **Cliente** | Correspondência Encontrada |
| (Y) **Fornecedor** | (G) **Fornecedor do Serviço** | Correspondência Encontrada |
| (AD) **Centro de custo** | (D) **C.Custo Cliente (Descrição)** | Correspondência Encontrada |
| (AF) **Forma de pagamento** | (P) **Forma [Pagamento 1]** | Correspondência Encontrada |
| (AG) **Passageiro** | (F) **Passageiro (Nome Completo)** | Correspondência Encontrada |
| (AI) **Solicitante** | (E) **Solicitante** | Correspondência Encontrada |
| (BM) **QTD_DIARIA** | (S) **Qt. Diárias** | Correspondência Encontrada |
| (BN) **TAXAS** | (V) **Tx.Embarque** | Correspondência Encontrada |
| (BO) **TX_SERVICO** | (W) **Taxa de Serviço Total** | Correspondência Encontrada |
| (BP) **OUTRAS TAXAS** | (U) **Tx.Extra** | Correspondência Encontrada |
| (BQ) **TARIFA** | (T) **Tarifa [R$] Cliente** | Correspondência Encontrada |
| (BS) **EXTRAS** | (X) **Tx.Assento (Cliente) [Taxas]** | Correspondência Encontrada |

## CAMPOS QUE NÃO TEM CORRESPONDENCIA PORÉM NÃO SÃO NECESSÁRIOS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (B) **CHAVE_TRANSACAO** | N/A | Sem Contrapartida |
| (C) **RLOC** | N/A | Sem Contrapartida |
| (E) **Assento Conforto** | N/A | Sem Contrapartida |
| (F) **BKO** | N/A | Sem Contrapartida |
| (Q) **Ano** | N/A | Sem Contrapartida |
| (R) **Ano/Mes** | N/A | Sem Contrapartida |
| (S) **Quarter** | N/A | Sem Contrapartida |
| (T) **Mês Emissão** | N/A | Sem Contrapartida |
| (U) **Dia Emissão** | N/A | Sem Contrapartida |
| (V) **Mês_ANO** | N/A | Sem Contrapartida |
| (W) **Dia da Semana** | N/A | Sem Contrapartida |
| (X) **Data Emissão** | N/A | Sem Contrapartida |
| (Z) **FORNECEDOR_CIDADE** | N/A | Sem Contrapartida |
| (AB) **Antecedencia** | N/A | Sem Contrapartida |
| (AC) **Antecedencia Criação Pedido** | N/A | Sem Contrapartida |
| (AE) **Descrição Centro de Custo** | N/A | Sem Contrapartida |
| (AJ) **Aprovador** | N/A | Sem Contrapartida |
| (AK) **APROVADOR 2** | N/A | Sem Contrapartida |
| (AL) **Origem Pedido** | N/A | Sem Contrapartida |
| (AO) **Estado Fornecedor** | N/A | Sem Contrapartida |
| (AR) **Tipo Apto** | N/A | Sem Contrapartida |
| (AS) **Milhas** | N/A | Sem Contrapartida |
| (AT) **Projeto** | N/A | Sem Contrapartida |
| (AU) **Rota / Período** | N/A | Sem Contrapartida |
| (AV) **Status Reserva** | N/A | Sem Contrapartida |
| (AW) **Source** | N/A | Sem Contrapartida |
| (AX) **Operação** | N/A | Sem Contrapartida |
| (AZ) **Conciliado?** | N/A | Sem Contrapartida |
| (BA) **NR_TRANSACAO** | N/A | Sem Contrapartida |
| (BB) **Promotor** | N/A | Sem Contrapartida |
| (BC) **AGENTE_EMISSAO** | N/A | Sem Contrapartida |
| (BD) **cabinetrecho_unico_final** | N/A | Sem Contrapartida |
| (BF) **Just Menor Tarifa** | N/A | Sem Contrapartida |
| (BG) **Just. Antecedecia** | N/A | Sem Contrapartida |
| (BH) **Eventos** | N/A | Sem Contrapartida |
| (BI) **AeroportoNomeOrigem_completo** | N/A | Sem Contrapartida |
| (BJ) **AeroportoNomeDestino_completo** | N/A | Sem Contrapartida |
| (BT) **TARIFA_MINIMA** | N/A | Sem Contrapartida |
| (BU) **TARIFA_MINIMA1** | N/A | Sem Contrapartida |
| (BV) **SAVING** | N/A | Sem Contrapartida |
| (BW) **LOST** | N/A | Sem Contrapartida |
| (BX) **Saving Lost** | N/A | Sem Contrapartida |
| (BY) **TARIFA_CHEIA** | N/A | Sem Contrapartida |
| (BZ) **ECONOMIA** | N/A | Sem Contrapartida |
| (CA) **ECONOMIA_NAO_ATINGID** | N/A | Sem Contrapartida |
| (CB) **TarifaAcordo** | N/A | Sem Contrapartida |
| (CC) **TarifaPromocional** | N/A | Sem Contrapartida |
| (CD) **Online x Offline** | N/A | Sem Contrapartida |
| (CE) **Política de Antecedência** | N/A | Sem Contrapartida |
| (CF) **Média Antecedência** | N/A | Sem Contrapartida |
| (CG) **Política de Menor Tarifa** | N/A | Sem Contrapartida |
| (CH) **Divisão** | N/A | Sem Contrapartida |
| (CI) **Produto Outros** | N/A | Sem Contrapartida |
| (CJ) **Tipo de Serviço** | N/A | Sem Contrapartida |
| (CK) **Diretoria** | N/A | Sem Contrapartida |
| (CL) **Observações** | N/A | Sem Contrapartida |

## CAMPOS QUE POSSUEM UMA PROVAVEL CORRESPONDENCIA MAS NÃO SÃO NECESSÁRIOS

| Coluna Modelo Auditado | Coluna Modelo em Análise | Status |
| :--- | :--- | :--- |
| (AH) **Matricula** | (Q) **Cód. Autorização Cartão [Recebimento 1]** | Correspondência Encontrada |




