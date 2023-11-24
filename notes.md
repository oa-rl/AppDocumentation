# Skoonner 
## Dev
[http://10.180.140.38:8082/k8s](http://10.180.140.38:8082/k8s)

# CloudWatch log Filters
## Group
fluent-bit-cloudwatch-
## Query
fields @timestamp, @message, @logStream
| filter @logStream like 'business' and @message like 'tracking'

fields @timestamp, @message, @logStream
| filter  @message like 'tracking'

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

# Migracion

## Add migration
dotnet ef migrations add INITIAL --context=DevMigrationContext -o ./Migrations/DevMigration/

## Update migration
dotnet ef database update --context=DevMigrationContext

Check point Endpoint Security

Github key
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

Jaeger UI
http://10.180.140.38:8081/search




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


gpupdate /force

# Textract

## Controller

using  Amazon.Textract.Model;

  

namespace  bi_api_business.ExternalServices.AWS.Interface

{

public  interface  IAWSTools

{

Task<Dictionary<string, List<string>>> TextTrackAsync(AnalyzeDocumentRequest  request);

}

}


## Service
using  Amazon.Textract;

using  Amazon.Textract.Model;

using  bi_api_business.ExternalServices.AWS.Interface;

  

namespace  bi_api_business.ExternalServices.AWS.Implementation

{

public  class  AWSToolsImpl : IAWSTools

{

private  AmazonTextractClient  _textractClient  =  new  AmazonTextractClient();

  

public  async  Task<Dictionary<string, List<string>>> TextTrackAsync(AnalyzeDocumentRequest  request)

{

request.FeatureTypes  =  new  List<string> { "FORMS" };

Dictionary<string, dynamic> key_map  =  new  Dictionary<string, dynamic>();

Dictionary<string, dynamic> value_map  =  new  Dictionary<string, dynamic>();

Dictionary<string, dynamic> block_map  =  new  Dictionary<string, dynamic>();

foreach (Block  block  in (await  _textractClient.AnalyzeDocumentAsync(request)).Blocks)

{

string  block_id  =  block.Id;

block_map[block_id] =  block;

if (block.BlockType  ==  "KEY_VALUE_SET")

{

if (block.EntityTypes.Contains("KEY"))

{

key_map[block_id] =  block;

}

else

{

value_map[block_id] =  block;

}

}

}

  

return  GetKvRelationship(key_map, value_map, block_map);

}

  

public  static  Dictionary<string, List<string>> GetKvRelationship(Dictionary<string, dynamic> keyMap, Dictionary<string, dynamic> valueMap, Dictionary<string, dynamic> blockMap)

{

Dictionary<string, List<string>>?  kvs  =  new();

foreach (KeyValuePair<string, dynamic> kvp  in  keyMap)

{

Block  keyBlock  =  kvp.Value;

Block?  valueBlock  =  FindValueBlock(keyBlock, valueMap);

string  key  =  GetText(keyBlock, blockMap);

string  val  =  GetText(valueBlock, blockMap);

if (!kvs.ContainsKey(key))

{

kvs[key] =  new  List<string>();

}

kvs[key].Add(val);

}

return  kvs;

}

  

public  static  Block?  FindValueBlock(Block  keyBlock, Dictionary<string, dynamic> valueMap)

{

Block  valueBlock  =  new();

List<Relationship> temp  =  keyBlock.Relationships;

foreach (Relationship  relationship  in  keyBlock.Relationships)

{

if (relationship.Type  ==  "VALUE")

{

foreach (string  valueId  in  relationship.Ids)

{

valueBlock  =  valueMap.Where(keyPariValue  =>  keyPariValue.Key  ==  valueId).FirstOrDefault().Value;

}

}

}

return  valueBlock;

}

  

public  static  string  GetText(Block  result, Dictionary<string, dynamic> blocksMap)

{

string  text  =  "";

if (result.Relationships  is  not  null)

{

foreach (Relationship  relationship  in  result.Relationships)

{

if (relationship.Type  ==  "CHILD")

{

foreach (string  childId  in  relationship.Ids)

{

Block  word  =  blocksMap[childId];

if (word.BlockType.Value  ==  "WORD")

{

text  +=  word.Text  +  " ";

}

if (relationship.Type  ==  "SELECTION_ELEMENT")

{

if (word.SelectionStatus.Value  ==  "SELECTED")

{

text  +=  "X ";

}

}

}

}

}

}

return  text;

}

  

}

}




// foreach (KeyValuePair<string, List<string>> row in documentDPI)

// {

// string key = row.Key.ToLower().Trim();

// foreach (string word in key.Split(" "))

// {

// if (dictionaryDPI.Contains(word))

// {

// Console.WriteLine(row);

// dpiFound = string.Join("", row.Value.FirstOrDefault()!.ToCharArray().Where(c => !char.IsWhiteSpace(c)));

// }

// }

// }







<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMzM2Njk3MjEsLTIwMTM0NzQ2OTksMj
A0MzE5MjMxNCwtODM4OTA5MTY3LC01NDQxMTUyOTYsMTU2NjIy
ODgzMiwtMjEzNzM3OTQyNywtMTM3NjY3Nzk3NywzMzA2NzcyOT
IsODQ3MTY2MTQ2LDIzNzkzNjc2MSwtMTU3MTI4MDUyLC04MDcw
NDc0ODMsMTg3OTIyOTI0MSwtNzM5MTg4ODkwLDIyNTUzMjMwNC
wzNzI0NzI2MzBdfQ==
-->