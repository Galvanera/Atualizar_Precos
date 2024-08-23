Atualizador de Preços de Produtos
Este repositório contém um script Python que utiliza a biblioteca pandas para atualizar os preços de produtos em uma planilha Excel. O script ajusta os multiplicadores de imposto com base no tipo de produto e recalcula os preços reais, salvando as mudanças em um novo arquivo Excel.

Funcionalidades
Leitura de Planilha Excel: Carrega os dados de produtos a partir de um arquivo Excel (produtos.xlsx).
Atualização de Multiplicadores de Imposto: Ajusta os multiplicadores de imposto com base no tipo de produto.
Cálculo de Preços Reais: Recalcula os preços reais dos produtos com base nos multiplicadores de imposto.
Exportação para Excel: Salva as mudanças em um novo arquivo Excel (Produtos.xlsx).
Como Usar
Instale as bibliotecas necessárias:
pip install pandas openpyxl

Clone este repositório:
git clone https://github.com/seu-usuario/atualizar_Precos.git
cd atualizar_Precos

Prepare o arquivo Excel:
Certifique-se de ter um arquivo chamado produtos.xlsx com as colunas Tipo, Produtos, Multiplicador imposto e Preço base original.
Execute o script:
python atualizar_precos.py

Veja os dados atualizados:
O script salvará os dados atualizados em um arquivo Excel chamado Produtos.xlsx.
