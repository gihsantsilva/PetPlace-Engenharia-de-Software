# Documento de Requisitos do Sistema PetPlace - Marketplace com Personalização Avançada

Este documento descreve o sistema PetPlace como um projeto de engenharia de software com foco em requisitos funcionais e não funcionais para um marketplace especializado em produtos e serviços veterinários.

---

## Índice
1. [Descrição do Projeto](#descrição-do-projeto)
2. [Objetivos e Escopo](#objetivos-e-escopo)
3. [Funcionalidades Principais](#funcionalidades-principais)
4. [Premissas e Restrições](#premissas-e-restrições)
5. [Características dos Usuários](#características-dos-usuários)
6. [Requisitos do Sistema](#requisitos-do-sistema)
7. [Estratégias de Desenvolvimento](#estratégias-de-desenvolvimento)
8. [Licenciamento e Conformidade Legal](#licenciamento-e-conformidade-legal)

---

## Descrição do Projeto
O **PetPlace** é um marketplace inovador, projetado para conectar tutores de pets, veterinários e fornecedores de produtos/serviços em uma plataforma integrada. Com personalização avançada por algoritmos de machine learning, o sistema oferece recomendações baseadas nas necessidades dos animais, garantindo uma experiência personalizada.

---

## Objetivos e Escopo
### Objetivos
- Oferecer um ambiente digital que facilite o acesso a produtos e serviços veterinários.
- Proporcionar uma experiência personalizada para tutores e profissionais, baseada no perfil de cada pet.
- Digitalizar processos tradicionais, como agendamentos, compras e consultas.

### Escopo
O sistema inclui funcionalidades como:
- Cadastro de usuários e pets.
- Algoritmos de recomendação personalizados.
- Gestão de compras, pedidos e agendamentos de serviços veterinários.
- Pagamento online e sistema de suporte.

---

## Funcionalidades Principais
### Funcionais
1. **Cadastro de Usuários e Pets**
   - Inclusão de informações como raça, idade e histórico de saúde.
2. **Algoritmo de Recomendação**
   - Sugestões de produtos e serviços baseadas em dados dos pets.
3. **Gestão de Compras**
   - Carrinho de compras, histórico de pedidos e integração com serviços de entrega.
4. **Agendamento de Serviços**
   - Agendamento e gerenciamento de consultas, exames e outros serviços veterinários.
5. **Pagamento Online**
   - Suporte a múltiplos métodos de pagamento, como cartão, débito e PIX.

### Não Funcionais
1. **Desempenho**
   - Tempo de resposta inferior a 2 segundos para interações comuns.
2. **Confiabilidade**
   - Arquitetura com alta disponibilidade, com 99,9% de uptime garantido.
3. **Usabilidade**
   - Interface responsiva e acessível conforme as diretrizes WCAG 2.1.

---

## Premissas e Restrições
### Premissas
- O sistema utilizará tecnologias amplamente adotadas para escalabilidade e manutenção.
- Algoritmos serão ajustados com base nos dados iniciais fornecidos.

### Restrições
- Conformidade com a LGPD e GDPR.
- Compatibilidade com dispositivos móveis e desktop.

---

## Características dos Usuários
Os usuários se dividem em três grupos:
1. **Tutores de Pets**
   - Necessitam de uma interface intuitiva para cadastro e gestão de informações dos pets.
2. **Veterinários**
   - Buscam funcionalidades para gerenciar consultas, prescrições e histórico de saúde.
3. **Fornecedores**
   - Precisam cadastrar e gerenciar produtos/serviços.

---

## Requisitos do Sistema
### Funcionais
- **RF01:** Cadastro de usuários e pets.
- **RF02:** Gestão de catálogo de produtos/serviços.
- **RF03:** Algoritmo de recomendação.
- **RF04:** Sistema de agendamentos.

### Não Funcionais
- **RNF01:** Desempenho ágil e responsivo.
- **RNF02:** Escalabilidade horizontal e modularidade.

---

## Estratégias de Desenvolvimento
1. **Frameworks Utilizados**
   - Frontend: React ou Angular.
   - Backend: Node.js ou Python (Django/Flask).
   - Banco de dados: MySQL ou PostgreSQL.
2. **Arquitetura**
   - Baseada em microserviços, com integração por APIs RESTful.
3. **Segurança**
   - Criptografia TLS para comunicações.

---

## Licenciamento e Conformidade Legal
- Conformidade com **ISO/IEC 25000** para qualidade de software.
- Licenciamento explícito dos componentes utilizados.
- Inclusão de Termos de Uso e Política de Privacidade.

---

### Próximos Passos
1. Refinar os casos de uso conforme prioridades do cliente.
2. Detalhar os diagramas de componentes e classes.
3. Validar protótipos com os stakeholders.

## Contribuidores

Agradeço as seguintes pessoas por contribuir para este projeto:

- [Murilo Faveri](https://github.com/MuhFaveri)
- [nogueirahyper](https://github.com/nogueirahyper)
- [giovanimaia18](https://github.com/giovanimaia18)
