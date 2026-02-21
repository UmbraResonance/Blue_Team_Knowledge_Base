```bash
(
  # --- 1. Core Campaign Concepts ---
  intitle:/\b(campaign|operation)\b/i OR
  intitle:/"widespread attack"/i OR
  intitle:/"coordinated attack"/i OR
  intitle:/"large-scale attack"/i OR
  intitle:/"espionage campaign"/i OR
  intitle:/"ransomware campaign"/i OR
  intitle:/"phishing campaign"/i OR

  # --- 2. Known Critical Activities and Events ---
  intitle:/SolarWinds/i OR
  intitle:/Stuxnet/i OR
  intitle:/NotPetya/i OR
  intitle:/WannaCry/i OR
  intitle:/MOVEit/i OR
  intitle:/"Colonial Pipeline"/i OR
  intitle:/Log4j/i OR
  intitle:/Log4Shell/i OR
  intitle:/"Operation Triangulation"/i OR
  intitle:/"Operation SyncHole"/i OR # [1]
  intitle:/"Operation Rewrite"/i OR # [2]

  # --- 3. Large-scale Attack Vectors and Techniques ---
  intitle:/"supply chain attack"/i OR
  intitle:/"supply chain compromise"/i OR #
  intitle:/"watering hole"/i OR #
  intitle:/"exploit kit"/i OR
  intitle:/\bEK\b/i OR
  intitle:/malvertising/i OR
  intitle:/"mass exploitation"/i OR
  intitle:/"widespread exploitation"/i OR

  # --- 4. Impact ---
  intitle:/"data breach"/i OR
  intitle:/"widespread compromise"/i OR
  intitle:/"major incident"/i OR
  intitle:/"operational disruption"/i OR #

  # --- 5. Common Key Words ---
  intitle:/\b(cyberattack|breach|espionage)\b/i
)
```
