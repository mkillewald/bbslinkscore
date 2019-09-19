### NOTE: This is an unstable development branch which has not yet been released, and is not guaranteed to work. Do not use this version, you have been warned. 

### For the stable release verision, return to branch [master](https://github.com/mkillewald/bbslinkscore/tree/master), or download the [latest release](https://github.com/mkillewald/bbslinkscore/releases/latest)

# C-Net BBSLink Score 1.0.1 (devel version)

A C-Net Pfile written in ARexx used to display the BBSLink Game Leaderboards on a C-Net Amiga BBS 
http://www.bbslink.net/scores.php

![BBSLink.net LORD Leaderboard](http://games.bbslink.net/score.php?door=lord&type=image)



**************************************************************************

### Changelog
                                                                   
v1.0.0 (14 Sep 2019) by k1ds3ns4t10n of -X-caliber BBS                                
                                                                    
This is public domain software. Use at your own risk.                                              
**************************************************************************

### Installation Instructions:

1.  Create a folder called 'BBSLink' in your PFiles: directory.
    Copy this file there.
    
2.  Download http_get from Aminet and install in C:
    https://aminet.net/package/comm/tcp/http_get
    
3.  Add a line to your SYSTEXT:sys.welcome file like this:
    
    Q#0 pfiles:bbslink/bbslinksolar "SCORE_CODE"}

    ^ NOTE: "Q" here is a ctrl-Q

    Replace SCORE_CODE with one of the following: 
```
    Score code: lord       Legend of the Red Dragon   
    Score code: lord2      Legend of the Red Dragon II: New World   
    Score code: mzkl       MZK LORD   
    Score code: ooii       Operation: Overkill II   
    Score code: usrpuscr   Usurper User Rankings   
    Score code: usrptscr   Usurper Team Rankings   
    Score code: usrppkil   Usurper Player Killers   
    Score code: usrpmkil   Usurper Monster Killers    
    Score code: usrpnews   Usurper News    
    Score code: bre        Barren Realms Elite   
    Score code: bretody    Barren Realms Elite Today's News   
    Score code: breyest    Barren Realms Elite Yesterday's News     
    Score code: falc       Falcon's Eye   
    Score code: falctody   Falcon's Eye Today's News   
    Score code: falcyest   Falcon's Eye Yesterday's News       
    Score code: fhontody   Falcon's Honor Today's News   
    Score code: fhonyest   Falcon's Honor Yesterday's News   
    Score code: arcl       The Arcadian Legends    
    Score code: arcltody   The Arcadian Legends Today's News   
    Score code: arclyest   The Arcadian Legends Yesterday's News   
    Score code: netr       Netrunner   
    Score code: assn       Assassin   
    Score code: bord       Bordello   
    Score code: junk       Junkyard   
    Score code: mega       Mega Slots   
    Score code: fish       Fresh Water Fishing Sim   
    Score code: lmon       Lemonade    
```
**************************************************************************
### -X-caliber BBS telnet://bbs.aholix.net:6800
