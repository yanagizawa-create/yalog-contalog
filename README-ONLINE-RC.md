# ContaLog v1.2.6 · Relatório Oficial / Online RC

## Novidade desta build
Inclui **Relatório Oficial de Inventário em Excel (.xlsx)**, disponível ao perfil MASTER na coluna de ações de cada inventário.

### Abas geradas
- **Resumo** — identificação do inventário, status, cliente/site, execução, acuracidade por item, acuracidade por quantidade, acuracidade de endereços, quantidades e controle de rodadas.
- **Endereços** — 100% da estrutura, status, vazio, divergência, rodadas e conclusão.
- **Itens** — posição analítica com sistema, 1ª/2ª/3ª contagens, responsáveis, datas, última contagem e diferença final.
- **Contagens** — histórico de cada lançamento realizado, inclusive endereços vazios.
- **Divergências** — somente itens cuja última contagem diverge do sistema.
- **Auditoria** — cópia sequencial do histórico de lançamentos para rastreabilidade.

## Uso
1. Acesse **Inventário** como MASTER.
2. Localize o inventário.
3. Clique em **📊 Relatório Excel**.
4. O arquivo será baixado no navegador.

## Observação
Esta build continua sendo **Online RC com persistência local (localStorage)**. O relatório registra o estado e o histórico disponíveis no navegador no momento da exportação. A persistência central, autenticação e multiusuário serão implementados na etapa Supabase.
