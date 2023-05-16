# Entity Relationship Soccer

## Entities
In our case we have put 13 entities:  
1. Players
2. Teams
3. Stadium
4. Partidos
5. Goles
6. Entradas
7. Personas
8. Seat
9. Presidente
10. Seasons
11. Portero
12. Jugador de campo
13. Arbitro
## Atributes, Primary Key
As you can see in the image, each entity has at least 1 attributes and the primary keys are usually id/code and it is in bold and underlined. For example:  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/d204a8f0-149d-4721-a3e7-abb195a06401)  
## Relationships, relationships with attributes
Here I have a relationships with attribute that is related to entries and people:  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/ca37123a-f876-4e74-bd3a-024581c57587)  
and relationship we have several like this:  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/bbd5d5e4-92be-4a7f-b6b0-8979e2ab427c)  
## Roles in recursive relationships
Here we have roles such as Partido with Aribtraje  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/6074dc36-0a0c-4839-9d00-703ea90def82)  
or Players idol Players:  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/c8485e0e-3296-429d-be8b-7b080ff5bc02)  
## (optional) Ternary relationships
Here we put the entities Teams, Presidente and Seasons as a ternary relationship  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/8775ff16-314e-4058-9843-f0ad8812b240)  
## Cardinalities
Here they are put in the whole entity relationship where can be One-to-one, One-to-many, Many-to-many.  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/1a9da220-1bf8-43a0-b90e-c1373d4dd76b)## Total and partial participation 
Here in general they are more partial participation than total participation  
## Weak entities 
Here we have as Weak entities: Stadium and Seat  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/6bf060cf-6df4-401a-9f0f-c5937a73c9b1)  
since without seats it is not considered a stadium  
## Generalization-specialization. Overlapping/disjoint. Total/partial.
Here we put as generalization and specialization the position played by the players who in this case goalkeeper or outfield player  
![image](https://github.com/kevin-coaquira/entidad-relacional/assets/91737963/1f3e2996-3a69-4fae-852f-06dde66b0a32)
