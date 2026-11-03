# Como colocar o projeto online

Você não precisa usar comandos. Faça tudo pelo site do GitHub.

## 1. Criar um espaço no GitHub

1. Entre em [github.com](https://github.com) e faça login ou crie uma conta.
2. Clique no sinal **+** no alto da página e escolha **New repository**.
3. Em **Repository name**, escreva `controle-financeiro`.
4. Marque **Public** e clique em **Create repository**.

## 2. Enviar os arquivos do projeto

1. No repositório que acabou de criar, clique em **Add file** e depois em **Upload files**.
2. Abra no seu computador a pasta `controle-financeiro` que recebeu.
3. Selecione e envie os arquivos que estão dentro dela: `index.html`, `styles.css`, `app.js`, `manifest.webmanifest`, `icon.svg` e `sw.js`. O `README.md` é opcional.
4. Na parte de baixo da página do GitHub, clique em **Commit changes**.

## 3. Ligar a publicação do site

1. No repositório, clique em **Settings**.
2. No menu lateral, clique em **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Escolha a branch **main** e a pasta **/(root)**, depois clique em **Save**.
5. Aguarde um ou dois minutos e atualize essa página. O GitHub mostrará o link do site.

O endereço costuma ser `https://SEU-USUARIO.github.io/controle-financeiro/`. Troque `SEU-USUARIO` pelo seu nome de usuário do GitHub. Você pode mandar esse link para outras pessoas.

## Abrir no celular

Abra o link no celular. No Android, abra o menu do navegador e escolha **Instalar app** ou **Adicionar à tela inicial**. No iPhone, abra no Safari, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.

Os dados de cada pessoa ficam salvos no navegador e no aparelho dela. Esta versão não usa contas nem sincroniza os dados entre dispositivos.

## Recursos do projeto

- Receitas, despesas e investimentos separados no resumo.
- Categorias Veículo e Investimentos incluídas.
- Orçamentos mensais por categoria de despesa.
- Lançamentos mensais recorrentes. Ao excluir um lançamento recorrente, também são interrompidas as próximas ocorrências.
- Parcelamento de despesas: informe o valor total da compra, a quantidade de parcelas e a data da primeira; o total é dividido em parcelas mensais e identificado no histórico.
- Comparação das receitas e despesas com o mês anterior.
- Meta mensal de reserva acompanhada pelos lançamentos de investimento.

## Como atualizar o site

Quando houver uma nova versão, envie os arquivos atualizados para o mesmo repositório, substituindo os antigos, e clique em **Fazer commit das alterações**. O GitHub Pages atualizará o mesmo link automaticamente.

A aba **Gráficos** permite comparar receitas, despesas e investimentos nos últimos 7 dias, no mês, nos últimos 6 meses, no ano ou em um período escolhido. Também mostra despesas agrupadas por categoria.

- Backup local: exporte os dados em JSON e restaure-os em outro navegador ou aparelho.
- Regras recorrentes podem ser editadas, pausadas e limitadas a um mês final.
- Categorias podem ser renomeadas ou excluídas; lançamentos existentes são reatribuídos ao excluir uma categoria usada.
- Orçamentos destacam quando o limite está quase atingido ou foi ultrapassado.
