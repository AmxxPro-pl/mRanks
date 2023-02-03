<div align="center">
# mRanks
<h1><p></p>AmxxPro.pl - Paczki & Pluginy CS 1.6<p></p></h1>
<img src="https://github.com/AmxxPro-pl/.github/blob/main/Banner.png"></img>
</div>


### Description
- Rozbudowany system rankingu na serwery CS 1.6
- Sprite rang CS:GO nad głową gracza gdy nacelujesz na przeciwnika.
- Ranking Top8, którzy mają najwięcej zdobytych pkt.

<b>** Dzięki [N1K1Cz](https://github.com/N1K1Cz) za pomoc przy HUD oraz Top8.</b>

### Requirements
- AMXModX 1.9 / AMXModX 1.10

### Configuration
<details>
  <summary><b>mRanks_Core.cfg</b></summary>

```
//============================================================== » mRanks - Core « ==============================================================\\
//                                                              © mpN` | AmxxPro.pl                                                              \\

// » Główne Ustawienia
mRanks_Chat_Tag "Rangi"                             // Prefix na czat ( Rangi - Domyślnie )
mRanks_Flags_Vip "t"                                // Flaga VIP'a ( t - Domyślnie )
mRanks_Extra_Points_Vip "1"                         // Czy VIP ma dostawać dodatkowe pkt? ( 1 - Tak | 0 - Nie )
mRanks_Min_Players "2"                              // Minimalna ilość graczy, aby naliczać pkt
mRanks_Forum "AmxxPro.pl"                           // Nazwa forum wyświetlana w HUD ( AmxxPro.pl - Domyślnie )

// » Zwykły Gracz
mRanks_Kill "1"                                     // Liczba punktów zdobywanych za zabójstwo ( 0 - Jeżeli ma nie dostawać )
mRanks_Kill_Hs "2"                                  // Liczba punktów zdobywanych za headshota ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Revenge "1"                     // Liczba punktów zdobywanych za zemstę ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Assist "1"                      // Liczba punktów zdobywanych za asystę ( 0 - Jeżeli ma nie dostawać )
mRanks_Points_Dead "1"                              // Liczba punktów traconych za zgon ( 0 - Jeżeli ma nie tracić )
mRanks_Extra_Points_Knife "1"                       // Liczba punktów zdobywanych za zabójstwo z noża ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Grenade "2"                     // Liczba punktów zdobywanych za zabójstwo z granatu ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Plant "1"                       // Liczba punktów zdobywanych za podłożenie bomby ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Defuse "1"                      // Liczba punktów zdobywanych za rozbrojenie bomby ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Hostage_Rescued "1"             // Liczba punktów zdobywanych za uratowanie zakładnika ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Win "1"                         // Liczba punktów zdobywanych za wygraną rundę ( 0 - Jeżeli ma nie dostawać )

// » VIP
mRanks_Kill_Vip "2"                                 // Liczba punktów VIP zdobywanych za zabójstwo ( 0 - Jeżeli ma nie dostawać )
mRanks_Kill_Hs_Vip "4"                              // Liczba punktów VIP zdobywanych za headshota ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Revenge_Vip "2"                 // Liczba punktów VIP zdobywanych za zemstę ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Assist_Vip "2"                  // Liczba punktów VIP zdobywanych za asystę ( 0 - Jeżeli ma nie dostawać )
mRanks_Points_Dead_Vip "2"                          // Liczba punktów VIP traconych za zgon ( 0 - Jeżeli ma nie tracić )
mRanks_Extra_Points_Knife_Vip "2"                   // Liczba punktów VIP zdobywanych za zabójstwo z noża ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Grenade_Vip "2"                 // Liczba punktów VIP zdobywanych za zabójstwo z granatu ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Plant_Vip "2"                   // Liczba punktów VIP zdobywanych za podłożenie bomby ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Defuse_Vip "2"                  // Liczba punktów VIP zdobywanych za rozbrojenie bomby ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Hostage_Rescued_Vip "2"         // Liczba punktów VIP zdobywanych za uratowanie zakładnika ( 0 - Jeżeli ma nie dostawać )
mRanks_Extra_Points_Win_Vip "2"                     // Liczba punktów VIP zdobywanych za wygraną rundę ( 0 - Jeżeli ma nie dostawać )

//============================================================== » mRanks - Core « ==============================================================\\
```
</details>

### ScreenShots

<details>
  <summary><b>Server</b></summary>
  
- Menu Główne

   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/1.png?raw=true"></img>
  
 - Panel Gracza
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/2.png?raw=true"></img>
 
 - Spis Rang
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/8.png?raw=true"></img>
 
 - Wymagania
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/9.png?raw=true"></img>
 
 - Grupy
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/9.png?raw=true"></img>
 
 - Grupy: Zwykły Gracz
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/4.png?raw=true"></img>
   
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/5.png?raw=true"></img>
 
 - Grupy: VIP
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/6.png?raw=true"></img>
   
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/7.png?raw=true"></img>
 
 - Top8
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/16.png?raw=true"></img>
 
 - Menu HUD
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/10.png?raw=true"></img>

 - Kolor HUD
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/11.png?raw=true"></img>

 - Ustawienia HUD
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/12.png?raw=true"></img>

 - Opcje HUD
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/13.png?raw=true"></img>

 - Wygląd HUD
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/14.png?raw=true"></img>

 - Wygląd Sprite
 
   <img src="https://github.com/AmxxPro-pl/mRanks/blob/main/img/15.png?raw=true"></img>

</details>

</details>
