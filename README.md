# Understanding DataGraph

Code created for article "Understanding Mulesoft Anypoint DataGraph" at timestampits.com

## Configure APIs on your Anypoint Platform

1. Upload the API Specs at `specs` folder on Exchange;
2. On API Manager, manage each API and copy its Autodiscovery API ID;
3. Import each API Impl on Anypoint Studio and point each API Spec. Refer the [docs](https://docs.mulesoft.com/studio/7.6/sync-imported-api-specifications-design-center) if needed;
4. Set each Autodiscovery API ID on Global Elements » api.autodiscovery Global Property;
5. Publish each API on Runtime Manager; Refer the [docs](https://docs.mulesoft.com/runtime-manager/deployment-strategies) if needed;
6. Add them to Unified Schema at DataGraph as explained on the article.
