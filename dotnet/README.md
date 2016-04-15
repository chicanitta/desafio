# Desafio em .NET do Grupo Minha Vida: ASP.NET e Web API

## Necessidades

Neste projeto, temos a necessidade de criar um cadastro web de guitarras e uma Web API(opcional) que ofereça os dados das guitarras que foram cadastrados (não é necessária a edição via API, somente a lista de guitarras e o detalhe). As informações servidas pela API serão consumidas por cerca de 400 a 700 devices mobiles no mesmo momento. As áreas de negócio não necessitam que ao atualizar uma informação de um instrumento ela esteja atualizada em realtime para os devices que consomem a API (pode existir alguns minutos para que um preço ou informação seja atualizada na api).

Uma Guitarra possui algumas características como: nome (no máximo 400 caracteres), preço (R$), descrição, data de inclusão no cadastro, url da imagem(opcional) e SKU (campo calculado com base no identificador da guitarra no banco e o nome em minúsculo com os espaços substituído por "_", exemplo: Nome: "Fender Telecaster", Id: 213, terá como resultado o seguinte SKU: "213_fender_telecaster" ).

SGBD pode se utilizar o LocalDB.
Layout pode se utilizar o template padrão do ASP.NET MVC ou um de sua preferencia.

# Itens avaliados #

* Acesso a dados
* Validações
* Testes
* SOLID
* Tratamento de erros

## Submissão

Após concluir a implementação, ela deve ser enviada via Pull Request :)
