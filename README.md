# Dashboard de Motoristas - Controle de Veículos

Dashboard responsivo para visualização do ranking e aproveitamento dos motoristas.

## Características

- **Fonte de dados ao vivo**: puxa diretamente da planilha publicada do Google Sheets (sem manipulação).
- **Responsivo**: funciona bem no celular (vertical) e no monitor/apresentação (horizontal).
- **Gráficos de barras**: ranking claro e percentual de aproveitamento (não usa gráfico de pizza).
- **Filtros**: por mês e quantidade de motoristas no topo.
- **Transparência**: mostra que os dados vêm da planilha oficial.

## Como hospedar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `dashboard-motoristas`).
2. Faça upload do arquivo `index.html` (e este README se quiser).
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha a branch `main` (ou `master`) e a pasta `/ (root)`.
5. Salve. Em alguns minutos o site estará disponível em:
   `https://SEU-USUARIO.github.io/dashboard-motoristas/`

## Atualização dos dados

Os dados são carregados automaticamente da planilha publicada toda vez que a página é aberta.  
Não é necessário atualizar o código quando a planilha for alimentada.

## Critérios de ranking

- **Total de Viagens**: quantidade de registros (linhas) do motorista na planilha.
- **Dias com +1 viagem**: dias em que o motorista aparece mais de uma vez.

O percentual mostrado é a participação do motorista no total de viagens do período selecionado.

## Observações

- A planilha é a fonte única e segura.
- Ideal para apresentação em reunião e visualização pelos motoristas no celular.
- Percentual de premiação pode ser definido posteriormente pela diretoria com base nos números exibidos.
