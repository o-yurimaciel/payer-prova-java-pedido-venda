# 🧪 Prova Técnica – Desenvolvedor Pleno (Java)


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
- Buscar pedido por ID
- Listar todos os pedidos
- Atualizar status do pedido (`PENDENTE`, `PAGO`, `CANCELADO`)
- Cancelar pedido
- Calcular e retornar o valor total do pedido

---

## 🔧 Requisitos Técnicos

Você deve utilizar obrigatoriamente:

- Java 17 **ou** Java 21  
- Spring Boot (qualquer versão compatível com Java 17 ou 21)  
- Persistência com JPA + banco de dados H2 ou Mongo DB(diferencial) 
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
