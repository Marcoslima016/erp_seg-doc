

<style>

table {
  table-layout: fixed;
  max-width: 100%;
}

.md-typeset code {
  overflow-wrap: break-word;
}
/* table th:first-of-type {
    width: 10%;
}
table th:nth-of-type(2) {
    width: 10%;
}
table th:nth-of-type(3) {
    width: 20%;
}
table th:nth-of-type(4) {
    width: 20%;
} */
</style>

Lista de tabelas utilizadas no sistema, descrevendo as colunas existentes em cada tabela e as suas relações. 




<!--===================== TABELA USUARIOS  =====================-->
---
##Table Usuarios
###Colunas
| Name | Data type | Descrição |  
|-----------|:-----------:|-----------:|  
| USUARIO_ID | int | Primary key da tabela |
| NOME | string | Nome do usuário |
| EMAIL | string | Email do usuario |

###Relações

| FK Table | PK Table | Column |  Desc  | 
|-----------|:-----------:|:-----------:|-----------:|  
|  |  |  |   | 



<!--===================== TABELA CHIPS  =====================-->
---
##Table Chips
###Colunas
| Name | Data type | Descrição |  
|-----------|:-----------:|-----------:|  
| CHIP_ID | int | Primary key da tabela |
| OPERADORA_ID | string | Operadora de serviços do chip |
| STATUS | string | Status do chip |

###Relações

| FK Table | PK Table | Column |  Desc  | 
|-----------|:-----------:|:-----------:|-----------:|  
|  |  |  |   | 



<br/><br/>
<!--================= TABELA RASTREADPRES  =================-->
---
##Table Rastreadores
###Colunas
| Name | Data type | Descrição |  
|-----------|:-----------:|-----------:|  
| RASTREADOR_ID | int | Primary key da tabela |

<!-- ###Relacão com outras tabelas -->

###Relações

| FK Table | PK Table | Column |  Desc  | 
|-----------|:-----------:|:-----------:|-----------:|  
| [Chips](#table-chips) | Rastreadores | RASTREADOR_ID|   |  
<!-- | Chips | Rastreadores | RASTREADOR_ID|   |  
| Chips | Rastreadores | RASTREADOR_ID|   |   -->



<br/><br/>
<!--==================== TABELA ANTENAS ====================-->
---
##Table Antenas

###Colunas

| Name | Data type | Descrição |  
|-----------|:-----------:|-----------:|  
| | |  |

<!-- ###Relacão com outras tabelas -->

###Relações

| FK Table | PK Table | Column |  Desc  | 
|-----------|:-----------:|:-----------:|-----------:|  
|  |  |  |  |  


<br/><br/>
<!--==================== TABELA ANTENAS ====================-->
---
##Table Chicotes

###Colunas

| Name | Data type | Descrição |  
|-----------|:-----------:|-----------:|  
| | |  |

<!-- ###Relacão com outras tabelas -->

###Relações

| FK Table | PK Table | Column |  Desc  | 
|-----------|:-----------:|:-----------:|-----------:|  
|  |  |  |  |  


