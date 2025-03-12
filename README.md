# Gerenciador de LAN House

Atividade 1 de Modelos, métodos e técnicas da engenharia de software.
A atividade é mais voltada pra modelagem de software então não tem programação. (Talvez mais pra frente)


# Como executar o projeto

Na primeira vez que o programa for iniciado no computador, ele ira pedir para que um login seja criado. Após criar o login ele irá exercer suas funcionalidades de forma padrão.
Porém ao iniciar o programa a partir da segunda vez, o sistema deverá pedir o login cadastrado previamente. Caso o login inserido seja incorreto o sistema não permitirá a entrada até o login correto ser inserido.
Após o login correto ser inserido o usuário será enviado para a tela de menu a qual estará disponivel todas as funcionalidades listadas na categoria a seguir.


# Principais funcionalidades

As principais funcionalidades do programa consistem em:

- Cadastro de computadores
- Visualização de computadores em uso e gerenciamento de tais
- Indetificar o tempo de uso de cada cliente
- Calcular o valor a ser pago pelo cliente com base em seu tempo de uso
- Cadastrar e armazenar perfis de clientes
- Registrar reservas
- Um calendário contendo a data e a hora das reservas previamente registradas

  # Requisitos funcionais e não funcionais

  Requisitos funcionais:

[RF001] Cadastro de computadores

O sistema permitirá o registro dos computadores locais.

Atores: Administrador.
Prioridade: Essencial.
----------------------------------------------------------	
[RF002] Gerenciamento dos computadores em uso

O sistema permitirá que o usuário veja os computadores que estão em uso no momento.

Atores: Administrador.
Prioridade: Essencial.
----------------------------------------------------------
[RF003] Identificar o tempo de uso dos clientes

O sistema identifica o tempo de uso de cada cliente após sua saída do computador.

Atores: Sistema.
Prioridade: Essencial.
----------------------------------------------------------
[RF004] Calcular o valor a ser pago

O sistema irá calcular o valor a ser pago pelo cliente de forma equivalente ao tempo gasto em um computador.

Atores: Sistema.
Prioridade: Desejável.
----------------------------------------------------------
[RF005] Cadastrar e armazenar perfis de clientes

O sistema permitirá o cadastro de clientes dentro do sistema.

Atores: Administrador.
Prioridade: Importante.
----------------------------------------------------------
[RF006] Registro de reservas

O sistema permitirá o registro de reservas para um computador, salvando a data e o dia da reserva.

Atores: Administrador.
Prioridade: Importante.
----------------------------------------------------------
[RF007] Calendário de reservas

O sistema possuirá um calendário de reservas, mostrando o dia, a hora da reserva e o cliente.

Atores: Administrador.
Prioridade: Importante.
----------------------------------------------------------

Requisitos não funcionais:

[RNF001] Acesso

O Sistema deve estar disponível para acesso do administrador sempre que necessário.
.
Prioridade: Essencial.
----------------------------------------------------------
[RNF002] Desempenho

O Sistema deve ser otimizado para gerar respostas rápidas, minimizando o tempo de carregamento do software.

Prioridade: Desejável.
----------------------------------------------------------
[RNF003] Confiabilidade

O Sistema deve ser capaz de lidar com falhas no software e no hardware de forma resiliente de forma que sempre garanta a disponibilidade do programa. 

Prioridade: Essencial.
----------------------------------------------------------
[RNF005] Dados

O Sistema deve ser capaz de armazenar todos os dados cadastrados pelo administrador.

Prioridade: Essencial.
----------------------------------------------------------
[RNF005] Segurança 

O Sistema deve pedir uma senha para que o programa seja acessível. E deve ser capaz de identificar e validar a senha caso esteja correta.

Prioridade: Desejável.
----------------------------------------------------------
[RNF006] Conexão com a Internet 

O Sistema deve ser capaz de fazer conexão com a internet

Prioridade: Essencial
----------------------------------------------------------

# Casos de uso

[USC001] Login
[USC002] Menu
[USC003] Computadores em uso
[USC004] Tempo de clientes
[USC004] Identificar o valor a ser pago
[USC005] Cadastrar cliente
[USC006] Registrar reserva
[USC007] Conferir calendário de reserva

Fluxo principal:

[USC001]
1. O sistema solicita um login	
2. O usuário insere a o login de administrador
3. O sistema verifica o login
[USC002]
4. O sistema exibe o menu
[USC003]
5. O sistema exibe os computadores em uso no momento
6. O usuário retorna ao menu




