## PLUGIN bot-plugin-services

### Managed intents
 
| Intent | Description | Entities | Example Sentences | Detailed Sentences | Trained | Used by | FPA APIs
| --- | --- | --- | --- | --- | --- | --- | --- |
| <sub>tef.intent.services.find</sub> | <sub>The user wants to find more information about all her services or a particular service </sub> | <sub>tef.service tef.phonenumber </sub>| <sub>"Show my Services", "Show the details of Fusion", "Show me the services of my line 666-666-666"</sub> | <sub>Draft</sub> | <sub>NO</sub> | <sub>[YOTBOT-7](https://jirapdi.tid.es/browse/YOTBOT-7) [YOTBOT-8](https://jirapdi.tid.es/browse/YOTBOT-8)</sub> | <sub>[service](https://demo-pdb-web-01.tid.es/v1/ui/#!/default/app_get_user_services)</sub>
 
### Entities
 
| Intent | Description | Example |
| --- | --- | --- |
| tef.service | The name for a Telefonica Service | fusion |
| tef.phonenumber | A phone number | 666666666 |


## PLUGIN bot-plugin-bill

| Intent | Description | Entities | Example Sentences | Detailed Sentences | Trained | Used by | FPA APIs
| --- | --- | --- | --- | --- | --- | --- | --- |
| <sub>tef.intent.bill.check</sub> | <sub>The user wants to find more information about her bill or a bill item </sub> | <sub>tef.service tef.phonenumber builtin.money </sub>| <sub>"How much is my bill", "Show the details of Other Concepts", "Why am I paying €50 for international calls"</sub> | <sub>Draft</sub> | <sub>NO</sub> | <sub>[YOTBOT-17](https://jirapdi.tid.es/browse/YOTBOT-17) [YOTBOT-15](https://jirapdi.tid.es/browse/YOTBOT-15)</sub> | <sub>[invoice](https://demo-pdb-web-01.tid.es/v1/ui/#!/default/invoicing_get_invoice)</sub>
 
### Entities
 
| Intent | Description | Example |
| --- | --- | --- |
| tef.service | The name for a Telefonica Service | fusion |
| tef.phonenumber | A phone number | 666666666 |
| builtin.money | A monetary amount | €50 |
