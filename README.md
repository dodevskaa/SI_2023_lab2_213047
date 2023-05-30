Anja Dodevska, 213047

![CFG](https://github.com/dodevskaa/SI_2023_lab2_213047/assets/129993335/52d5bdf9-b609-41c6-ad96-da8673f9f9da)

Цикломатската комплексност е 11. Се пресметува на 3 начини:
1) Се бројат регионите
2) (Број на ребра - број на јазли) + 2
3) Предикатни јазли + 1

Според Every Branch критериумот има 5 тест случаи:
1) со корисник null
2) no username valid&existing email, втор корисник, валиден пасворд со карактер кој не се наоѓа на прва позиција
3) има username, email нема @, пасворд е помал од 8 (pasw<8)
4) username се совпаѓа, email не се совпаѓа, пасворд има празно место
5) username/email не е битно, пасворд нема specialcharacter

Според Multiple Condition критериумот за условот if (user==null || user.getPassword()==null || user.getEmail()==null) има 4 тест случаи:
1) user = null T
2) user != null, pasw = null F T
3) user != null && pasw != null, email = null F F T
4) nitu eden ne e null F F F

