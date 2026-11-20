# Trilha PM² Advanced

Trilha de preparação de Gino Terentim para a certificação PM² Advanced da PM² Alliance: oito estações no ciclo Training from the Back of the Room, revisão espaçada, simulados no formato oficial e um tutor que responde consultando o texto oficial do PM².

**Acesso:** https://ginoterentimjr.github.io/trilha-pm2-advanced/

## O que a página oferece

- **Trilha e estações:** oito estações (Conexão, Conceitos, Prática e Conclusão), com rodadas de até 25 questões por estação.
- **Revisão:** 149 flashcards em cinco caixas de repetição espaçada (1, 3, 7, 14 e 30 dias).
- **Simulado:** banco de 292 questões em inglês; simulado completo (70 em 60 minutos) e minissimulado (20 em 17 minutos), com a distribuição oficial e correção comentada; registro do simulado preparatório oficial (exam.pm2.center).
- **Tutor:** consulta o PM² Guide v3.1, os 33 templates v3.1 e as notas de mudança antes de responder e cita a página ou o template. Explica questões erradas, faz perguntas no estilo da prova e analisa os simulados.
- **Consulta e Plano:** RASCI completo do guia e as duas cadências de estudo.

## Privacidade e conexões

- Este repositório contém apenas código, documentos de estudo e material público da Comissão Europeia. Nenhum dado pessoal fica aqui.
- O progresso é gravado no repositório **privado** de dados (padrão: `ginoterentimjr/conducao-dados`, pasta `trilha-pm2-advanced/progresso.json`), pela API do GitHub, com o token fine-grained informado em **Conexões**.
- O tutor usa a chave da API da Anthropic informada em **Conexões**. Chave e token ficam só no `localStorage` do navegador. Como a página de condução está no mesmo endereço (`ginoterentimjr.github.io`), a trilha reaproveita a chave e o token que já estiverem guardados por ela no mesmo navegador.
- Na versão publicada no Claude (claude.ai/artifact/QLowzmtA5domE2roSiDMx1), o progresso fica na conta do Claude e o tutor funciona pela própria conta, sem chave.

## Estrutura

```
index.html                       curso completo (questões, cartões, estações, tutor e corpus de busca)
documentos/                      Plano de Estudos e Mapa de Cobertura (PDF)
material/                        publicações oficiais da Comissão Europeia
material/PM2 Artefacts 3.1 (33 templates)/
```

## Fontes e licenças

- PM² Project Management Methodology Guide 3.1, PM² Project Artefacts v3.1, notas de mudança e PM² Methodology Overview: © European Union. Reprodução e reuso autorizados com citação da fonte; documentos licenciados sob CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). O logotipo PM² é propriedade da União Europeia.
- O corpus de busca do tutor reproduz o texto dessas publicações, com a fonte indicada em cada trecho.
- Não estão neste repositório, por serem de terceiros: o PM² Certification Handbook (consultar em pm2alliance.eu) e os Free Preparatory Exams (na plataforma exam.pm2.center, com conta gratuita).
- Questões, cartões, estações, plano e mapa de cobertura: Gino Terentim · Rethinking Learning.
