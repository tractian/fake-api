# FAKE API

Para você usar essa API, utilize essa url (<https://my-json-server.typicode.com/tractian/fake-api>).

## END POINTS

### Ativos

>#### Dicionário
>
>status => Estado atual (inAlert = Em Alerta, inOperation = Em Operação, inDowntime = Em Parada)
>healthscore => Saúde em %
>specifications
>>maxTemp => Temperatura Máxima em Celsius
>>power => Potência em kWh
>>rpm => RPM
>metrics
>>totalCollectsUptime => Total de Coletas Uptime(Ligada)
>>totalUptime => Total de Horas de Coletas Uptime(Ligada)
>>lastUptimeAt => Data da Ultima Coleta Uptime(Ligada)
>#### Acessar todos os ativos
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/assets
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/assets>
>
>#### Acessar apenas um ativo
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/assets/:id
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/assets/1>

### Usuários

>#### Acessar todos os usuários
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/users
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/users>
>
>#### Acessar apenas um usuário
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/users/:id
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/users/1>

### Unidades

>#### Acessar todas as unidades
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/units
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/units>
>
>#### Acessar apenas uma unidade
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/units/:id
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/units/1>

### Empresas

>#### Acessar todas as empresas
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/companies
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/companies>
>
>#### Acessar apenas uma empresa
>
>``` bash
>https://my-json-server.typicode.com/tractian/fake-api/companies/:id
>```
>
>Ex: <https://my-json-server.typicode.com/tractian/fake-api/companies/1>
>
