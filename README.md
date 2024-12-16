# Modelo-Conceitual-Oficina-Mec-nica
Criação um esquema conceitual do zero a partir de uma narrativa fornecida para o contexto de oficina mecânica para um Desafio de Projeto.

Anexo do Modelo logo acima.

Decide por criar o modelo definindo entidades pricipais, como: 
Clientes: Representam os donos dos veículos.
Veículos: Ligados aos clientes para controlar os carros que chegam na oficina.
Mecânicos: Profissionais com informações como nome, endereço e especialidade.
Equipe: Agrupa os mecânicos que trabalham juntos em uma OS (Ordem de Serviço).
Ordem de Serviço (OS): Organiza os serviços, peças e equipes envolvidas.

Cada Ordem de Serviço está ligada a outras duas entidade: 
Serviços: Ela contem o campo valorMãoDeObra para o calculo do valor que tera a mão de obra do serviço a ser realizado. E o campo equipeResponsavel 
visto que  a narrativa sugere que uma equipe identifica os serviços a serem executados.
Peças: Associadas à OSe com um campo da identiuficar o valor das peças e um canpo para identificar a quantidade diretamente no relacionamento.

Adicionei um campo Autorização do Cliente na entidade Ordem de Serviço (OS) já que a narrativa menciona que o cliente precisa autorizar a execução.
