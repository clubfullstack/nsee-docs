# Bem-vindo à Documentação de Teste Ambiente Virtual Veritas

Esta página inicialmente tem por finalidade agrupar a documentação base dos testes realizados no laboratório NSEE para Virtualização  dos instrumentos VenSpec-M.

O laboratório NSEE utiliza uma estrutura baseada no código aberto Quick EMUlator (QEMU) para a virtualização de instrumentos aeroespaciais. 

As pesquisas e testes realizados em laboratório anteriormente validaram a possibilidade do desenvolvimento de uma estrutura abrangente utilizando o QEMU para a virtualização de instrumentos aeroespaciais. A seguir estão os principais resultados observados: 

a) Emulação da Arquitetura SPARC e do Processador LEON3: O laboratório NSEE tem realizado avanços significativos na emulação de arquiteturas SPARC e do processador LEON3 utilizando o QEMU. Estes esforços demonstram a capacidade do QEMU em simular arquiteturas complexas, proporcionando uma base sólida para a virtualização de outros instrumentos;

b) Testes com Protocolo SpaceWire e Processador LEON3: O laboratório NSEE também avançou na realização de testes utilizando a arquitetura SPARC e o processador LEON3, agora com foco na utilização do protocolo SpaceWire. Neste contexto, foi desenvolvida uma  arquitetura de comunicação entre o QEMU, que emula o processador LEON3, e um script em Python. O QEMU se comunica via UART com o script, que realiza configurações e insere valores de teste, implementando um loopback utilizando o protocolo SpaceWire. 

- [SPARC-LEON3](sparc.md)
- [SPACE WIRE-LEON3](space_wire.md)
- [Outro JTVEIA](another-doc.md)

nsee-docs/
├── docs/
│   ├── README.md
│   ├── veritas/
│   │   ├── sparc/
│   │   │   ├── documentation.md
│   │   │   └── codes.md
│   │   ├── space-wire/
│   │   │   ├── documentation.md
│   │   │   └── codes.md
├── index.html
├── sidebar.md


