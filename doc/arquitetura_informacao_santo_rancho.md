# ARQUITETURA DA INFORMAÇÃO DO SITE

## Santo Rancho Oliveira Moda Country Ltda.

**Documento de UX/UI Design --- Versão 1.0**

## 1. Visão geral da arquitetura

A arquitetura da informação do site da **Santo Rancho Oliveira Moda
Country Ltda.** será organizada para proporcionar uma navegação simples,
intuitiva e visualmente atrativa, valorizando a identidade country da
empresa e facilitando o acesso aos produtos e informações
institucionais.

A estrutura será pensada para atender homens, mulheres, crianças,
famílias, praticantes de esportes equestres e admiradores da cultura
sertaneja.

**Diretriz principal:** o visitante deverá conseguir conhecer a empresa,
explorar os produtos e entrar em contato com a loja com poucos cliques.

O projeto terá caráter institucional e comercial, sem funcionalidades de
pagamento ou finalização de compras na primeira versão.

## 2. Hierarquia das páginas

A estrutura principal será dividida em seis áreas:

1.  **Início:** apresentação da marca e destaques.
2.  **A empresa:** história, missão e valores.
3.  **Produtos:** catálogo organizado por categorias.
4.  **Galeria:** imagens da loja, produtos e cultura country.
5.  **Onde estamos:** localização e informações da loja.
6.  **Contato:** canais de atendimento e redes sociais.

## 3. Sitemap --- Mapa do site

O mapa abaixo apresenta a hierarquia das páginas e seus relacionamentos.

``` mermaid
flowchart TD
    A["SITE - SANTO RANCHO OLIVEIRA"]
    A --> B["Início"]
    A --> C["A Empresa"]
    A --> D["Produtos"]
    A --> E["Galeria"]
    A --> F["Onde Estamos"]
    A --> G["Contato"]
    C --> C1["Nossa História"]
    C --> C2["Missão e Valores"]
    D --> D1["Moda Masculina"]
    D --> D2["Moda Feminina"]
    D --> D3["Moda Infantil"]
    D --> D4["Botas e Calçados"]
    D --> D5["Acessórios Country"]
    D1 --> H["Detalhes do Produto"]
    D2 --> H
    D3 --> H
    D4 --> H
    D5 --> H
    B --> I["Destaques de Produtos"]
    B --> J["Apresentação da Marca"]
    B --> K["Chamada para Contato"]
    F --> F1["Endereço"]
    F --> F2["Mapa de Localização"]
    G --> G1["WhatsApp"]
    G --> G2["Redes Sociais"]
    G --> G3["Telefone e E-mail"]
```

*Observação: os detalhes de produtos serão apresentados em páginas
individuais, utilizando um mesmo modelo de layout.*

## 4. Definição dos menus e submenus

A navegação principal ficará no cabeçalho do site, com acesso às páginas
mais importantes.

### 4.1. Menu principal

-   Início
-   A Empresa
-   Produtos
-   Galeria
-   Onde Estamos
-   Contato

### 4.2. Submenus

  Menu           Submenus ou conteúdos
  -------------- ---------------------------------------------------
  Início         Apresentação e destaques
  A Empresa      Nossa história, missão e valores
  Produtos       Masculino, feminino, infantil, botas e acessórios
  Galeria        Loja, produtos e ambiente country
  Onde Estamos   Endereço e mapa
  Contato        WhatsApp, telefone, e-mail e redes sociais

**Comportamento esperado:** - No computador, o menu Produtos poderá
abrir um submenu suspenso. - No celular, o menu será apresentado em
formato lateral ou expansível. - O logotipo funcionará como atalho para
a página inicial. - O botão de WhatsApp ficará em posição de destaque.

## 5. Descrição de cada página

### 5.1. Página inicial (Home)

**Prioridade: Alta**

**Objetivo:** apresentar a empresa e despertar o interesse dos
visitantes.

**Conteúdo:** 1. Cabeçalho com logotipo e menu de navegação. 2. Banner
principal com fotografia da loja ou produtos country. 3. Frase
institucional destacando a identidade sertaneja. 4. Apresentação
resumida da empresa. 5. Destaques das categorias de produtos. 6.
Produtos em evidência. 7. Fotografias do ambiente da loja. 8. Chamada
para conhecer a empresa. 9. Botão de contato pelo WhatsApp. 10. Rodapé
com informações institucionais.

**CTAs principais:** - Conheça nossos produtos. - Saiba mais sobre
nós. - Fale conosco.

