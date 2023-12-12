# Sistema de Controle de Horas Trabalhadas

## Descrição

Este é um programa Java simples para controle de horas trabalhadas de funcionários. O sistema permite que os funcionários registrem suas horas de trabalho diárias, especificando a ocupação desempenhada durante um determinado período. O administrador tem a capacidade de cadastrar funcionários, ocupações e gerenciar o sistema.

## Funcionalidades

- Cadastro de Funcionários: O administrador pode cadastrar funcionários, incluindo nome, matrícula e senha.
- Cadastro de Ocupações: O administrador é responsável por cadastrar ocupações, identificadas por um código e um nome.
- Registro de Horas e Ocupação: Os funcionários podem registrar suas entradas e saídas diárias, especificando a ocupação desempenhada.
- Segurança e Acesso: Apenas funcionários cadastrados pelo administrador podem acessar o sistema, utilizando matrícula e senha.
- Relatórios: O sistema gera relatórios com base na matrícula do funcionário ou na ocupação desempenhada durante um período de datas.
- Horário de Brasília: Os registros de horas são sincronizados com um servidor confiável que utiliza o horário de Brasília.

## Estrutura do Projeto

O projeto está organizado em pacotes (packages) para melhor modularidade e organização. A estrutura inclui pacotes para administração, autenticação, dados, modelos, serviços, interface do usuário e utilitários.
