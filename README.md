# 🧪 Prova Técnica – Desenvolvedor Java


## 🎯 Objetivo

Avaliar a capacidade de desenvolver uma API REST utilizando Java, com foco em estrutura de código, modelagem, domínio de boas práticas, uso de ferramentas e clareza de raciocínio.

---

## 💼 Desafio Técnico

Desenvolver uma API REST para gerenciamento de **pedidos de venda**.

### Funcionalidades obrigatórias

- Criar pedido com:
  - Cliente
  - Lista de itens (produto, quantidade, preço unitário)
  - Data do pedido
- A criação do pedido pode ser feita de forma assíncrona, utilizando uma fila para processar os pedidos (diferencial)
- Buscar pedido por ID
- Atualizar status do pedido (`PENDENTE`, `PAGO`, `CANCELADO`)
- Listar todos os pedidos (adicione filtro por status do pedido)
- Cancelar pedido
- Implementar auditoria simples (guardar data e usuário fictício que fez a última alteração no pedido)
- Listar vendas por cliente e calcular o total da soma de todos os pedidos do cliente com status (PAGO)
- Gerar relatório simples contendo:
  - Total de pedidos no sistema
  
  - Total de pedidos por status (PENDENTE, PAGO, CANCELADO)
  
  - Receita total acumulada dos pedidos PAGO

---

## 🔧 Requisitos Técnicos

Você deve utilizar obrigatoriamente:

- Java 17 **ou** Java 21  
- Spring Boot (qualquer versão compatível com Java 17 ou 21)  
- Persistência com JPA + banco de dados H2 ou Mongo DB
- Validações com Bean Validation  
- Mapeamento adequado entre entidades (Cliente, Pedido, ItemPedido, Produto)  
- Testes unitários (JUnit + Mockito)  
- Versionamento com Git (repositório público no GitHub)  
- README com instruções claras de execução  

---

## ✅ Entrega

Você deve entregar:

1. Repositório público no GitHub chamado `prova-java-pleno`  
2. Um `README.md` com:
   - Descrição do projeto  
   - Como rodar a aplicação (com `mvn` ou `gradle`)  
   - Exemplos de requisições (via curl, Postman, etc.)  
   - Quais funcionalidades foram implementadas  
   - Observações (se houver algo não concluído ou limitações)

---

## 🚫 Regras

- A prova é individual  
- O uso de frameworks e bibliotecas auxiliares é permitido, mas evite gerar código automático (ex: via ChatGPT)  
- A entrega deve ser feita no prazo combinado  
- Qualquer dúvida durante a execução, entre em contato com os avaliadores.

---

## 💡 Dica

Organize o projeto como se fosse para produção. Esperamos ver boas práticas como:

- Separação de camadas (`controller`, `service`, `repository`)  
- Uso correto de DTOs e entidades  
- Tratamento de erros e respostas adequadas da API  
- Código limpo e testável
