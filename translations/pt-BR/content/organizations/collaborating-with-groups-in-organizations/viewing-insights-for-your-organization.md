---
title: Exibir informações da organização
intro: 'As informações da organização fornecem dados sobre a atividade, as contribuições e as dependências dela.'
product: '{% data reusables.gated-features.org-insights %}'
redirect_from:
  - /articles/viewing-insights-for-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/viewing-insights-for-your-organization
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Visualizar ideias da organização
permissions: Organization members can view organization insights.
---

Você pode usar informações de atividade da organização para entender melhor como os integrantes da sua organização estão usando o {% data variables.product.product_name %} para colaborar e trabalhar no código. As informações de dependência podem ajudar você a monitorar, reportar e agir de acordo com o uso de código aberto da organização.

{% note %}

**Observação:** Para visualizar os insights da organização, sua organização deverá usar {% data variables.product.prodname_ghe_cloud %}. {% data reusables.enterprise.link-to-ghec-trial %}

{% endnote %}

## Exibir informações de atividade da organização

{% note %}

**Observação:** As ideias da atividade da organização estão atualmente na versão beta pública e são sujeitas a alterações.

{% endnote %}

Com as informações de atividade da organização, é possível exibir visualizações de dados semanais, mensais e anuais de toda a organização ou de repositórios específicos, como atividade de pull requests e problemas, principais linguagens usadas e dados cumulativos sobre onde os integrantes da organização passam o tempo.

{% data reusables.profile.access_org %}
{% data reusables.user-settings.access_org %}
3. No nome da organização, clique em {% octicon "graph" aria-label="The bar graph icon" %} **Insights** (Informações). ![Clique na guia Insights (Informações) da organização](/assets/images/help/organizations/org-nav-insights-tab.png)
4. Como alternativa, no canto superior direito da página, opte por exibir dados do período de **1 semana**, **1 mês** ou **1 ano** mais recente. ![Escolha o período para visualizar informações da organização](/assets/images/help/organizations/org-insights-time-period.png)
5. Ou, no canto superior direito da página, opte por exibir dados de até três repositórios e clique em **Apply** (Aplicar). ![Escolha os repositórios para visualizar informações da organização](/assets/images/help/organizations/org-insights-repos.png)

## Exibir informações de dependência da organização

{% note %}

**Observação:** Certifique-se que você habilitou o [Gráfico de dependências](/code-security/supply-chain-security/understanding-your-software-supply-chain/configuring-the-dependency-graph).

{% endnote %}

Com as informações de dependência, é possível visualizar vulnerabilidades, licenças e outras informações importantes dos projetos de código aberto dos quais a sua organização depende.

{% data reusables.profile.access_org %}
{% data reusables.user-settings.access_org %}
3. No nome da organização, clique em {% octicon "graph" aria-label="The bar graph icon" %} **Insights** (Informações). ![Guia Insights (Informações) na principal barra de navegação da organização](/assets/images/help/organizations/org-nav-insights-tab.png)
4. Clique em **Dependencies** (Dependências) para exibir as que pertencem a esta organização. ![Guia Dependencies (Dependências) na principal barra de navegação da organização](/assets/images/help/organizations/org-insights-dependencies-tab.png)
5. Para exibir informações de dependência para todas as suas organizações do {% data variables.product.prodname_ghe_cloud %}, clique em **My organizations** (Minhas organizações). ![Botão My organizations (Minhas organizações) na guia Dependencies (Dependências)](/assets/images/help/organizations/org-insights-dependencies-my-orgs-button.png)
6. Você pode clicar nos resultados dos gráficos **Consultorias de segurança abertas** e **Licenças** para filtrar por um status de vulnerabilidade, uma licença ou uma combinação dos dois. ![Gráficos de "vulnerabilidades das minhas organizações"](/assets/images/help/organizations/org-insights-dependencies-graphs.png)
7. Também pode clicar em {% octicon "package" aria-label="The package icon" %} **Dependents** (Dependentes) ao lado de cada vulnerabilidade para ver quais dependentes na organização estão usando cada biblioteca. ![Dependentes vulneráveis em My organizations (Minhas organizações)](/assets/images/help/organizations/org-insights-dependencies-vulnerable-item.png)

## Leia mais
 - "[Sobre organizações](/organizations/collaborating-with-groups-in-organizations/about-organizations)"
 - "[Explorar as dependências de um repositório](/github/visualizing-repository-data-with-graphs/exploring-the-dependencies-of-a-repository)"
 - "[Alterando a visibilidade das dicas de dependência da sua organização](/organizations/managing-organization-settings/changing-the-visibility-of-your-organizations-dependency-insights)"{% ifversion ghec %}
- "[Aplicando as políticas de insights de dependência na sua empresa](/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-dependency-insights-in-your-enterprise)"{% endif %}
