# Modelo-Conceitual-Oficina-Mec-nica
Criação um esquema conceitual do zero a partir de uma narrativa fornecida para o contexto de oficina mecânica para um Desafio de Projeto.

Anexo do Modelo logo acima.

Decide por criar o modelo definindo entidades pricipais, como: <br>
Clientes: Representam os donos dos veículos.<br>
Veículos: Ligados aos clientes para controlar os carros que chegam na oficina.<br>
Mecânicos: Profissionais com informações como nome, endereço e especialidade.<br>
Equipe: Agrupa os mecânicos que trabalham juntos em uma OS (Ordem de Serviço).<br>
Ordem de Serviço (OS): Organiza os serviços, peças e equipes envolvidas.<br>

Cada Ordem de Serviço está ligada a outras duas entidade: <br>
Serviços: Ela contem o campo valorMãoDeObra para o calculo do valor que tera a mão de obra do serviço a ser realizado. E o campo equipeResponsavel 
visto que  a narrativa sugere que uma equipe identifica os serviços a serem executados.<br>
Peças: Associadas à OSe com um campo da identiuficar o valor das peças e um canpo para identificar a quantidade diretamente no relacionamento.

Adicionei um campo Autorização do Cliente na entidade Ordem de Serviço (OS) já que a narrativa menciona que o cliente precisa autorizar a execução.
