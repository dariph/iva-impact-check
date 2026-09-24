🇧🇷 IVA-Impact Check™

Simulador Especializado de IBS & CBS (Reforma Tributária 2027)

Planejamento Tributário, Apuração de Créditos Não-Cumulativos, Simples Nacional (Puro vs. Híbrido) e Preservação de Margem de Contribuição.

📌 Sobre o Projeto

O IVA-Impact Check™ é uma aplicação web interativa desenvolvida para resolver uma das maiores incertezas do meio corporativo e contábil brasileiro: como a transição para o modelo de IVA Dual (CBS e IBS a partir de 01/2027) impactará os preços de venda, a carga tributária líquida e a lucratividade das empresas.

🚀 Principais Recursos & Funcionalidades

1. 🧮 Simulação Comparativa de Carga e Margem

Modelo Vigente: Lucro Real, Lucro Presumido ou Simples Nacional (PIS, COFINS, ICMS, ISS).

Novo Modelo (IVA Dual):

Marco Janeiro/2027: CBS referencial a 8,80% e IBS a 0,10% (Total base 8,90%), com extinção do PIS/COFINS.

Cenário Pleno Projetado: Alíquota nacional estimada de ~26,50% com slider configurável.

Precificação Automática: Cálculo do preço de venda sugerido para manter a mesma margem nominal de contribuição (R$).

2. ⚖️ O Dilema do Simples Nacional (EC 132/2023 & LC 214/2025)

Simples Puro (Tradicional): Apuração unificada via DAS, vedação à apropriação de créditos de entrada e transferência residual de crédito para clientes PJ.

Simples Híbrido (Opção do Art. 146 da CF): Manutenção dos tributos diretos no DAS (IRPJ, CSLL, CPP) e apuração de IBS/CBS por fora, transferindo crédito integral para compradores corporativos (competitividade em cadeias B2B).

3. 📉 Regimes Diferenciados & Redutores de Alíquota

Redução de 70%: Locação de bens imóveis (com incidência líquida de 2,67% em 2027 e 7,95% no regime pleno).

Redução de 60%: Serviços de saúde, educação e agronegócio.

Redução de 30%: Serviços prestados por profissões intelectuais/regulamentadas.

Alíquota Zero / Isenção (100%): Cesta básica nacional e imunidades constitucionais.

4. 📊 Livro de Apuração de Créditos & Abatimento

Demonstração contábil do débito sobre vendas, créditos apropriados sobre aquisição de insumos diretos e despesas operacionais qualificadas (energia, aluguel PJ, serviços tomados).

Avaliação do imposto líquido a recolher e análise do impacto da transferência de créditos para clientes PJ.

5. 📑 DRE Sintética Comparativa & Diagnóstico Estratégico

Demonstração do Resultado comparando linha a linha o modelo tradicional contra o novo sistema.

Gráficos dinâmicos com a biblioteca Recharts.

Checklist prático de prontidão para o Split Payment e parametrização de ERPs.

6. 🌓 Design & Usabilidade

Dark / Light Mode: Alternância de tema com persistência imediata em localStorage.

Exportação com 1 Clique: Geração e cópia de relatório técnico padronizado pronto para anexar em pareceres ou propostas de consultoria.

Embed Ready: Arquitetura autoajustável (w-full, h-auto), pronta para ser incorporada via <iframe> em plataformas de membros (Kiwify, Hotmart, WordPress).

🛠️ Tecnologias Utilizadas

A aplicação foi projetada sob uma arquitetura limpa de Single-File Component (SFC) com compilação via navegador por meio de Native ES Modules e Import Maps, eliminando o atrito de instalações pesadas (node_modules) para fins de distribuição e embed:

Linguagem / Core: HTML5, JavaScript (ES6+), JSX

Interface: React 18 (react, react-dom)

Estilização: Tailwind CSS CDN

Visualização de Dados: Recharts

Ícones: Lucide React

Compilação Client-Side: Babel Standalone

💻 Como Executar Localmente

Como o mini-app é autossuficiente e roda diretamente no navegador, você não precisa instalar npm ou configurar servidores complexos.

Passo a passo:

Clone este repositório:

git clone https://github.com/dariph/iva-impact-check.git

Acesse a pasta do projeto:

cd iva-impact-check

Abra o arquivo index.html em qualquer navegador moderno:

Dê dois cliques no arquivo index.html.

💼 Aplicação Comercial e Parcerias

Esta ferramenta foi desenvolvida com o objetivo de apoiar e facilitar a tomada de decisão no planejamento tributário, servindo como um recurso prático e acessível para:

Escritórios Contábeis: Apresentação consultiva em reuniões de planejamento tributário com clientes de médio e grande porte.

Software Houses & ERPs: Ferramenta didática para conscientizar equipes de suporte e clientes sobre a necessidade de adaptação dos cadastros fiscais.

Associações Comerciais & CDLs: Diagnóstico em massa para pequenas e médias empresas avaliarem o risco de perda de competitividade B2B.

⚖️ Fundamentação Legal

Emenda Constitucional nº 132/2023 (Instituição do Sistema Tributário Nacional sobre o Consumo).

Projeto de Lei Complementar nº 68/2024 / Lei Complementar nº 214/2025 (Instituição e Regulamentação do IBS, CBS e Imposto Seletivo).

Súmula Vinculante nº 31 do STF (Não incidência de ISS sobre locação pura de bens móveis/imóveis).

👤 Autor

Desenvolvido por Dari Pinheiro Heirich

LinkedIn: linkedin.com/in/dari-pinheiro-heirich-07706040b

GitHub: github.com/dariph/iva-impact-check
