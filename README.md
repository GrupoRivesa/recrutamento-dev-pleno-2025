## **Desafio Técnico: Sistema de Gestão de Máquinas JCB**

### **Contexto**
Sua equipe está evoluindo o sistema interno de uma empresa que gerencia uma frota de máquinas JCB usadas em obras (escavadeiras, retroescavadeiras, carregadeiras). O objetivo é desenvolver um **MVP** que permita o cadastro, visualização, edição e acompanhamento do status dessas máquinas e suas manutenções preventivas e corretivas.

---

### **Requisitos**

#### **Backend (Node.js)**
1. **API RESTful** para:
    - CRUD de máquinas (modelo, ano, status, horímetro, empresa, operador).
    - Cadastro e consulta de manutenções (vinculadas a máquinas).
2. **Relacionamento** entre máquinas e manutenções (1:N).
3. **Consulta** de máquinas com filtros (por status, empresa, operador ou modelo).
4. **Documentação da API** (Swagger/OpenAPI ou README detalhado).
5. **Versionamento de código** estruturado (Git, PRs sugeridos, uso de branches).
6. Estrutura de usuários e autenticação.

#### **Frontend**
1. Integração com a API para cadastrar, listar, editar e visualizar máquinas e manutenções.
2. Interface em **React**.
3. Listas e formulários claros.
4. **Fluxo**: “Dashboard” de máquinas, detalhes de máquina com lista de manutenções.

#### **Banco de Dados (SQL)**
1. Mapeamento relacional (máquinas x manutenções).
2. Queries otimizadas para filtros e busca.

#### **Automação e IA**
1. Implementar um endpoint que, baseado no **horímetro**, sugere quando uma máquina terá uma manutenção preventiva.
2. Implementar uma automação simples envolvendo alguma IA, como um endpoint que faz análise de texto de relatórios de manutenção e classifica como "grave/leve".

#### **Documentação**
- Diagrama simples do banco (pode ser imagem ou texto).
- README com **breve planejamento/decisões arquiteturais**.
- Ferramentas utilizadas.

---

### **Critérios de avaliação**
- Estrutura de código e clareza da organização do projeto.
- Uso adequado de banco relacional.
- Projeto de API RESTful bem definida.
- Otimização e limpeza nas queries SQL.
- Boas práticas de versionamento e documentação.
- Experiência mínima de frontend e integração.
- Planejamento apresentado no README.
- Implementação de automação/IA.
- Atenção à colaboração (nomes de branch, instruções de setup, pequenas dicas para júnior no código ou doc).

---

### **Exemplo de Histórias de Usuário**
- Como gestor, quero cadastrar uma nova máquina e vincular operador e empresa.
- Como analista, desejo visualizar as manutenções de cada máquina para agendar preventivas.
- Como usuário, filtro máquinas por status e busco por modelo.

---

### **Orientações Gerais**
- Pode rodar localmente apenas (não precisa deploy ou testes automatizados).
- Responsividade pode ser simples, priorize o fluxo de uso.
- Use SQLite, Postgres, MySQL, etc. (preferencialmente Open Source).

---

Deixe um ou dois comentários/exemplos no repositório demonstrando como você orientaria um colega júnior em um ponto crítico do projeto.

---
