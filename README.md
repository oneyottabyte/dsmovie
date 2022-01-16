# dsmovie - Semana Spring React - Dev Superior.

<h1 id="descricao">
	<img src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/24/000000/external-readme-is-a-easy-to-build-a-developer-hub-that-adapts-to-the-user-logo-color-tal-revivo.png"/>
  Descrição
</h1>
Criando um projeto de um site de filmes, que mostra um catalogo de filmes com a opção de avaliação deles.

<h1 id="arquitetura">
<img src="https://img.icons8.com/office/30/000000/blueprint.png"/>
  Arquitetura do Projeto
</h1>


- Criar projetos backend e frontend
- Salvar os projeto no Github em monorepo
- Montar o visual estático do front end
- Implementar o back end
- Modelo de domínio
- Acesso a banco de dados
- Estruturar o back end no padrão camadas
- Criar endpoints da API REST
- Implantação na nuvem
- Integrar back end e front end
- Três pilares do React
  - Componentes
  - Props
  - Estado
- React Hooks
  - useState
  - useEffect
  - useParams
  - useNavigate
  
  
#### Modelo conceitual
![Image](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/dsmovie-dominio.png "Modelo conceitual")

#### Padrão camadas adotado

![Image](https://github.com/devsuperior/bds-assets/raw/main/sds/padrao-camadas.png "Padrão camadas")
 
- Criar repository
- Criar DTO
- Criar service
- Criar controller

#### Lógica:

1) Informar email, id do filme e valor da avaliação (1 a 5).

2) Recuperar usuário do banco de dados pelo email. Se o usuário não existir, insira no banco.

3) Salvar a avaliação do usuário para o dado filme.

4) Recalcular a avaliação média do filme e salvar no banco de dados.

![Image](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/dsmovie-objs.png "Padrão camadas")

### Passo: Validação no Postgres local

- Criar três perfis de projeto: test, dev, prod
- Gerar script SQL no perfil dev
- Testar projeto no banco Postgres local


<h1 id="tecnologias-dependencias">
<img height="30" src="https://img.icons8.com/fluency/50/000000/administrative-tools.png"/>
	Tecnologias e Dependências
</h1>

<a name = "tech_stack"></a>

- Java 11
- ReactJS
- SpringBoot(Web,JPA,H2,Maven)
- Bootstrap
- CSS
- Figma
- Heroku
- Netlify https://doriandsmovie.netlify.app/
- Axios
- Yarn
- Postgres

<h1 id="desenvolvedor">
<img height="30" src="https://img.icons8.com/color/48/000000/devpost.png"/>
  Desenvolvedor
</h1>

<table align="center">
     <td align="center"><a href="https://github.com/oneyottabyte"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/oneyottabyte" width="100px;" alt=""/><br /><sub><b>Dorian Vieira</b></sub></a><br /><a href="https://github.com/oneyottabyte" title="Dorian Vieira"></a></td>
</table>

## Agradecimentos
[DevSuperior - Escola de programação](https://devsuperior.com.br)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig)
[![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)](https://youtube.com/devsuperior)
