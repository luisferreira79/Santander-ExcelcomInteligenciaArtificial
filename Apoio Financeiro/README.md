# Santander - Excel com Inteligência Artificial
1. Objetivo do Desafio
Este desafio tem como proposta o desenvolvimento de um aplicativo de apoio financeiro, cujo foco principal é auxiliar o usuário na tomada de decisão sobre investimentos mensais com base no seu salário. A solução está estruturada inicialmente em uma planilha que simula o funcionamento do aplicativo e seus cálculos.

2. Funcionamento Geral
A planilha está dividida em tabelas específicas que se integram para realizar os cálculos necessários. A seguir, detalha-se a função de cada uma:

3. Aba: APP (Painel Principal)
🔧 Configurações Iniciais
O usuário informa:
Salário mensal
A planilha retorna a sugestão de investimento, baseada em 30% do valor do salário.
Também é inserido um rendimento médio da carteira para simulação.

💰 Investimento Mensal
O usuário define:
Valor a investir por mês
Quantidade de anos para investimento
Taxa de rendimento mensal esperada
Com base nesses dados, a planilha:
Calcula o patrimônio acumulado ao fim do período.
Estima os dividendos mensais, considerando a taxa informada.
Importante: Os resultados são válidos sob a condição de que o valor mensal seja investido sem falhas ao longo de todo o período.

4. Tabela: Cenários
Esta seção apresenta uma perspectiva ano a ano, projetando:
O valor total acumulado
O valor mensal dos dividendos esperados
Isso oferece uma visualização clara da evolução do investimento ao longo dos anos.

5. Tabela: Perfil do Investidor
O usuário pode escolher entre três perfis de investidor:
Conservador
Moderado
Agressivo
Cada perfil possui uma proporção sugerida de alocação em tipos de Fundos de Investimento Imobiliário (FIIs), como:
Papel
Tijolo
Híbridos
FOFs
A planilha soma automaticamente os percentuais com base na seleção do perfil, orientando a alocação da carteira.

6. Visualização Gráfica
A planilha inclui um gráfico do tipo pizza, que ilustra visualmente a distribuição sugerida da carteira conforme o perfil selecionado, facilitando o entendimento do usuário sobre como seus recursos devem ser alocados.

8. Aba: tab_apoio (Tabela Auxiliar)
Esta aba contém dados auxiliares que servem como base para os cálculos automáticos da planilha principal. É aqui que se encontram as proporções dos perfis de investidores e outros parâmetros usados em fórmulas.

✅ Conclusão
A estrutura da planilha serve como protótipo funcional de um aplicativo de educação e planejamento financeiro, ideal para usuários que desejam entender melhor o impacto do investimento recorrente e da disciplina financeira. A lógica pode ser facilmente migrada para uma plataforma digital com interface amigável, possibilitando simulações rápidas, personalizadas e educativas.