### 5.2. Página A Empresa

**Prioridade: Alta**

**Objetivo:** apresentar a identidade, história e valores da empresa.

**Conteúdo:** 1. Título: Nossa história. 2. História da Santo Rancho
Oliveira Moda Country Ltda. 3. Apresentação da trajetória da empresa. 4.
Missão institucional. 5. Visão da empresa. 6. Valores e princípios. 7.
Fotografias da loja e da equipe, quando disponíveis.

**CTAs principais:** - Conheça nossos produtos. - Entre em contato.

### 5.3. Página Produtos

**Prioridade: Alta**

**Objetivo:** permitir que os visitantes conheçam os produtos
comercializados e confeccionados pela empresa.

**Conteúdo:** 1. Banner de apresentação do catálogo. 2. Título: Nossa
linha de produtos. 3. Categorias organizadas visualmente. 4. Fotografias
dos produtos. 5. Nome e descrição dos produtos. 6. Botão para visualizar
detalhes.

**Subpáginas:**

#### Moda Masculina

Camisas, calças, camisetas e peças masculinas de estilo country.

#### Moda Feminina

Roupas, peças e combinações voltadas ao estilo country feminino.

#### Moda Infantil

Vestuário country para crianças.

#### Botas e Calçados

Botas e calçados de inspiração country.

#### Acessórios Country

Chapéus, cintos, fivelas e outros acessórios.

**CTAs principais:** - Ver produtos. - Consultar pelo WhatsApp. -
Conhecer outras categorias.

### 5.4. Página de detalhes do produto

**Objetivo:** apresentar informações específicas sobre cada produto.

**Conteúdo:** 1. Fotografias do produto. 2. Nome do produto. 3.
Descrição. 4. Características. 5. Informações de tamanho e cores, quando
disponíveis. 6. Produtos relacionados, quando disponíveis.

**CTAs principais:** - Consultar disponibilidade. - Solicitar
informações pelo WhatsApp. - Voltar ao catálogo.

### 5.5. Página Galeria

**Prioridade: Média**

**Objetivo:** apresentar visualmente a loja, seus produtos e a
experiência da marca.

**Conteúdo:** 1. Fotografias do ambiente interno. 2. Fotografias da
fachada. 3. Exposição de roupas, botas e chapéus. 4. Fotografias de
produtos. 5. Imagens relacionadas à cultura country.

**CTAs principais:** - Conheça nossa loja. - Veja nossos produtos. -
Como chegar.

### 5.6. Página Onde Estamos

**Prioridade: Média**

**Objetivo:** facilitar a localização física da empresa.

**Conteúdo:** 1. Endereço completo da loja. 2. Mapa interativo. 3.
Informações sobre horários de funcionamento. 4. Referências para
localização, quando disponíveis.

**CTAs principais:** - Como chegar. - Abrir localização no mapa. - Falar
pelo WhatsApp.

### 5.7. Página Contato

**Prioridade: Alta**

**Objetivo:** facilitar a comunicação entre os visitantes e a empresa.

**Conteúdo:** 1. Mensagem de boas-vindas. 2. Número de WhatsApp
comercial. 3. Telefone de atendimento. 4. E-mail institucional. 5. Links
para redes sociais. 6. Endereço comercial. 7. Horários de atendimento.

**CTAs principais:** - Chamar no WhatsApp. - Ligar agora. - Acessar
Instagram. - Enviar e-mail.

*Os dados comerciais deverão ser fornecidos e validados pela empresa
antes da publicação.*

## 6. Fluxo de navegação do usuário

O fluxo de navegação deverá permitir que o visitante encontre
rapidamente o conteúdo desejado.

``` mermaid
flowchart TD
    A["Usuário acessa o site"] --> B["Página Inicial"]
    B --> C["Conhecer a Empresa"]
    B --> D["Explorar Produtos"]
    B --> E["Visualizar Galeria"]
    B --> F["Localização"]
    B --> G["Contato"]
    D --> H["Escolher Categoria"]
    H --> I["Selecionar Produto"]
    I --> J["Visualizar Detalhes"]
    J --> K["Consultar pelo WhatsApp"]
    C --> L["Conhecer História e Valores"]
    L --> G
    E --> G
    F --> M["Abrir Mapa"]
    M --> G
    G --> N["WhatsApp / Telefone / E-mail"]
```

### Exemplos de jornadas

**Jornada 1 --- Cliente interessado em produtos**

