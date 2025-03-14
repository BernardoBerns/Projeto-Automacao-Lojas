# Projetos-Automacao

Automacao de Indicadores

📌 Objetivo

Este projeto tem como objetivo automatizar o cálculo e envio de relatórios diários de desempenho para uma rede de lojas de roupas, otimizando o processo manual realizado pela equipe de análise de dados.

📝 Descrição

A rede conta com 25 lojas espalhadas pelo Brasil, e todos os dias os gerentes de cada loja precisam receber um OnePage contendo os principais indicadores da sua unidade. O processo automatizado deve:

Calcular os indicadores para cada loja.

Gerar arquivos individuais com os dados da respectiva loja.

Enviar e-mails automáticos com o resumo no corpo do e-mail e um anexo contendo os detalhes das vendas.

Gerar relatórios consolidados e enviá-los à diretoria, destacando as melhores e piores lojas do dia e do ano.

Manter um histórico de backups das planilhas geradas.

📊 Indicadores Monitorados

Os principais indicadores a serem calculados no OnePage são:

Faturamento (Meta: R$ 1.650.000 anual / R$ 1.000 diário)

Diversidade de Produtos vendidos (Meta: 120 anual / 4 diário)

Ticket Médio por Venda (Meta Ano: 500 / Meta Dia: 500)

📂 Estrutura dos Arquivos

Os seguintes arquivos são utilizados no projeto:

Emails.xlsx → Contém os e-mails e nomes dos gerentes das lojas

Vendas.xlsx → Base de dados com as vendas de todas as lojas

Lojas.csv → Listagem das lojas da rede

⚙️ Tecnologias Utilizadas

Python

pandas (Manipulação de dados)

openpyxl (Leitura e escrita de arquivos Excel)

smtplib (Envio de e-mails)

email.message (Formatação de e-mails)

Git/GitHub (Controle de versão)

🎓 Desafio do Curso

Este projeto foi desenvolvido como parte de um desafio proposto pelo curso da Hashtag, com o objetivo de aplicar conceitos de automação e análise de dados em um cenário realista.