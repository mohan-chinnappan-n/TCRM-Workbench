# Tableau CRM Workbench Demos

## Topics
- [Dataflow Field Usage](#dffu)
- [Data Connector](#dc)

- [REST Console](#restc)
- [SOQL Console](#soqlc)


- [Limits - TCRM and Platform](#limits)
- [Assets Counts - TCRM ](#ac)

- [dataflow optimization flow](#dfopt))
- [SAQL in REST console](#saql))




- [CLI - Plugin Features](https://www.salesforceblogger.com/2020/11/17/mohans-sfdx-plugin-for-analytics/)
    - Most of the features in CLI Plugin will be available in TCRM Workbench!


<a name="dffu"></a>
## Field Usage for a dataflow
-![DF Field Usage](img/tcrm-wb-main-1.gif)


<a name="dc"></a>
## Data Connectors 
-![Data connectors](img/tcrm-wb-dc-2.gif)

<a name="restc"></a>
## REST Console 
-![REST Console](img/tcrm-wb-restc-3.gif)


<a name="soqlc"></a>
## SOQL Console 
-![SOQL Console](img/tcrm-wb-soqlc-1.gif)
-![Event SOQL Console](img/tcrm-wb-soqlc-2.gif)



<a name="Limits"></a>
## Limits (TCRM and Platform_ 
-![REST Console](img/tcrm-wb-limits-2.gif)

<a name="ac"></a>
## TCRM Asset Counts 
-![TCRM Asset Counts](img/tcrm-wb-assets-1.gif)

<a name='dfopt'></a>
## Dataflow Optimization Flow
-![DF Optimization flow](img/opt/tcrm-df-opt-1.gif)

<a name='saql'></a>
## Running SAQL using REST console
### SAQL
```
{
    "query": "q = load \"0Fb3h0000008sotCAA/0Fc3h0000026d2LCAQ\";q = group q by 'all';q = foreach q generate count() as 'count'; q = limit q 2000;"
  
}
```
-![SAQL using REST Console)(img/saql/saql-1.png)


