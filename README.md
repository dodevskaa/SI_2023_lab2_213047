# Втора лабораториска вежба по Софтверско инженерство
## Ања Додевска, 213047
### Control Flow Graph
![CFG](https://github.com/dodevskaa/SI_2023_lab2_213047/assets/129993335/0b070f6d-e8a1-49e1-91ec-e54b8abfd818)

![CFG](https://github.com/dodevskaa/SI_2023_lab2_213047/assets/129993335/52d5bdf9-b609-41c6-ad96-da8673f9f9da)
### Цикломатската комплексност
Цикломатската комплексност е 11. Се пресметува на 3 начини:
1) Се бројат регионите
2) (Број на ребра - број на јазли) + 2
3) Предикатни јазли + 1
### Every Branch
Every Branch методата ни овозможува да пишуваме тест примери колку што ни се потребни за нашиот код да се посетат сите јазли. Според Every Branch критериумот има 5 тест случаи:
1) username да биде null
2) no username valid&existing email, втор корисник, валиден пасворд со карактер кој не се наоѓа на прва позиција
3) има username, email нема @, пасворд е помал од 8 (pasw<8)
4) username се совпаѓа, email не се совпаѓа, пасворд има празно место
5) username/email не е битно, пасворд нема specialcharacter
### Multiple Condition
Multiple Condition методата ни служи за евалуација на сите јазли во кои се врши одлучување во однос на true или false. Според Multiple Condition критериумот за условот if (user==null || user.getPassword()==null || user.getEmail()==null) има 4 тест случаи:
1) user = null T
2) user != null, pasw = null F T
3) user != null && pasw != null, email = null F F T
4) nitu eden ne e null F F F

