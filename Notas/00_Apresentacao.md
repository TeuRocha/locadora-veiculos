### Projeto: Sistema de Controle de Locadora VL (Atualizado)

**Descrição do Projeto:**

A Locadora VL contratou nossa empresa para desenvolver um sistema online de controle de locações de veículos. O objetivo principal do sistema é permitir a gestão digital de todos os processos, como cadastro, locação, pagamento e controle de veículos. Embora a locação seja 100% online, os atendentes continuam sendo necessários para garantir o atendimento presencial aos clientes quando necessário.

### Alterações e Ajustes Realizados:

#### **1. Atendentes Disponíveis:**
- **Processo Online e Presencial:** O cliente pode realizar todo o processo de locação online, mas, se o cliente for à loja, o atendente realizará a locação através do sistema online.
- **Priorização por Disponibilidade:** Os atendentes serão priorizados de acordo com a **disponibilidade**, e não mais pelo desempenho. Caso o cliente já tenha realizado locações anteriormente, o atendente que o atendeu será mantido para as próximas locações.
- **Clientes Fidelizados:** Para clientes que já alugaram múltiplas vezes, o atendente preferido será alocado automaticamente, mantendo a continuidade no atendimento.

#### **2. Descontos e Promoções (Ajustados):**
- **Desconto para Períodos Prolongados:**
  - Descontos adicionais para locações de maior duração (ex: 1 mês, 6 meses ou 1 ano).
  - O valor do desconto será maior conforme o número de dias ou meses que o cliente aluga.
  - **Novo Desconto Proposto:** 10% para locações mensais, 20% para locações superiores a 6 meses.
  
- **Desconto para Renovação:**
  - Caso o cliente tenha alugado um veículo no mês anterior com desconto, ele receberá **um novo desconto** de 5% sobre o valor da renovação, para incentivar a continuidade.
  - Para locações sucessivas, o cliente terá um "desconto de fidelidade" progressivo, aumentando conforme o número de meses consecutivos alugados.

- **Desconto TOP10 Clientes:** 
  - Clientes no **TOP10 de locações mensais** (considerando o valor total das locações) recebem um desconto adicional de **12,5%** em suas próximas locações.

- **Desconto de Aniversário:**
  - Clientes com **aniversário no mês** terão **upgrade de categoria**, ou um desconto de 5% no valor da locação.
  
- **Desconto para Fidelidade de Longo Prazo:**
  - Clientes que realizarem **5 ou mais locações no mesmo ano** ou que locarem por **mais de 6 meses consecutivos**, terão um **desconto adicional de 20%** em qualquer categoria (**para aquela locação**).

- 

#### **3. Escolha de Categoria de Veículo e Alternativas:**
- **Escolha de Categoria:**
  - Quando o cliente escolhe uma categoria de veículo no portal e a opção não está disponível, o sistema automaticamente:
    - **Mostra uma alternativa melhor** (upgrade) com um **desconto de 10%**, ou,
    - **Exibe uma categoria inferior** pelo preço normal.
  
- **Mudanças de Categoria no Caso de Não Disponibilidade:**
  - Caso o veículo solicitado não esteja disponível, o sistema informará ao cliente e automaticamente oferecerá uma alternativa de categoria, dando o cliente a opção de aceitar a alternativa superior com um desconto ou a inferior pelo preço regular.

#### **4. Validação de Documentos e Tempo de Validação:**
- **Validação Online de Documentos:**
  - O cliente fará a **validação dos documentos via OCR** diretamente no portal, durante o processo de locação.
  - O **tempo de validação** será monitorado, e caso o cliente demore mais de 30 minutos para completar a validação, o sistema alertará sobre o atraso, oferecendo uma opção de **contato com o atendente** via chat.

- **Opção de Pagamento:**
  - **Débito**: Agora, além do **Cartão de Crédito** e **PIX**, será possível pagar também via **Débito bancário**, oferecendo mais uma opção de pagamento para os clientes.

#### **5. Equipe do Pátio:**
- **Preparação de Veículos:**
  - O time do pátio receberá as locações feitas através do portal com pelo menos **4 horas de antecedência** para garantir que o veículo esteja pronto para retirada.
  - Caso o cliente faça a reserva com menos de 4 horas de antecedência, o sistema informará ao cliente que a retirada será feita no **proximo prazo** hábil.
  
- **Preparo Antecipado:** 
  - A equipe do pátio terá um **período justo para preparar o carro**, baseado na categoria escolhida, realizando verificação de documentos e inspeção do veículo.

#### **6. Acompanhamento de Locação e Status:**
- **Notificações de Status de Locação:**
  - O cliente será **notificado em tempo real** sobre o status de sua locação, desde a aprovação até a disponibilização do veículo para retirada.
  - Caso haja qualquer mudança no status do veículo (como problemas de disponibilidade), o cliente será informado automaticamente por email e SMS.

#### **7. Portal Exclusivo para Locações:**
- **Portal 100% Funcional:**
  - O portal será o único meio para realizar a locação, incluindo pagamento e escolha do veículo, tanto para clientes novos quanto para clientes fidelizados.
  - Quando o cliente chega à loja, o processo de retirada é simples: ele só precisará apresentar um documento de identificação e assinar a nota promissória (se pagamento foi via PIX).

---

### **Alterações Sujeridas**

- **Atendentes continuam no sistema**, mas atendem através do portal. Eles são priorizados pela **disponibilidade**, e clientes frequentes mantêm o mesmo atendente.
- **Descontos ajustados**, com foco em locações de longo prazo e renovação de locações, com bonificação para clientes que alugam mensalmente ou por muitos meses consecutivos.
- **Alternativas de categoria de veículos** oferecidas automaticamente quando o cliente escolher uma categoria indisponível.
- **Opção de pagamento por débito** adicionada, além de Cartão de Crédito e PIX.
- **Validação de documentos via OCR** com limite de tempo, com notificações para clientes sobre atrasos.
- **Equipe do pátio com 4 horas de antecedência** para garantir tempo suficiente para preparar o veículo.
