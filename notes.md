# Skoonner 
## Dev
[http://10.180.140.38:8082/k8s](http://10.180.140.38:8082/k8s)

# SOAP-UI
0. Buscar SOAP UI
1. Clic boton SOAP
2. Clic "initial WSDL" Buscamos el WSDL
3. You can search the endpoint (ClienteNatural)
4. Wait for the request
5. Clic in XML
6. Copy the answeer
7. Right Clic in the name that was under the file name 
8. Generate MockService
9. Remove the word mock in the path file
10. Clic in the name that is next to the green row
11. Clic play
12. clic in the green rows
13. Copy the path
14. Go to Visual Studio
15. Right clic in the project name 
16. Add "Servicio conectado"
17. Clic in the plus icon in the second section (OPEN API, WCF ...)
18. Clic WCF
19. Click next
20. paste the URL
21. Clic ir
22. next, next, finish
23. For implement see bi bussiness 390, search this "services.AddSingleton<wsCIFXNIT>" in all project



Check point Endpoint Security

Github key
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

Jaeger UI
http://10.180.140.38:8081/search

CloudWatch log Filters
Group
fluent-bit-cloudwatch-empresasgt

fields @timestamp, @message, @logStream
| filter @logStream like 'business' and @message like 'tracking'

fields @timestamp, @message, @logStream
| filter  @message like 'tracking'

dotnet
dotnet watch => run with swagger UI

Skooner QA
http://10.180.76.68:8081/k8s/#!

Skooner DEV
http://10.180.140.38:8082/k8s/#!workload

Skonner Dev Token
Github key
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

Jaeger UI
http://10.180.140.38:8081/search

CloudWatch log Filters
Group
fluent-bit-cloudwatch-empresasgt

fields @timestamp, @message, @logStream
| filter @logStream like 'business' and @message like 'tracking'

dotnet
dotnet watch => run with swagger UI

Skooner QA
http://10.180.76.68:8081/k8s/#!

Skooner Token QA
eyJhbGciOiJSUzI1NiIsImtpZCI6IlNXcWJCeFpoTWpEbHBwS2Zua0RfaDYwZDhVRm12aW92YVZ0V2ZkeUhoVzAifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJkZWZhdWx0Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZWNyZXQubmFtZSI6InNrb29uZXItc2EtdG9rZW4tNmw3cTkiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoic2tvb25lci1zYSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImZiMDhhYTY5LTZkYzQtNGE3OS04MzkxLTE2MWJhNWYwNmE1OCIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDpkZWZhdWx0OnNrb29uZXItc2EifQ.dP6e3zNJQHBxDbdNavAq2kaU552owzkoVZ9IEpukFxjQQ84ejZNhmqE8OuMLh3YjxhQxNZO-8bapXAAdPU1KLKLqlkdwZezFjXk5ZBkGtKYn8MfY3HlnDAQ8Bw5t0v6fqdOIPLAdXlpBFyrj3NLYkQ3eZA25_ZMbQ1tOZkpt3vt1gdqK_Gj383x0p3giHa1Sh3wDqRictIuvBXfpFmPf7s_eMsGjFNHog8s8gabZrSt_cmkSs7nJq6yqOXoc91snj2vMz6Z8BuF8RjRzduFjZ4Wv3ZLYOKOY3zJ6-H8mfGe-cJCI06VnimA6Ta_tXxlL7figknjuA7w7CpPsUXlJXw


Skooner DEV
http://10.180.140.38:8081/k8s/#!workload

Skooner Token DEV
eyJhbGciOiJSUzI1NiIsImtpZCI6IkNoNTNRRWJONTdaSU9IZ0dfM3JXdHNuMmowSDlfQU5ZY3NlSkctQ3ZZd1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJkZWZhdWx0Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZWNyZXQubmFtZSI6InNrb29uZXItc2EtdG9rZW4tbWxkbGciLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoic2tvb25lci1zYSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjFmNzc4ZDljLTk4NzktNDczMi04MzJhLWNmNmRiZTcxMjRmZiIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDpkZWZhdWx0OnNrb29uZXItc2EifQ.ZuCkYPctjzRqHP0sqK29QlPyJO1jiwAEnHIZQz3arXuap8ylSIS9Q9DUrNm2lv63AZgMZT8ZNW58de1Ain0XLgqKuZtUN-6Q_MKUaifaoyY7MLdH91TNzG4TAh0HRvtXHZ7MBSbS7_fHSjGo_I-3eF0hPunollE5QoNkwArusXdKPhMq9-p1c8Jc4eWUiX9_TwCjQehrM0SU0v14RU_Tb1eNztAzrCH_Iabh7BK7M8EGertl64SknkCW-XGI94iDcIa_EAbL9Eg35UJna1AgbKKbyxLVwdpsszqxm09chENB9Suqw_BO5nKII7_dV3kOQ7hdwoG5_3fgSbgg49Qiag

Comands
printenv display enviroments

dotnet ef migrations add INITIAL --context=DevMigrationContext -o ./Migrations/DevMigration/
dotnet ef database update --context=DevMigrationContext

git stash list

git stash show

git stash show -p

git stash show -p stash@{1} OR git stash show -p 1 












INSERT INTO

public.deb_card(

id,

kit_identifier,

expiry_date,

card_digits,

deb_card_order_id,

cat_card_status_id,

cat_agent_id,

active,

created_at,

updated_at,

deleted_at

)

VALUES

(6051,000437,'11/2027',4598,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6052,000442,'11/2027',4648,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6053,000456,'11/2027',4788,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6054,000461,'11/2027',4838,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6055,000475,'11/2027',4978,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6056,000480,'11/2027',5025,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6057,100432,'11/2027',4549,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6058,100446,'11/2027',4689,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6059,100451,'11/2027',4739,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6060,100465,'12/2027',4879,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6061,100470,'12/2027',4929,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6062,200436,'12/2027',4580,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6063,200441,'12/2027',4630,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6064,200455,'12/2027',4770,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6065,200460,'12/2027',4820,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6066,200479,'12/2027',5017,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6067,300445,'12/2027',4671,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6068,300450,'12/2027',4721,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6069,300469,'12/2027',4911,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6070,300474,'12/2027',4960,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6071,400435,'12/2027',4572,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6072,400440,'12/2027',4622,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6073,400459,'12/2027',4812,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6074,400464,'12/2027',4861,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6075,400478,'12/2027',5009,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6076,500449,'12/2027',4713,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6077,500454,'12/2027',4762,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6078,500468,'12/2027',4903,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6079,500473,'12/2027',4952,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6080,600439,'12/2027',4614,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6081,600444,'12/2027',4663,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6082,600458,'12/2027',4804,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6083,600463,'12/2027',4853,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6084,600477,'12/2027',4994,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6085,700434,'12/2027',4564,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6086,700448,'12/2027',4705,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6087,700453,'12/2027',4754,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6088,700467,'12/2027',4895,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6089,700472,'12/2027',4945,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6090,800438,'12/2027',4606,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6091,800443,'12/2027',4655,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6092,800457,'12/2027',4796,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6093,800462,'12/2027',4846,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6094,800476,'12/2027',4986,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6095,800481,'12/2027',5033,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6096,900433,'12/2027',4556,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6097,900447,'12/2027',4697,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6098,900452,'12/2027',4747,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6099,900466,'12/2027',4887,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null),

(6100,900471,'12/2027',4937,7,2,null,true,'2023-10-31 11:17:57.510417-06',null,null);
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU2NjIyODgzMiwtMjEzNzM3OTQyNywtMT
M3NjY3Nzk3NywzMzA2NzcyOTIsODQ3MTY2MTQ2LDIzNzkzNjc2
MSwtMTU3MTI4MDUyLC04MDcwNDc0ODMsMTg3OTIyOTI0MSwtNz
M5MTg4ODkwLDIyNTUzMjMwNCwzNzI0NzI2MzBdfQ==
-->