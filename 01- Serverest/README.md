#  Testes de API — Serverest

**Objetivo:** validar o fluxo utilizando a API pública [Serverest.dev](https://serverest.dev/), com automação em JavaScript dentro do Postman.

---

## Estrutura do Projeto
- **POST Criar Usuário + Login (Automatizado)** — cria usuário admin e autentica automaticamente.
- **GET Produtos** — lista produtos cadastrados.
- **POST Criar Produto** — cadastra novo produto com token.
- **DELETE Produto** — deleta produto criado.
  
> A Collection inclui scripts de automação que geram o token e o reaproveitam nas requisições seguintes.

---

##  Variáveis de Ambiente
- `BASE_URL` = `https://serverest.dev`
- `token` = é preenchido automaticamente no login

---

##  Scripts e Automação
**POST Criar Produto (Automatizado)** contém o script responsável por:
- Criar usuário administrador;
- Realizar login;
- Capturar e salvar o `token` globalmente;

---

##  Ferramentas Utilizadas
- **Postman** — criação e execução das requisições
- **JavaScript (scripts internos)** — automação dos testes e variáveis
- **Serverest API** — simula backend de e-commerce para testes
- **GitHub** — versionamento e portfólio público

---

##  Evidências
![Testes no Postman](./imgs/testeJs.png)


---

##  Como Executar
1. Importe a Collection (`Serverest.postman_collection.json`);
2. Importe o Environment (`Serverest.postman_environment.json`);
3. Selecione o Environment e execute a Collection no **Runner**.

---

##  Autoria
Desenvolvido por **Laura Oliveira**  
📂 GitHub: [@Lauraoliveiraqa](https://github.com/Lauraoliveiraqa)
