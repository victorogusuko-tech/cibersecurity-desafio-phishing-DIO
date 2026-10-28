Desafio: Criando um Phishing com Kali Linux

Descrição do Projeto
Este projeto é resultado do desafio prático da plataforma DIO (Digital Innovation One). O objetivo educacional é compreender a mecânica dos ataques de engenharia social, especificamente o Phishing, utilizando a ferramenta Social-Engineer Toolkit (SET) no Kali Linux.

Aviso Legal: Este projeto tem fins estritamente educacionais. As técnicas aqui documentadas foram executadas em ambiente de laboratório controlado para fins de estudo de cibersegurança.

Ferramentas Utilizadas
Sistema Operacional: Kali Linux
Ferramenta de Exploração: Social-Engineer Toolkit (setoolkit)

Conceitos Abordados: 
Engenharia Social, Clonagem de Páginas Web, Captura de Credenciais.
Estrutura do Ataque (Conceitual)
Preparação do Ambiente: Configuração da rede e inicialização do setoolkit.
Seleção do Vetor: Escolha do módulo de engenharia social focado em vetores web (Web Site Attack Vectors).

Método de Clonagem: Utilização do método de clonagem de sites para espelhar a página de login de um serviço alvo (ex: Facebook).
Captura: Simulação da inserção de credenciais pela vítima, demonstrando como os dados em texto claro (ou hashes) são interceptados pelo servidor local do atacante.


Mitigação e Defesa
Para se proteger contra ataques de phishing semelhantes, as seguintes práticas são recomendadas:
Autenticação Multifator (MFA): Exigir uma segunda forma de verificação torna credenciais vazadas insuficientes para o acesso.
Verificação de Domínio: Sempre validar se a URL no navegador corresponde ao domínio oficial do serviço.
Gerenciadores de Senha: Estas ferramentas geralmente não preenchem senhas automaticamente se o domínio da página não corresponder ao registro salvo.
Treinamento de Conscientização: Educar usuários para identificar urgências falsas e e-mails suspeitos (spear phishing).
