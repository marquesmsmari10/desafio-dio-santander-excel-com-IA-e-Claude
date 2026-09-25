# 📊 Simulador de Investimentos em FIIs (Fundos Imobiliários) 🏢

*Hello there!* Seja muito bem-vindo(a) ao meu repositório! Meu nome é Mariana, tenho 35 anos, sou professora de inglês e uma grande entusiasta do mundo da tecnologia e das finanças. 👩‍🏫💻✨

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)**. O objetivo? Desmistificar os investimentos e usar a tecnologia para nos ajudar a tomar decisões financeiras mais inteligentes! 

Peguei toda a minha paixão por ensinar e documentar, juntei com os conceitos de planilhas eletrônicas e criei essa ferramenta maravilhosa. O projeto tomou como base de estudos o arquivo de referência `desafioDIOexcel.xlsx` disponibilizado durante as aulas.

---

## 🎯 O que é este projeto?

Sabe aquela dúvida que sempre bate: *"Se eu investir X reais por mês em Fundos Imobiliários, quanto terei daqui a 5 anos?"* 

Foi exatamente para responder a essa pergunta que criei esta **Ferramenta de Simulação de Investimentos**. Ela é uma planilha automatizada construída para o Google Sheets (e compatível com Excel) que calcula de forma rápida e visual:
- O valor **Total Investido** (do seu próprio bolso).
- O **Patrimônio Acumulado** (A mágica dos juros compostos em ação!).
- O **Total de Juros Ganhos** durante o período.
- O seu **Dividendo Mensal Estimado** no final do período (a tão sonhada renda passiva 💸).

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Google Sheets / Microsoft Excel:** Para a estruturação lógica, cálculos financeiros e criação do modelo.
- **Fórmulas Financeiras:** Utilização da função de Valor Futuro (`VF`) para calcular o crescimento do patrimônio.
- **GitHub & Markdown:** Para versionamento, documentação técnica estruturada e compartilhamento do portfólio.

---

## 🧠 Como a lógica foi construída?

*Let's dive in!* Aqui está um resumo do que eu fiz para transformar o desafio em realidade:

1. **Definição das Variáveis de Entrada:** Criei uma área limpa onde o usuário só precisa preencher quatro informações básicas: *Investimento Inicial*, *Aporte Mensal*, *Taxa de Rendimento Mensal* e *Tempo (em meses)*.
2. **Cálculo do Total Investido:** Uma matemática simples, multiplicando os meses pelo aporte e somando o valor inicial.
3. **O Poder dos Juros Compostos:** Apliquei a fórmula financeira `VF` (Valor Futuro) para automatizar o cálculo complexo de juros sobre juros a cada mês. 
4. **Projeção de Renda Passiva:** Multipliquei o Patrimônio Acumulado final pela taxa de rendimento para mostrar quanto o usuário receberia de "aluguel" (dividendos) ao final do período.
5. **Formatação amigável:** Preparei tudo para que até quem nunca abriu uma planilha na vida se sinta confortável em usar. Acessibilidade é tudo! 🌟

---

## 🚀 Como usar este simulador?

Você pode testar a planilha você mesmo(a)! É super fácil:

1. Faça o download do arquivo `simulador_fiis.csv` neste repositório.
2. Abra o seu **Google Sheets** (Planilhas do Google).
3. Vá em **Arquivo > Importar > Fazer Upload** e selecione o arquivo baixado.
4. Na caixinha que aparecer, escolha "Substituir planilha atual" e marque a opção para converter texto em números e datas.
5. *Voilá!* A planilha está pronta. Agora é só brincar com os números nas células de **Parâmetros de Entrada** e ver a mágica acontecer!

---

## 💡 Próximos Passos (Next Steps!)

Como uma boa *tech enthusiast*, eu sei que um projeto nunca está 100% finalizado; ele está sempre evoluindo! Para o futuro, pretendo:
- [ ] Adicionar um gráfico dinâmico de evolução patrimonial.
- [ ] Colocar uma tabela completa de amortização mês a mês até o fim do período.
- [ ] Incluir uma aba comparando o investimento em FIIs com a Poupança.

---

*Thank you so much* por visitar meu projeto! Se você gostou, não esqueça de deixar uma estrelinha ⭐ no repositório. Dúvidas ou sugestões? Sinta-se à vontade para abrir uma *issue* ou me chamar!

**Feito com 💖 e muita dedicação por Mariana!**