# Rule Summaries

## G.A.T.O.R
Gunnery + Attacker Modifiers + Target Modifiers + Other + Range

## Punch/Kick (Physical Attack)
Declared in Physical Phase, must be adjacent to target and in forward arc, arm/leg(s) did not fire any weapon this round:  

**Target Number:**  
`Piloting Skill + [attacker mod] [-2 Kick] + [defender mod/terrain] + [actuator modifiers]`  

**Damage:**  
Punch: `(Mech weight / 10) - actuator damage` then roll 1d6 on Punch Location Table
Kick: `(Mech weight / 5)` then 1d6 on Kick Location Table

*Kicked target rolls for PSR. A failed Kick attack, the attacker rolls for PSR*  
*Kicks with damaged actuators halves damage*  

### Combined Punch[Kick] Location Table

1d6 | Left Side | Front/Rear | Right Side
:-: | :-------: | :--------: | :--------:
 1 | LT [LL] | LA [RL] | RT [RL]
 2 | LT [LL] | LT [RL] | RT [RL]
 3 | CT [LL] | CT [RL] | CT [RL]
 4 | LA [LL] | RT [LL] | RA [RL]
 5 | LA [LL] | RA [LL] | RA [RL]
 6 | HD [LL] | HD [LL] | HD [RL]

## Charging (Physical Attack)

Declared in Movement Phase and target must be in valid arc, finished movement, and standing (not a target of a Charge, DFA, Push)

- Move to target's adjacent hex (count hexes moved)  
- Physical Phase:  

  **Target Number**:  
  `Piloting Skill + (Piloting Skill - Target Piloting Skill) + [attacker mod] + [defender mod]`

  **Damage**:  
  Target: `(Mech weight / 10) * [Hexes moved]`  (5pt grouping & Hit Location table)  
  Self: `1 pt * 10 tons (Mech weight)`  

- Move into target hex and displace target on opposite direction (if possible)
- Roll for falls (both target and attacker): `Piloting Skill + 2`


## Death from Above (Physical Attack)

Declared in Movement Phase, target must have finished movement, and target's hex is reachable via Jump MP. 

- Attacker cannot make weapon attacks but can be targetted
- Move to target's adjacent hex
- Physical Phase:  
  
  **Target Number**:  
  `Piloting Skill + 3 [Jump] + (Piloting Skill - Target Piloting Skill) + [defender mod/terrain]`
  
  **Damage**:  
  Target: `(Mech weight / 10) * 3` (5pt grouping & Punch Location Table)  
  Self: `(Mech weight / 5)` (5pt grouping & Kick Location Table [front])  

- Move into target hex and displace target on opposite direction (if possible)
- **Roll for falls** (both attacker and target):  
  Success: Attacker gets `[PSR + 4]` and target gets `[PSR + 2]`  
  Fail: 0-level fall damage `(Mech weight / 2)` then damage to Mechwarrior `PSR`


