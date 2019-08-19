# passphrase-gen-js

The project inspired by `pwgen` Linux command-line utility.

Script generates lists of words from the supplied dictionary.

Pick at least three to create a memorable and strong passphrase.

Default dictionary is `corncob-lowercase.txt`.

## Sample output

```
Corncob dictionary:

vulcanologist      affixed            wellorganised      sipper             mechanist          
ventricle          hopefulness        immediate          ranis              doomsday           
remitting          frothing           solders            goodness           tilting            
affirming          sunburned          decremented        especially         spied              
hydrofluoric       abundant           shares             dourness           distiller          
precursor          debrief            viable             belying            dedicating         
outshone           greyhounds         purlins            bloodred           reafforestation    
yachtsman          fixer              worshipful         lateral            porous             
nymphomania        conduction         engined            lungful            tomahawk           
scuffed            imparted           rendezvoused       mealtimes          daunted            
servilely          waxed              missy              override           grilling           
bracelet           orchestrations     burgundy           yellings           demeans            
wreathing          conurbations       saipan             landing            drool              
debunks            headboards         scherzi            cancel             nazi               
caimans            discontinues       energising         lustful            saleable           
coursing           predictably        mitigate           assassin           regretful          
doorkeepers        envelopes          scherzi            abhorred           transpose          
rigging            leakage            conspicuousness    marxists           theorise           
biscuity           rotas              arrests            harrows            shiftless          
embroider          lone               sensitively        unscrambling       rifts              
```

```
Passphrase entropy:

1 words  15.8 bits
2 words  31.7 bits
3 words  47.5 bits
4 words  63.3 bits
5 words  79.1 bits
6 words  95.0 bits
7 words  110.8 bits
8 words  126.6 bits
```

```
Passwords from pwgen:

pwgen -sn 6    27.1 bits
pwgen -sn 8    36.6 bits
pwgen -sn 10   48.5 bits
pwgen -sn 12   58.8 bits
pwgen -sn 14   72.2 bits
pwgen -sn 15   75.2 bits
pwgen -sn 16   83.5 bits
pwgen -sn 18   95.2 bits
pwgen -sn 20   104.1 bits
pwgen -sn 25   130.0 bits
```
