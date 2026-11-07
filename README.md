# Instituto Jaraguá

Site institucional estático do Instituto Jaraguá. O [GitHub Pages](https://pedromagalhaesbatista.github.io/instituto-jaragua/) publica a raiz da branch `main`.

Edite `index.html` para atualizar o conteúdo e `styles.css` para ajustar o visual. Para conferir localmente, execute `python3 -m http.server 8000` nesta pasta e abra `http://localhost:8000`.

## Relatórios bimestrais

O acervo fica em `relatorios.html`. Cada edição tem uma página permanente em `relatorios/edicao-NN/index.html`. A primeira edição está em preparação, com tema a definir.

Para publicar a primeira edição, preencha o título, a descrição, os autores, a data de publicação, a cobertura dos dados e a versão na página da edição. Atualize também o título, o resumo e a situação no acervo. Ajuste as informações de compartilhamento no `<head>` das páginas.

Reúna os arquivos aprovados em `relatorios/edicao-01/arquivos/`. A primeira parte recebe o diagnóstico, as bases, o dicionário e o pacote de replicação. A segunda recebe análises e referências comentadas, com links para textos ou páginas das publicações. A terceira recebe as propostas, a síntese para decisão e a apresentação. Inclua o link do relatório completo junto aos metadados da edição.

Substitua cada aviso de preparação por seu conteúdo e pelos links de acesso. Para arquivos hospedados na pasta da edição, um link de download pode seguir este formato, com nome, formato, versão e tamanho reais.

```html
<a href="arquivos/base-dados-v1.csv" download>Baixar base de dados · CSV · v1.0 · 240 KB</a>
```

Os avisos atuais são texto. Insira links de download quando os arquivos estiverem disponíveis e valide seus caminhos antes de publicar. Identifique as fontes, a data de coleta, a cobertura temporal e geográfica, os métodos de tratamento, as limitações e as condições de reutilização. Documente as dependências e os passos necessários para reproduzir os resultados.

Para uma nova edição, crie uma pasta própria, usando a estrutura de `edicao-01`. Atualize os conteúdos, os links relativos, a URL canônica e os metadados da nova página. Acrescente sua entrada ao acervo, mantendo os endereços das edições anteriores. Ao atualizar arquivos publicados, identifique a versão e a data e mantenha um registro das alterações e o acesso às versões utilizadas no relatório.

As alterações enviadas à branch `main` são publicadas pelo GitHub Pages.

A fotografia do Porto de Jaraguá é de [Mattuta, via Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Panoramica_do_Porto_de_Jaragu%C3%A1_Macei%C3%B3_Alagoas.jpg), sob a licença [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt-br). As cópias para o site e a imagem de compartilhamento foram redimensionadas. O logotipo pertence ao Instituto Jaraguá.
