# Voorbeeld van input.txt  
NAME [3 spaces] MIN_NODES [3 spaces] MAX_NODES  
Antonio&nbsp;&nbsp;&nbsp;28&nbsp;&nbsp;&nbsp;560&nbsp;&nbsp;&nbsp;660  
Diverta&nbsp;&nbsp;&nbsp;16&nbsp;&nbsp;&nbsp;152&nbsp;&nbsp;&nbsp;190  
Anna Watcho&nbsp;&nbsp;&nbsp;30&nbsp;&nbsp;&nbsp;750&nbsp;&nbsp;&nbsp;750  
Limbo&nbsp;&nbsp;&nbsp;22&nbsp;&nbsp;&nbsp;336&nbsp;&nbsp;&nbsp;420  
HUMAN&nbsp;&nbsp;&nbsp;10&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0  
BigInteger&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;80&nbsp;&nbsp;&nbsp;80  
Doblo&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;29&nbsp;&nbsp;&nbsp;37  
  
# OUTPUTS  
ronde1.txt  
ronde1.html  
ronde1_status.txt  
rating_update.html  
  
# ELO to MaxNodes    
VOORBEELD LEVEL 9 & 1430 ELO  
Level 9 NODES --> 75  
Level 10 NODES --> 85  
Level 9 ELO --> 1400  
verschilNodes = 85 - 75 = 10  
75 + ((verschilNodes * (1430 - 1400)) / 75)  
75 + ((10 * (1430 - 1400)) / 75) = 79 MaxNodes    
