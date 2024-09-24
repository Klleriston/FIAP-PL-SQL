# Gatilhos Mágicos - Exercendo a Automação

Este projeto implementa um sistema de automação inteligente para gerenciamento de tráfego, incluindo o controle de semáforos, registro de acidentes e envio de notificações de emergência. Utiliza um **Modelo Entidade-Relacionamento (MER)** para representar as principais entidades envolvidas.

## Modelo MER

O modelo de banco de dados inclui as seguintes tabelas:

- **tb_veiculos**: Armazena dados dos veículos monitorados.
- **tb_semaforo**: Gerencia o controle dos semáforos na cidade.
- **tb_padrao_trafego**: Registra padrões de tráfego em diferentes horários e locais.
- **tb_acidente**: Armazena detalhes de acidentes e suas características.
- **tb_notificacao_emergencia**: Armazena notificações de emergência geradas automaticamente em caso de acidentes.
- **tb_acidente_semaforo**: Relacionamento entre acidentes e semáforos afetados.
- **tb_acidente_veiculo**: Relacionamento entre acidentes e veículos envolvidos.
- **tb_padrao_trafego_veiculo**: Relacionamento entre veículos e padrões de tráfego.

## Funcionalidades Automatizadas

O sistema de automação inteligente realiza as seguintes atividades:

1. **Ajuste automático de semáforos com base no fluxo de tráfego:**
   - Otimiza o fluxo de veículos ajustando automaticamente os tempos dos semáforos conforme o tráfego.
   
2. **Envio automático de notificações de emergência em caso de acidente:**
   - Reduz o tempo de resposta dos serviços de emergência, enviando notificações automáticas quando um acidente é registrado.
   
3. **Atualização automática dos padrões de tráfego:**
   - Mantém os dados de tráfego atualizados periodicamente para análises em tempo real e melhor gestão do trânsito.
   
4. **Reposição automática de estoque de peças para manutenção de semáforos:**
   - Gera pedidos de reposição automaticamente para evitar que o estoque de peças fique crítico.

## Diagrama MER

O modelo de entidade-relacionamento pode ser visualizado no link abaixo:

[MER - dbdiagram.io](https://dbdiagram.io/d/Fiap-66f2d6cda0828f8aa6e96d94)

