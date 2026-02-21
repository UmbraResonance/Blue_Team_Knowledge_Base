```bash
(
    # --- 1. High-Confidence Patterns ---
    intitle:/APT\d+/i OR 
    intitle:/UNC\d+/i OR 
    intitle:/UAT-\d+/i OR
    intitle:/FIN\d+/i OR 
    intitle:/G\d{4}/i OR

    # --- 2. Known Multi-Word Aliases ---
    intitle:/"Threat Actor"/i OR 
    intitle:/"Threat Group"/i OR 
    intitle:/"Nation-State"/i OR

    # --- 3. CrowdStrike Naming Rules (Animals) ---
    intitle:/\bBear\b/i OR 
    intitle:/\bBuffalo\b/i OR 
    intitle:/\bChollima\b/i OR 
    intitle:/\bCrane\b/i OR 
    intitle:/\bHawk\b/i OR 
    intitle:/\bJackal\b/i OR 
    intitle:/\bKitten\b/i OR 
    intitle:/\bLeopard\b/i OR 
    intitle:/\bLynx\b/i OR 
    intitle:/\bOcelot\b/i OR 
    intitle:/\bPanda\b/i OR 
    intitle:/\bSaiga\b/i OR 
    intitle:/\bSphinx\b/i OR 
    intitle:/\bSpider\b/i OR 
    intitle:/\bTiger\b/i OR 
    intitle:/\bWolf\b/i OR

    # --- 4. Microsoft Naming Rules (Weather) ---
    intitle:/\bBlizzard\b/i OR 
    intitle:/\bTyphoon\b/i OR 
    intitle:/\bSandstorm\b/i OR 
    intitle:/\bSleet\b/i OR 
    intitle:/\bDust\b/i OR 
    intitle:/\bCyclone\b/i OR 
    intitle:/\bRain\b/i OR 
    intitle:/\bHail\b/i OR 
    intitle:/\bTempest\b/i OR 
    intitle:/\bTsunami\b/i OR 
    intitle:/\bFlood\b/i OR 
    intitle:/\bStorm\b/i OR

    # --- 5. Palo Alto Unit 42 Naming Rules (Constellation) ---
    intitle:/\bLibra\b/i OR 
    intitle:/\bOrion\b/i OR 
    intitle:/\bScorpius\b/i OR 
    intitle:/\bVirgo\b/i OR 
    intitle:/\bDraco\b/i OR 
    intitle:/\bGemini\b/i OR 
    intitle:/\bPisces\b/i OR 
    intitle:/\bSerpens\b/i OR 
    intitle:/\bTaurus\b/i OR 
    intitle:/\bUrsa\b/i OR
	
	# --- 6. Trend Micro Naming Rules ---
	(intitle:/\b(Earth|Wind|Water|Fire)\b/i f:22) OR
	
    # --- 7. Other Key Words (Need frenquently update) ---
    intitle:/\bLazarus\b/i OR 
    intitle:/\bTurla\b/i OR 
    intitle:/\bWinnti\b/i OR 
    intitle:/\bBookworm\b/i OR 
    intitle:/\bIronHusky\b/i OR 
    intitle:/\bNightEagle\b/i
)
```
