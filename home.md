# Ambiente de processamento BB Cloud

\#interna \#ditec

Este documento tem por objetivo disponibilizar informações sobre o ambiente de processamento em nuvem do Banco do Brasil.


<div style="text-align: justify">

<table width="100%" cellspacing="0" cellpadding="0">
 <tr>
    <td width="33%"><img width="35px" src="img/kubernetes.svg"/><b style="font-size:30px">Paas</b></td>
    <td width="33%"><img width="35px" src="img/azure.svg"/><b style="font-size:30px">SRE</b></td>
    <td width="33%"><img width="35px" src="img/azure.svg"/><b style="font-size:30px">Nuvem Pública</b></td>
 </tr>


 <tr>
    <td width="25%" font-size="20px">Documentação da plataforma de processamento de microserviços no Banco do Brasil
    </td>
    <td width="25%" font-size="20px">Documentação sobre Engenharia de Confiabilidade de Sites no Banco do Brasil
    </td>
    <td width="25%" font-size="20px">Documentação relativa ao processo de adoção de Clouds Públicas no Banco do Brasil
    </td>
 </tr>



<tr>

<td style="text-align:top">

- [Visão Geral](./documentos/01-visao-geral)
- [Rancher](https://fontes.intranet.bb.com.br/psc/psc_releases_sustentacao/-/blob/master/README.md)
- [Openshift](https://fontes.intranet.bb.com.br/psc/psc_releases_sustentacao/-/blob/master/README.md)
- [Google Kubernetes Engine - GKE](https://fontes.intranet.bb.com.br/scn/publico/atendimento/-/wikis/home)
- [Azure Kubernetes Service - AKS](https://fontes.intranet.bb.com.br/scn/publico/atendimento/-/wikis/home)

</td>

<td>

- [Visão Geral](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/0-Conceitos)
- [Conceitos](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/0-Conceitos)
- [Primeiros Passos](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/1-Primeiros-Passos)
- [Jornada Crítica](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/4-Jornada-Cr%C3%ADtica-do-Usu%C3%A1rio)
- [Observabilidade](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/5-Stack-de-Monitora%C3%A7%C3%A3o-e-Telemetria)
- [Piloto SRE no Banco do Brasil](https://fontes.intranet.bb.com.br/psc/publico/atendimento/-/wikis/Guia-para-SRE-no-Banco-do-Brasil/6-Gest%C3%A3o-de-Incidentes-e-Eventos)

</td>


<td>

- [Visão Geral](#serviços-de-computação-em-nuvem-visão-geral)
- [Serviços Contratados](#serviços-de-computação-em-nuvem-serviços-contratados)
- [Iniciativas em Atendimento](#serviços-de-computação-em-nuvem-iniciativas)
- [Atendimento e Suporte](#serviços-de-computação-em-nuvem-atendimento-e-suporte)
- [Perguntas Frequentes](#serviços-de-computação-em-nuvem-perguntas-frequentes)
- [Atendimento de Incidentes](#serviços-de-computação-em-nuvem-atendimento-de-incidentes)
- [Roteiros](#serviços-de-computação-em-nuvem-roteiros)

</td>


</tr>
</table>
</div>



<div style="text-align: justify">

<table width="100%" cellspacing="0" cellpadding="0">
 <tr>
    <td width="25%"><img width="35px" src="img/suporte.svg"/><b style="font-size:30px">Suporte</b></td>
    <td width="25%"><img width="35px" src="img/welcom.svg"/><b  style="font-size:30px">Bem vindo</b></td>
    <td width="25%"><img width="35px" src="img/google.svg"/><b  style="font-size:30px">Link Úteis</b></td>
 </tr>


 <tr>
    <td width="25%">Atendimento a usuários da plataforma, além de acesso a roteiros, incidentes, procedimentos e ferramentas.
    </td>
    <td width="25%">Onboarding de novos funcionários, acesso a cursos, guildas, trilhas de aprendizagem e outros links úteis.
    </td>
    <td width="25%">Links úteis.
    </td>
 </tr>



<tr>

<td>

- [Roteiro de configuração do kubectl](./documentos/01-visao-geral)
- [Atendimento ao Desenvolvedor](./documentos/01-visao-geral)
- [Atendimento às Issues da Plataforma (infra)](./documentos/02-contratacao-e-acionamentos)
- [Resolução de Incidentes ](https://fontes.intranet.bb.com.br/psc/publico/monitoracao/-/blob/master/incidentes)
- [Roteiros](./documentos/04-gestao-financeira)
- [Dúvidas Frequentes](./documentos/05-servico-de-kubernetes)
- [Ofertas](./documentos/06-servicos-de-rede-e-seguranca)
- [Artigos](./documentos/07-servicos-de-computacao)

</td>

<td>

- [Visão Geral](./documentos/01-visao-geral)
- [Contratação e Acionamentos](./documentos/02-contratacao-e-acionamentos)
- [Gestão de Acesso](./documentos/03-gestao-de-acesso)
- [Gestão Financeira](./documentos/04-gestao-financeira)
- [Serviços de Kubernetes](./documentos/05-servico-de-kubernetes)
- [Serviços de Redes e Segurança](./documentos/06-servicos-de-rede-e-seguranca)
- [Serviços de Computação](./documentos/07-servicos-de-computacao)
- [Serviços de Armazenamento](./documentos/08-servicos-de-armazenamento)
- [Serviços de IA e Cognitivos](./documentos/09-servicos-de-ia-e-cognitivos)

</td>


<td>

- [Links de acesso Argocd](./documentos/02-contratacao-e-acionamentos)
- [Links de acesso Rancher](./documentos/03-gestao-de-acesso)
- [Links de acesso Openshift](./documentos/04-gestao-financeira)
- [Links de acesso GKE](./documentos/05-servico-de-kubernetes)
- [Links de acesso AKS](./documentos/06-servicos-de-rede-e-seguranca)
- [Links de acesso Monitoração](./documentos/06-servicos-de-rede-e-seguranca)
- [Links de acesso demais ferramentas](./documentos/08-servicos-de-armazenamento)

</td>

</tr>
</table>
</div>


