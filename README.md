# TRABALHO DE BANDO DE DADOS

Nome:Pedro Wesley Lima de Paiva

```sql
--Questão 01
select * from tabela_paises;
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/d803b09c-1890-4712-9049-716be46a1206)

```sql
--Questão 02
select pais, cidade from tabela_paises where pais = 'Brazil';
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/91b5ab88-b02f-4b1d-a352-0055bed5045c)


```sql
--Questão 03
select pais, regiao, cidade from tabela_paises where regiao = 'Ceará';
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/864d5ad6-6fe8-4a66-a8c4-575eca0ebab2)

```sql
--Questão 04
select count(regiao) as total_regioes from tabela_paises where pais = 'China' group by pais;
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/1f162b61-431f-455d-a8cc-391c096d6529)

```sql
--Questão 05
select count(distinct regiao) from tabela_paises where pais = 'Canada';
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/2820dcfb-fc7b-4e43-895e-b4622a33664e)

```sql
--Questão 06
select count(distinct pais) from tabela_paises;
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/a4ad4fd3-3ef3-4508-82d7-14fc3a0d084b)

```sql
--Questão 07
select count(distinct cidade) from tabela_paises where pais = 'Brazil'
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/4b066e8c-ca52-437d-8e3d-817f654224e6)

```sql
--Questão 08
select count(regiao) as total_regioes from tabela_paises group by pais;
```
![image](https://github.com/byID887766pedro/trabalho.de.bando.dados/assets/129344687/68c241d0-f432-47b0-9140-b23cf8a7f0ef)

```sql
--Questão 09
```

