# Product design

<span style="color:red">Pré-requisitos: <a href="02-Product-discovery.md"> Product discovery</a></span>

## Histórias de usuários
Eu, João Silva preciso acompanhar e controlar meus gastos de forma prática no celular para manter minhas finanças organizadas e evitar distrações.
Eu, João Silva quero receber sugestões de lazer e economia com base nos meus hábitos para aproveitar o tempo livre sem gastar além do necessário.

Eu, Antônio Carlos preciso montar planejamentos e calcular custos de forma automatizada para otimizar o tempo e focar mais na gestão da empresa e tempo com a família.
Eu, Antônio Carlos quero armazenar e acessar dados de clientes de forma prática para facilitar a gestão e melhorar o relacionamento com os clientes.

Eu, Valdemir Henrique preciso ter controle fácil sobre lucro e despesas da empresa para melhorar os resultados e tomar decisões com mais agilidade.
Eu, Valdemir Henrique quero receber suporte e orientações sobre o uso de sistemas administrativos para aprender e aplicar novas ferramentas para a gestão da empresa.

Eu, Marli Vilaça preciso registrar meus gastos no celular de forma simples para controlar melhor minhas finanças e evitar problemas.
Eu, Marli Vilaça quero receber notificações sobre vencimentos de contas para evitar esquecimentos e manter tranquilidade nas finanças.



## Proposta de valor

(images/mpvalor1.png)
(images/mpvalor2.png)
(images/mpvalor3.png)
(images/mpvalor4.png)


### Requisitos funcionais

RF01: O sistema deve permitir que o usuário se cadastre informando nome, email, senha e demais dados pessoais.

RF02: O sistema deve permitir que o usuário faça login utilizando email e senha previamente cadastrados.

RF03: O sistema deve validar as credenciais do usuário e permitir o acesso apenas se estiverem corretas.

RF04: O sistema deve permitir que o usuário registre suas despesas, incluindo valor, data, categoria e descrição.

RF05: O sistema deve exibir um histórico das despesas cadastradas.

RF06: O sistema deve permitir a edição e exclusão de despesas já registradas.

RF07: O sistema deve permitir que o usuário registre seus ganhos, com informações como valor, data, fonte e categoria.

RF08: O sistema deve exibir um histórico dos ganhos cadastrados.

RF09: O sistema deve permitir a edição e exclusão de ganhos já registrados.

RF10: O sistema deve permitir que o usuário registre fontes de renda extra separadamente dos ganhos fixos.

RF11: O sistema deve exibir relatórios ou gráficos diferenciando os ganhos fixos das rendas extras.

RF12: O sistema deve permitir que o usuário crie metas financeiras com valor-alvo, descrição e prazo.

RF13: O sistema deve exibir o progresso das metas com base nos ganhos e despesas do usuário.

RF14: O sistema deve alertar o usuário caso esteja se afastando do cumprimento das metas.

RF15: O sistema deve permitir que o usuário vincule sua conta bancária através de uma API segura.

RF16: O sistema deve importar automaticamente dados bancários (ganhos e despesas) para controle integrado.

RF17: O sistema deve oferecer recomendações personalizadas com base nos dados financeiros do usuário.

RF18: O sistema deve disponibilizar uma seção de dúvidas frequentes (FAQ).

RF19: O sistema deve permitir o envio de perguntas por parte dos usuários para receber orientação financeira.


### Requisitos não funcionais

RNF01: O sistema deve ser construído de forma que seja fácil adicionar novas funcionalidades no futuro, sem precisar refazer grandes partes do que já foi desenvolvido.

RNF02: O site deve oferecer um tempo de resposta de no máximo 2 a 3 segundos para operações críticas, como: carregamento de dados financeiros, geração de relatórios, exibição de dashboards.

RNF03: O sistema deve ser escalável horizontal e verticalmente, suportando um aumento no número de usuários e de transações sem degradação perceptível de desempenho.

RNF04: A estrutura do sistema deve ser bem organizada, dividida em partes com responsabilidades claras, facilitando a manutenção, as melhorias e a resolução de problemas quando necessário.

RNF05: O sistema deve estar disponível para acesso pelo usuário 24 horas por dia, 7 dias por semana, com alta tolerância a falhas.

RNF06: O sistema deve permitir a aplicação de testes automatizados para garantir a confiabilidade das funcionalidades mesmo após modificações.


## Restrições

01 - O uso de dados bancários será simulado, não havendo integração real com instituições financeiras.

02 - A equipe de desenvolvimento será composta apenas pelos integrantes do grupo, sem contratação externa.

03 - O projeto deverá ser entregue até o final do semestre.
