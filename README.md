# ArquiteturaSoftware
 1 - Quais são as principais desvantagens de concentrar toda a lógica, interface e dados em um único arquivo?  
Resp: Dificuldade de manutenção, quando toda a aplicação está concentrada em um único arquivo, qualquer mudança, por menor que seja, pode gerar impactos em outras partes do código, dificultando a identificação de onde e como fazer as alterações. Falta de organização: Misturar lógica de negócio, interface de usuário e manipulação de dados no mesmo lugar torna o código confuso, dificultando o entendimento, especialmente em projetos maiores. Essas são só algumas das principais desvantagens.  

2- Como a separação em camadas facilita a manutenção e a escalabilidade da aplicação?  
Resp: Ao organizar o código de forma modular, permite alterações isoladas em cada parte (interface, lógica de negócios, dados) sem impactar o restante. Também melhora a escalabilidade ao permitir a adição de novas funcionalidades ou componentes de forma independente, facilitando o crescimento da aplicação sem comprometer o código existente.

3- Quais são os principais benefícios da arquitetura Pipe e Filtros para sistemas que precisam de flexibilidade nas transformações de dados?  
Resp: Seus principais benefícios são a modularidade, facilitando manutenção e reutilização de componentes; escalabilidade, permitindo o crescimento do sistema sem grandes refatorações; e a possibilidade de paralelismo, otimizando o processamento. Além disso, cada filtro pode ser testado e depurado de forma independente.
