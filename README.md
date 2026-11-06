Levantamento de Requisitos | ConsertaJá
Projeto acadêmico desenvolvido no contexto de Análise e Desenvolvimento de Sistemas, com foco no levantamento e na especificação inicial de requisitos de um sistema para uma assistência técnica.
Sobre o projeto
A ConsertaJá Assistência Técnica é uma empresa fictícia de pequeno porte que realiza manutenção e reparo de computadores, notebooks e periféricos.

O estudo propõe um sistema web para centralizar informações de clientes, equipamentos, agendamentos e ordens de serviço, facilitando a organização dos atendimentos e o acompanhamento dos reparos.
Nota: a empresa e a entrevista descritas neste projeto são fictícias/simuladas e foram elaboradas exclusivamente para fins acadêmicos.

Problema identificado
O registro de solicitações por mensagens e anotações manuais pode provocar:
- Conflitos de horários;
- Perda ou dificuldade de localização de informações;
- Falta de histórico organizado dos clientes e equipamentos;
- Dificuldade para acompanhar o andamento dos reparos;
- Falhas de comunicação sobre diagnósticos, orçamentos e prazos.
Objetivo da solução
Propor um sistema que permita organizar o fluxo de atendimento da assistência técnica, desde o agendamento até a conclusão e entrega do equipamento.
Técnica de elicitação
A técnica escolhida foi a entrevista semiestruturada, pois permite compreender os procedimentos da empresa por meio de perguntas previamente elaboradas, mantendo espaço para aprofundar assuntos relevantes.

Para este trabalho, a entrevista foi simulada com base no cenário proposto. Em uma situação real, seria necessário entrevistar o responsável pelo atendimento e os profissionais técnicos para validar as necessidades levantadas.
Requisitos funcionais
Código	Descrição
RF01	Permitir cadastrar, consultar, alterar e inativar clientes.
RF02	Permitir registrar equipamentos com tipo, marca, modelo e número de série, quando disponível.
RF03	Permitir criar, consultar, alterar e cancelar agendamentos, registrando data, horário, cliente e motivo do atendimento.
RF04	Gerar uma ordem de serviço vinculada ao cliente e ao equipamento.
RF05	Permitir atualizar o status da ordem de serviço: recebido, em avaliação, aguardando aprovação, em reparo, concluído e entregue.
RF06	Registrar diagnóstico, orçamento e observações do serviço.
RF07	Permitir consultar o histórico de atendimentos por cliente e equipamento.


Requisitos não funcionais
Código	Descrição
RNF01	Disponibilizar uma interface responsiva para computadores, tablets e celulares.
RNF02	Exigir autenticação por usuário e senha para acessar funções administrativas.
RNF03	Restringir o acesso às informações conforme o perfil do usuário.
RNF04	Armazenar as informações em banco de dados e realizar backups periódicos.
RNF05	Apresentar as informações de forma clara e permitir localizar clientes e ordens de serviço em poucos segundos, em condições normais de uso.
RNF06	Utilizar comunicação segura por HTTPS quando disponibilizado em ambiente web.


Fluxo básico do sistema
1. O atendente cadastra ou localiza o cliente.
2. O equipamento é registrado e o atendimento é agendado.
3. O sistema gera uma ordem de serviço.
4. O técnico registra o diagnóstico e atualiza o andamento do reparo.
5. Após a conclusão, o atendimento é atualizado para entregue.
Escopo inicial
A proposta contempla:
- Cadastro e consulta de clientes;
- Cadastro de equipamentos;
- Agendamento de atendimentos;
- Abertura e acompanhamento de ordens de serviço;
- Registro de diagnósticos, orçamentos e histórico.
Este repositório documenta a etapa de levantamento de requisitos. Não contém uma aplicação implementada ou código executável.
Considerações finais
O levantamento demonstra como a identificação de problemas operacionais pode orientar a criação de uma solução tecnológica. O sistema proposto busca reduzir falhas de organização, melhorar o acompanhamento dos serviços e centralizar as informações da assistência técnica.

Os requisitos apresentados representam uma primeira versão e devem ser validados com os usuários antes do desenvolvimento.
Área: Análise e Desenvolvimento de Sistemas
Tema: Levantamento de Requisitos
Tipo: Projeto acadêmico
