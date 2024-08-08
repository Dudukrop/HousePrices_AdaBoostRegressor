<h1>House Prices</h1>
    <p>O projeto "House Prices" é uma análise e predição dos preços de venda de casas utilizando o dataset do Kaggle. Este projeto envolve a análise exploratória dos dados, a limpeza e a transformação das variáveis, e a aplicação de algoritmos de aprendizado de máquina para prever o preço de venda de imóveis.</p>

    <h2>Data Overview</h2>
    <p>Os dados utilizados no projeto são divididos em conjuntos de treino e teste, e incluem uma variedade de características de propriedades, como o tamanho do lote, o ano de construção, a qualidade da construção, entre outros.</p>
    <ul>
        <li><strong>Conjunto de Treino:</strong> 1460 entradas com 81 características cada.</li>
        <li><strong>Conjunto de Teste:</strong> 1459 entradas com 80 características cada.</li>
        <li>O conjunto de dados completo é uma concatenação dos conjuntos de treino e teste, resultando em 2919 entradas.</li>
    </ul>

    <h2>Data Cleaning</h2>
    <p>Foram realizadas diversas etapas de limpeza de dados para lidar com valores ausentes e transformar variáveis, incluindo:</p>
    <ul>
        <li>Preenchimento de valores ausentes em variáveis categóricas com a categoria mais frequente ou uma nova categoria como "None".</li>
        <li>Preenchimento de valores ausentes em variáveis numéricas com a média ou zero, dependendo do contexto.</li>
        <li>Conversão de variáveis categóricas em numéricas para utilização em modelos de aprendizado de máquina.</li>
    </ul>

    <h2>Data Exploration</h2>
    <p>A análise exploratória dos dados foi realizada para entender a distribuição das variáveis e suas relações com o preço de venda. Algumas das principais descobertas incluem:</p>
    <ul>
        <li>A maioria das casas está localizada em zonas residenciais de baixa densidade (<em>MSZoning: RL</em>).</li>
        <li>A qualidade geral da construção (<em>OverallQual</em>) tem uma forte correlação com o preço de venda.</li>
        <li>Variáveis como <em>GrLivArea</em> e <em>TotalBsmtSF</em> também são indicadores importantes do preço de venda.</li>
    </ul>

    <h2>Preenchimento de Valores Ausentes</h2>
    <p>Valores ausentes foram tratados conforme abaixo:</p>
    <ul>
        <li><strong>MSZoning:</strong> Preenchido com 'RL'.</li>
        <li><strong>LotFrontage:</strong> Preenchido com a média dos valores.</li>
        <li><strong>Alley:</strong> Preenchido com 'None'.</li>
        <li><strong>Utilities:</strong> Preenchido com 'AllPub'.</li>
        <li><strong>MasVnrType:</strong> Preenchido com 'None'.</li>
        <li><strong>MasVnrArea:</strong> Preenchido com 0.</li>
        <li><strong>BsmtQual:</strong> Preenchido com 'TA'.</li>
        <li><strong>BsmtCond:</strong> Preenchido com 'TA'.</li>
        <li><strong>BsmtExposure:</strong> Preenchido com 'No'.</li>
        <li><strong>BsmtFinType1:</strong> Preenchido com 'Unf'.</li>
        <li><strong>BsmtFinSF1:</strong> Preenchido com 0.</li>
        <li><strong>BsmtFinType2:</strong> Preenchido com 'Unf'.</li>
        <li><strong>BsmtFinSF2:</strong> Preenchido com 0.</li>
        <li><strong>BsmtUnfSF:</strong> Preenchido com 0.</li>
        <li><strong>TotalBsmtSF:</strong> Preenchido com a média dos valores.</li>
        <li><strong>Electrical:</strong> Preenchido com 'SBrkr'.</li>
        <li><strong>BsmtHalfBath:</strong> Preenchido com 0.</li>
        <li><strong>KitchenQual:</strong> Preenchido com 'TA'.</li>
        <li><strong>Functional:</strong> Preenchido com 'Typ'.</li>
        <li><strong>FireplaceQu:</strong> Preenchido com 'None'.</li>
        <li><strong>GarageType:</strong> Preenchido com 'None'.</li>
        <li><strong>GarageYrBlt:</strong> Preenchido com 0.</li>
        <li><strong>GarageFinish:</strong> Preenchido com 'None'.</li>
        <li><strong>GarageCars:</strong> Preenchido com 2.</li>
        <li><strong>GarageArea:</strong> Preenchido com a média dos valores.</li>
        <li><strong>GarageQual:</strong> Preenchido com 'TA'.</li>
        <li><strong>GarageCond:</strong> Preenchido com 'TA'.</li>
        <li><strong>PoolQC:</strong> Preenchido com 'None'.</li>
        <li><strong>Fence:</strong> Preenchido com 'None'.</li>
        <li><strong>MiscFeature:</strong> Preenchido com 'None'.</li>
        <li><strong>SaleType:</strong> Preenchido com 'WD'.</li>
    </ul>

    <h2>Conclusão</h2>
    <p>O projeto "House Prices" demonstra o processo de análise de dados, limpeza e preparação de um conjunto de dados imobiliários para previsão de preços de venda utilizando algoritmos de aprendizado de máquina.</p>