1.  Acessa a página inicial.
2.  Seleciona Produtos.
3.  Escolhe uma categoria.
4.  Visualiza um produto.
5.  Clica em Consultar pelo WhatsApp.

**Jornada 2 --- Visitante que deseja conhecer a empresa**

1.  Acessa a página inicial.
2.  Seleciona A Empresa.
3.  Conhece a história e os valores.
4.  Acessa a Galeria.
5.  Entra em contato.

**Jornada 3 --- Cliente que deseja visitar a loja**

1.  Acessa a página inicial.
2.  Seleciona Onde Estamos.
3.  Visualiza o endereço.
4.  Abre o mapa.
5.  Consulta a rota até a loja.

## 7. Principais botões e chamadas para ação (CTAs)

Os CTAs devem ser objetivos, visíveis e utilizar uma linguagem próxima
do público country.

  Botão                     Destino               Objetivo
  ------------------------- --------------------- -----------------------
  Conheça a Santo Rancho    A Empresa             Apresentar a marca
  Ver produtos              Produtos              Acessar o catálogo
  Moda Masculina            Categoria masculina   Explorar produtos
  Moda Feminina             Categoria feminina    Explorar produtos
  Moda Infantil             Categoria infantil    Explorar produtos
  Ver detalhes              Produto               Consultar informações
  Consultar pelo WhatsApp   WhatsApp              Iniciar atendimento
  Conheça nossa loja        Galeria               Visualizar o ambiente
  Como chegar               Mapa                  Encontrar a loja
  Fale conosco              Contato               Acessar atendimento

**Recomendação de UX:** utilizar o WhatsApp como principal chamada para
ação comercial, pois permite que o visitante tire dúvidas diretamente
com a empresa sem precisar de uma loja virtual.

## 8. Estrutura do cabeçalho e rodapé

### 8.1. Cabeçalho (Header)

Deverá conter: - Logotipo da Santo Rancho. - Menu principal. - Submenu
de categorias de produtos. - Botão de contato pelo WhatsApp. - Menu
responsivo para dispositivos móveis.

### 8.2. Rodapé (Footer)

Deverá conter: - Logotipo da empresa. - Breve descrição institucional. -
Links para as páginas principais. - Categorias de produtos. - Telefone e
WhatsApp. - Endereço comercial. - Redes sociais. - Direitos reservados
da empresa.

## 9. Recomendações de identidade visual e experiência do usuário

A arquitetura deverá respeitar a identidade visual previamente
desenvolvida para a marca.

**Diretrizes visuais:** - Preto e marrom: tradição, força e
rusticidade. - Bege e dourado: elegância e sofisticação.

**Recomendações:** 1. Utilizar fotografias reais da loja e dos produtos.
2. Priorizar imagens de boa qualidade. 3. Manter botões de fácil
identificação. 4. Utilizar títulos curtos e objetivos. 5. Evitar menus
muito extensos. 6. Garantir boa experiência em dispositivos móveis. 7.
Manter consistência entre todas as páginas. 8. Utilizar elementos
gráficos country de forma equilibrada, sem prejudicar a leitura.

## 10. Priorização das páginas

  Página                   Prioridade   Versão
  ------------------------ ------------ ----------
  Início                   Alta         MVP
  A Empresa                Alta         MVP
  Produtos                 Alta         MVP
  Categorias de produtos   Alta         MVP
  Detalhes do produto      Alta         MVP
  Galeria                  Média        MVP
  Onde Estamos             Média        MVP
  Contato                  Alta         MVP
  Loja virtual             Futura       Versão 2
  Cadastro de clientes     Futura       Versão 2
  Blog                     Futura       Versão 2
  Área administrativa      Futura       Versão 2

## 11. Resultado esperado

Ao final da aplicação desta arquitetura da informação, o site da Santo
Rancho Oliveira Moda Country Ltda. deverá apresentar uma estrutura
organizada, com navegação intuitiva e identidade visual consistente.

A organização proposta permitirá que os visitantes: - Conheçam a empresa
e sua história. - Explorem as categorias de produtos. - Visualizem
detalhes dos produtos. - Conheçam o espaço físico da loja. - Encontrem
facilmente os canais de atendimento. - Entrem em contato com a empresa
pelo WhatsApp.

**Próxima etapa recomendada:** desenvolver os wireframes (esboços das
telas) de cada página, começando pela página inicial, catálogo de
produtos e contato, antes de iniciar a programação do site.
