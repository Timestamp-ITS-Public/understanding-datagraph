# Understanding DataGraph

Code created for article "Understanding Mulesoft Anypoint DataGraph" at timestampits.com

## Configure APIs on your Anypoint Platform

1. Clone or download the repo to get API Specs and Impl. `Jar`s to deploy them on Runtime Manager are on Releases section.
2. Upload the API Specs at `specs` folder on Exchange;
3. On API Manager, manage each API and copy its Autodiscovery API ID;
4. Publish each API on Runtime Manager. Before, set each Autodiscovery API ID using api.autodiscovery property, and set org credentials as well. Refer the [deployment strategies docs](https://docs.mulesoft.com/runtime-manager/deployment-strategies) and [configuring credentials docs](https://docs.mulesoft.com/api-manager/2.x/org-credentials-config-mule4#configuring-credentials-in-runtime-manager-for-your-deployed-application) if needed;
5. Add them to Unified Schema at DataGraph as explained on the article. Refer the [datagraph docs](https://docs.mulesoft.com/datagraph/) if needed.
