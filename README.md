# 5g-stack-tcc

Projeto de Trabalho de Conclusao de Curso (TCC) de Gabriel Barbosa Silva Nunes, aluno de Engenharia de Telecomunicacoes na UFRN, focado na construcao e analise de testbeds educacionais para redes moveis 5G Open RAN com ferramentas open source.

## Visao geral

Este repositorio materializa uma proposta de ambiente didatico para estudo pratico de redes 5G. A ideia central e disponibilizar uma infraestrutura virtualizada e reproduzivel que permita observar, configurar e experimentar componentes de uma rede 5G Open RAN com enfase em ensino, pesquisa e prototipacao.

O projeto utiliza implementacoes abertas e virtualizadas para aproximar conceitos teoricos da pratica. Com isso, o testbed permite:

- acompanhar fluxos de sinalizacao da rede 5G;
- capturar e inspecionar pacotes com Wireshark;
- gerar trafego de dados com iperf3;
- estudar conceitos de NFV e SDN em um ambiente controlado;
- apoiar a producao de material didatico e a reproducao de experimentos.

## Objetivos do projeto

Os principais objetivos do projeto sao:

- produzir material didatico de qualidade sobre redes 5G Open RAN;
- documentar a configuracao de testbeds 5G virtualizados;
- oferecer uma base reutilizavel para aulas, laboratorios e pesquisas;
- coletar logs, capturas e resultados de desempenho para analise academica;
- democratizar o aprendizado pratico em redes moveis com tecnologias abertas.

## Publico-alvo

O conteudo do repositorio foi pensado para atender diferentes perfis:

- estudantes de graduacao e pos-graduacao em Telecomunicacoes, Computacao e areas afins;
- pesquisadores interessados em 5G, Open RAN e virtualizacao de funcoes de rede;
- profissionais da industria que desejam explorar SDN, NFV e prototipacao de redes moveis;
- entusiastas que buscam aprender com um ecossistema 5G open source de forma guiada.

## Arquitetura e abordagem

O testbed proposto e totalmente virtualizado. A infraestrutura combina:

- **OpenAirInterface (OAI)** para implementacao do Core 5G e da RAN;
- **Proxmox VE** como plataforma de virtualizacao para hospedar VMs e conteineres;
- **Docker** para empacotar e executar as funcoes de rede com reproducibilidade;
- **Wireshark** para captura e analise detalhada da sinalizacao;
- **iperf3** para geracao e medicao de trafego de usuario.

Essa abordagem permite montar um ambiente flexivel para explorar interacoes entre UE, gNB e Core 5G, observando tanto o plano de controle quanto o plano de usuario.

## Exemplos de atividades e experimentos

Com o ambiente descrito no projeto, e possivel realizar atividades como:

- analise de procedimentos de conexao e registro da UE;
- observacao de mensagens NAS, RRC e NGAP;
- captura de trafego em interfaces da rede virtualizada;
- testes de throughput, latencia e perda de pacotes;
- coleta de logs para estudo de falhas, desempenho e conformidade com especificacoes.

## Contribuicao academica

O projeto busca unir teoria e pratica em redes moveis por meio de uma infraestrutura aberta e documentada. Alem de apoiar o aprendizado, o repositorio serve como base para reproducao de experimentos, geracao de evidencias empiricas e expansao colaborativa de testbeds educacionais em 5G.

## Referencias citadas no documento-base

- [OpenAirInterface](https://openairinterface.org/)
- [Proxmox Virtual Environment - Wikipedia](https://en.wikipedia.org/wiki/Proxmox_Virtual_Environment)
- [Understanding Network Function Virtualization (NFV)](https://medium.com/@RocketMeUpNetworking/understanding-network-function-virtualization-nfv-775e6a32af58)
- [Software-defined networking - Wikipedia](https://en.wikipedia.org/wiki/Software-defined_networking)
- [Wireshark](https://www.wireshark.org/)
- [iperf - Wikipedia](https://en.wikipedia.org/wiki/Iperf)
