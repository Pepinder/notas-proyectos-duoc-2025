# Instrucciones evaluación

La evaluación consiste en realizar un informe técnico en formato Jupyter Notebook que contenga las dos primeras fases de la metodología CRISP-DM aplicada a los datos de Starcraft_duoc. Para desarrollar la evaluación utilice los anexos “Evaluación Parcial 1 Anexo 1” y “EV1_Anexo 2_starcraft_duoc”

Etapas de CRISP-DM:

1. Entendimiento del negocio.
2. Entendimiento de los datos.

### Realice un informe técnico que contenga las dos primeras fases de la metodología CRISP-DM:

- Identifiquelos objetivos claves y KPIs relevantes para la compañía coherentes con la fase Business Understanding.
- Calcule estadísticos sobre los datos, identificando insight relevantes, con el fin deanalizar la relación entre patrones y datos, definidos en la fase DataUnderstanding.
- Señale las características y naturaleza claves dentro de los datos para definir los objetivos generales del análisis.
- Identifique la existencia de valores atípicos y valores perdidos, proponiendo rutinas de limpieza que se pueden abordar para generar mayor precisión en los modelos y menor sesgo en el análisis.
- Aplique matriz de correlación, identificando qué correlaciones tienen las características, reconociendo las correlaciones negativas y positivas, e interpretando qué valor generan en el proceso los valores obtenidos.
- Proponga pasos a seguir considerando fases posteriores de acuerdo con los resultados obtenidos en las fases abordadas.

En este contexto, se presentan los siguientes datos en el csv:

- GameID: Unique ID for each game
- LeagueIndex: 1-8 for Bronze, Silver, Gold, Platinum, Diamond, Master, GrandMaster, Professional leagues
- Age: Age of each player
- HoursPerWeek: Hours spent playing per week
- TotalHours: Total hours spent playing
- APM: Action per minute
- SelectByHotkeys: Number of unit selections made using hotkeys per timestamp
- AssignToHotkeys: Number of units assigned to hotkeys per timestamp
- MinimapAttacks: Number of attack actions on minimal per timestamp
- MinimapRightClicks: Number of right-clicks on minimal per timestamp
- NumberOfPACs: Number of PACs per timestamp
- GapBetweenPACs: Mean duration between PACs (milliseconds)
- ActionLatency: Mean latency from the onset of PACs to their first action (milliseconds)
- ActionsInPAC: Mean number of actions within each PAC
- TotalMapExplored: Number of 24x24 game coordinate grids viewed by player per timestamp
- WorkersMade: Number of SCVs, drones, probes trained per timestamp
- UniqueUnitsMade: Unique units made per timestamp
- ComplexUnitsMade: Number of ghosts, investors, and high templars trained per timestamp
- ComplexAbilityUsed: Abilities requiring specific targeting instructions used per timestamp
- MaxTimeStamp: Time stamp of game's last recorded event
