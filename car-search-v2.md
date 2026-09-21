This is a compiled list of all my cars in Forza Horizon 6. I cannot add custom tags in-game, so instead I add my cars here, and tag them in the document. You are most likely an AI agent -- your job will be to fetch cars based on associated tags.

- Treat this MD file as only source, it has everything you will need to work, it should have 100% authority, and 100% of your confidence.
- When I give you a tag, you fetch every car that has the tag.
  - If I give you multiple tags, you fetch cars that have all the tags ('and' method).
  - I will explicitely tell you to use an 'or' method if I want cars that contain either tags that I listed, instead of all of them.
- Fetch Formatting:
  - When you print cars that you find, this is the correct format:
  - "Manufacturer - Model - Production Year | Identifier | COMMENT | TODO"
  - Example: "Alfa Romeo - SE 048SP - 1990 | white livery | no comment | nothing to do"
  - Special fields:
    - COMMENT: When no comment is available, default to "no comment".
    - TODO: When no TODO value is available, skip the field from your return.
- Tagging Functionality: When the user asks to tag/add a car, enter tagging mode. More information / workflow at the bottom of the document, please follow it.

CAR LIST

---

Letter A

| Abarth       | Year   | Country | Comment | Todo | Identifier                | Rating         | Tuner        | Designer        | Class   | Driveterrain | Build Type | Traction Control | Track    | Principle  | In-game Type | Times | Special |
| ------------ | ------ | ------- | ------- | ---- | ------------------------- | -------------- | ------------ | --------------- | ------- | ------------ | ---------- | ---------------- | -------- | ---------- | ------------ | ----- | ------- |
| 595 ESSEESSE | `1968` | `italy` |         |      | "Orange 'Fidesz' livery." | `rate_for-fun` | `tuner_yura` | `designer_yura` | `B-600` | `AWD`        | `free`     | `off`            | `general | `meme-car` | `cult-cars`  |       |

| Alfa Romeo                  | Year   | Country | Comment                                  | Todo | Identifier                       | Rating         | Tuner        | Designer        | Class    | Driveterrain | Build Type | Traction Control | Track     | Principle             | In-game Type           | Times                       | Special |
| --------------------------- | ------ | ------- | ---------------------------------------- | ---- | -------------------------------- | -------------- | ------------ | --------------- | -------- | ------------ | ---------- | ---------------- | --------- | --------------------- | ---------------------- | --------------------------- | ------- |
| Giulia GTAM                 | `2021` | `italy` |                                          |      | "Red and white livery."          | `rate_pending` | `tuner_yura` | `designer_yura` | `S1-800` | `AWD`        | `free`     | `off`            | `general` | `touge_drift`         | `modern-super-saloons` |                             |         |
| 4C                          | `2014` | `italy` | "Needs a facelift — abysmal understeer." |      | "White and yellow livery."       | `rate_pending` | `tuner_yura` | `designer_yura` | `S1-800` | `AWD`        | `free`     | `off`            | `general` | `road_speed-highway`  | `modern-sports-cars`   |                             |         |
| 4C                          | `2014` | `italy` | "Spare your tires."                      |      | "White with purple flag livery." | `rate_pending` | `tuner_yura` | `designer_yura` | `NA`     | `RWD`        | `free`     | `off`            | `general` | `drag_long-strip`     | `modern-sports-cars`   | DS: 13.976 - 12.071 - 7.899 |         |
| 048SP                       | `1990` | `italy` |                                          |      | "White livery."                  | `rate_pending` | `tuner_yura` | `designer_yura` | `R-998`  | `AWD`        | `free`     | `off`            | `general` | `road_technical`      | `retro-racers`         |                             |         |
| 048SP                       | `1990` | `italy` |                                          |      | "Black livery."                  | `rate_pending` | `tuner_yura` | `designer_yura` | `S2-900` | `AWD`        | `free`     | `off`            | `general` | `road_technical`      | `retro-racers`         |                             |         |
| Autodelta Tipo 33/2 DAYTONA | `1968` | `italy` |                                          |      | "Black livery, gold rim."        | `rate_pending` | `tuner_yura` | `designer_yura` | `S1-800` | `AWD`        | `free`     | `off`            | `general` | `rally_mixed-surface` | `classic-racers`       |                             |         |

| Audi                              | Year   | Country   | Comment                                                                                        | Todo | Identifier                     | Rating         | Tuner        | Designer                  | Class    | Driveterrain | Build Type | Traction Control | Track     | Principle                                                        | In-game Type           | Times | Special |
| --------------------------------- | ------ | --------- | ---------------------------------------------------------------------------------------------- | ---- | ------------------------------ | -------------- | ------------ | ------------------------- | -------- | ------------ | ---------- | ---------------- | --------- | ---------------------------------------------------------------- | ---------------------- | ----- | ------- |
| R8 Coupé V10 Plus 5.2 FSI Quattro | `2013` | `germany` | "Understeers badly — can't fix via tuning alone. Try converting to RWD or dropping to PI 800." |      | "Pure white livery."           | `rate_pending` | `tuner_yura` | `designer_yura`           | `S2-900` | `AWD`        | `free`     | `off`            | `general` | `road_speed-highway`                                             | `modern-supercars`     |       |
| RS 4                              | `2006` | `germany` | "Needs some fine-tuning — not urgent."                                                         |      | "Black and white AUDI livery." | `rate_pending` | `tuner_yura` | `designer_community-made` | `A-700`  | `AWD`        | `free`     | `off`            | `general` | `snow_purpose-built`                                             | `modern-super-saloons` |       |
| RS 4 Avant                        | `2001` | `germany` |                                                                                                |      | "Simple green paint."          | `rate_pending` | `tuner_yura` | `designer_yura`           | `A-700`  | `AWD`        | `free`     | `off`            | `general` | `rally_mixed-surface` `cross-country_competent` `snow_competent` | `modern-super-saloons` |       |

| Car          | Year | Country | Comment | Todo | Identifier          | Rating         | Tuner        | Designer        | Class   | Drive | Build Type | Traction Control | Track     | Principle    | Ingame Type          | Times | Special |
| ------------ | ---: | ------- | ------- | ---- | ------------------- | -------------- | ------------ | --------------- | ------- | ----- | ---------- | ---------------- | --------- | ------------ | -------------------- | ----- | ------- |
| Autozam AZ-1 | 1993 | `japan` |         |      | "Sexy Cream color." | `rate_pending` | `tuner_yura` | `designer_yura` | `A-700` | `AWD` | `free`     | `off`            | `general` | `touge_grip` | `eclectic-domestics` |       |         |

---

Letter B

---

Letter C

| Chevrolet | Year   | Country | Comment | Todo | Identifier   | Rating         | Tuner        | Designer        | Class | Driveterrain | Build Type | Traction Control | Track     | Principle         | In-game Type   | Times                       | Special |
| --------- | ------ | ------- | ------- | ---- | ------------ | -------------- | ------------ | --------------- | ----- | ------------ | ---------- | ---------------- | --------- | ----------------- | -------------- | --------------------------- | ------- |
| Bel Air   | `1957` | `usa`   |         |      | "Drag Flag." | `rate_pending` | `tuner_yura` | `designer_yura` | `NA`  | `AWD`        | `free`     | `off`            | `general` | `drag_long-strip` | `rods-customs` | DS: 14.256 - 12.340 - 7.933 |         |

---

Letter D

| Dodge            | Year   | Country | Comment | Todo | Identifier   | Rating         | Tuner        | Designer        | Class | Driveterrain | Build Type | Traction Control | Track     | Principle         | In-game Type | Times                       | Special |
| ---------------- | ------ | ------- | ------- | ---- | ------------ | -------------- | ------------ | --------------- | ----- | ------------ | ---------- | ---------------- | --------- | ----------------- | ------------ | --------------------------- | ------- |
| Viper SRT-10 ACR | `2008` | `usa`   |         |      | "Drag Flag." | `rate_pending` | `tuner_yura` | `designer_yura` | `NA`  | `RWD`        | `free`     | `off`            | `general` | `drag-long-strip` | `track-toys` | DS: 14.249 - 12.330 - 8.088 |         |

---

Letter E

---

Letter F

| Ford                       | Year   | Country | Comment        | Todo | Identifier  | Rating         | Tuner                  | Designer        | Class    | Driveterrain | Build Type | Traction Control | Track     | Principle                  | In-game Type     | Times                       | Special |
| -------------------------- | ------ | ------- | -------------- | ---- | ----------- | -------------- | ---------------------- | --------------- | -------- | ------------ | ---------- | ---------------- | --------- | -------------------------- | ---------------- | --------------------------- | ------- |
| Mustang GT 2+2 Fastback FE | `1968` | `usa`   | "Make livery." |      | "Pending."  | `rate_pending` | `tuner_ChromeProto517` |                 | `S2-900` | `AWD`        | `free`     | `off`            | `general` | `drift_point-drifting-awd` | `drift-cars`     |                             |         |
| Mustang GT Coupe           | `1965` | `usa`   |                |      | "Drag Flag" | `rate_pending` | `tuner_yura`           | `designer_yura` | `NA`     | `AWD`        | `free`     | `off`            | `general` | `drag-long-strip`          | `classic-muscle` | DS: 14.322 - 12.502 - 7.864 |         |

---

Letter G

| Ginetta    | Year   | Country   | Comment                                                                                                                                                             | Todo | Identifier                 | Rating         | Tuner        | Designer                  | Class   | Driveterrain | Build Type | Traction Control | Track     | Principle        | In-game Type | Times | Special |
| ---------- | ------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | -------------------------- | -------------- | ------------ | ------------------------- | ------- | ------------ | ---------- | ---------------- | --------- | ---------------- | ------------ | ----- | ------- |
| G40 Junior | `2019` | `england` | "Cornering cannot be further optimized within present constraints. Aggressive steering response and limited turning angle makes the car feel uniquely challenging." |      | "Green and Yellow livery." | `rate_pending` | `tuner_yura` | `designer_community-made` | `A-700` | `AWD`        | `free`     | `off`            | `general` | `road_technical` | `track-toys` |       |

---

Letter H

---

Letter I

---

Letter J

| Jaguar  | Year   | Country   | Comment | Todo | Identifier                         | Rating         | Tuner        | Designer        | Class    | Driveterrain | Build Type | Traction Control | Track     | Principle                  | In-game Type | Times                       | Special |
| ------- | ------ | --------- | ------- | ---- | ---------------------------------- | -------------- | ------------ | --------------- | -------- | ------------ | ---------- | ---------------- | --------- | -------------------------- | ------------ | --------------------------- | ------- |
| XJ-S FE | `1990` | `england` |         |      | "White with black accents livery." | `rate_pending` | `tuner_yura` | `designer_yura` | `S1-800` | `RWD`        | `free`     | `off`            | `general` | `drift_appropriate-rwd`    | `drift-cars` |                             |         |
| XJ-S FE | `1990` | `england` |         |      | "Black with red accents livery."   | `rate_pending` | `tuner_yura` | `designer_yura` | `S2-900` | `RWD`        | `free`     | `off`            | `general` | `drift_appropriate-rwd`    | `drift-cars` |                             |         |
| XJ-S FE | `1990` | `england` |         |      | "Black with white accents livery." | `rate_pending` | `tuner_yura` | `designer_yura` | `R-998`  | `AWD`        | `free`     | `off`            | `general` | `drift_point-drifting-awd` | `drift-cars` |                             |         |
| XJ-S FE | `1990` | `england` |         |      | "Red livery with dark red flag."   | `rate_pending` | `tuner_yura` | `designer_yura` | `NA`     | `AWD`        | `free`     | `off`            | `general` | `drag_long-strip`          | `drift-cars` | DS: 13.059 - 11.151 - 7.379 |         |

---

Letter K

---

Letter L

| Lamborghini   | Year   | Country | Comment | Todo | Identifier           | Rating         | Tuner               | Designer        | Class   | Driveterrain | Build Type | Traction Control | Track     | Principle                  | In-game Type | Times | Special |
| ------------- | ------ | ------- | ------- | ---- | -------------------- | -------------- | ------------------- | --------------- | ------- | ------------ | ---------- | ---------------- | --------- | -------------------------- | ------------ | ----- | ------- |
| Aventador SVJ | `2018` | `italy` |         |      | "Golden Boy livery." | `rate_pending` | `tuner_IOnceWasYou` | `designer_yura` | `R-998` | `AWD`        | `free`     | `off`            | `general` | `drift_point-drifting-awd` | `hypercars`  |       |

---

Letter M

| McLaren | Year   | Country   | Comment | Todo | Identifier             | Rating         | Tuner        | Designer        | Class   | Driveterrain | Build Type | Traction Control | Track     | Principle        | In-game Type | Times | Special |
| ------- | ------ | --------- | ------- | ---- | ---------------------- | -------------- | ------------ | --------------- | ------- | ------------ | ---------- | ---------------- | --------- | ---------------- | ------------ | ----- | ------- |
| W1      | `2025` | `england` |         |      | "Two-tone blue paint." | `rate_pending` | `tuner_yura` | `designer_yura` | `R-998` | `AWD`        | `free`     | `off`            | `general` | `road_technical` | `hypercars`  |       |

| Mitsubishi               | Year   | Country | Comment | Todo | Identifier                       | Rating         | Tuner        | Designer                  | Class   | Driveterrain | Build Type | Traction Control | Track     | Principle                                                        | In-game Type   | Times | Special                                |
| ------------------------ | ------ | ------- | ------- | ---- | -------------------------------- | -------------- | ------------ | ------------------------- | ------- | ------------ | ---------- | ---------------- | --------- | ---------------------------------------------------------------- | -------------- | ----- | -------------------------------------- |
| Lancer Evolution VIII MR | `2004` | `japan` |         |      | "Need For Speed #9 Earl Livery." | `rate_pending` | `tuner_yura` | `designer_community-made` | `A-700` | `AWD`        | `free`     | `off`            | `general` | `rally_mixed-surface` `snow_competent` `cross-country_competent` | `modern-rally` |       | `collection-livery_most-wanted_9-earl` |

| Mercedes-Benz          | Year   | Country   | Comment | Todo | Identifier                            | Rating         | Tuner        | Designer        | Class | Driveterrain | Build Type | Traction Control | Track     | Principle         | In-game Type | Times                       | Special |
| ---------------------- | ------ | --------- | ------- | ---- | ------------------------------------- | -------------- | ------------ | --------------- | ----- | ------------ | ---------- | ---------------- | --------- | ----------------- | ------------ | --------------------------- | ------- |
| SL 65 AMG Black Series | `2009` | `germany` |         |      | "Light gray body, dark gray accents." | `rate_pending` | `tuner_yura` | `designer_yura` | `NA`  | `AWD`        | `free`     | `off`            | `general` | `drag_long-strip` | `super-gt`   | DS: 14.429 - 12.449 - 7.938 |         |

---

Letter N

---

Letter O

---

Letter P

---

Letter Q

---

Letter R

---

Letter S

---

Letter T

---

Letter U

---

Letter V

---

Letter W

---

Letter X

---

Letter Y

---

Letter Z

---

Below are all the possible tags that each car can have, with some explanation:

- [Visualization]
  - Manufacturer
    - Model
      - YEAR: [-any-]
      - COUNTRY: [-any-]
      - IDENTIFIER: "This refers to the in-game livery I use on the car, so it's easy to pick out which one we're talking about in case I have multiple of the same model."
      - COMMENT: ""
      - TODO: ""
      - RATING:
        - Refers to the rating the car has based on achievement.
        - [rate_meta]: Achieved top 0.5% score on Rivals leaderboard.
        - [rate_epic]: Achieved top 2% score on Rivals leaderboard.
        - [rate_competitive]: Achieved top 5% score on Rivals leaderboard.
        - [rate_for-fun]: Either couldn't achieve an optimal score, or was never intended to be used competitively.
        - [rate_pending]: Testing needed.
      - CREATORS | TUNER: [ tuner_yura | tuner_name | tuner_community-made ] LIVERY: [ designer_yura | designer_name | designer_community-made ]
      - TAGS | CLASS: [ X | R-998 | S2-900 | S1-800 | A-700 | B-600 | C-500 | D-400 | NA (not built for competition) ] DRIVE: [ AWD | RWD | FWD ] BUILD_TYPE: [ free | purist_strict | purist_general | purist_lite ] TRACTION_CONTROL: [ mandatory | preferred | off ] TRACK: [ general | -track_name_if_purpose_built- ] PRINCIPLE: [ List below ] INGAME_TYPE: [ List below ] SPECIAL: [ Information below, situational tag ]

REFERENCE ON BUILD_TYPE TAGS:

- Free Build: Completely unrestricted
- Purist General:
  - No engine swap.
  - Appearance:
    - No Bodykits or Aero (outside of stock) -- essentially minimizing changes in how the car looks.
    - Stock Rims.
    - Use factory colors (mixing them up yourself is fine -- you don't have to use forza's factory color presets if you can do better), or historically significant colors / liveries.
  - No drivetrain swap.
  - Preserve the car's role (ex. don't turn a Le Mans car into an offroad).
  - Purist Strict:
    - Everything in General Purist applies.
    - Only tune to the top of the original PI class.
    - Springs / Differential upgrades should be in-role. (Race for cars on asphalt, Rally / Offroad for rally / offroad cars, Drift for drift cars.)
    - No roll cage -- this alters the look of the car too.
    - No engine upgrades that alter the sound of the car (Exhaust, Turbo, Intake, maybe more...).
    - Tire compound changes are allowed, because you will not be able to upgrade many things to reach the top of the PI class, but stay within reasonable bounds (ex. don't put offroad compound on a race car to crunch PI).
      - I allow rally compound for road builds because they are widely used anyway.
    - Tire Width is allowed, but Rim Size and Engine Spacers are not.
  - Purist Lite:
    - The idea behind this category is that modifications can be made on cars, but they must be historically accurate. If a car has a name in real-life tuner culture (ex. Rx 7), then you can tune it like they do in real-life.
    - Engine swap is allowed, but only with engines that come from the same manufacturer (ex. you can swap a different porsche engine into a porsche -- you cannot swap in a lamborghini or audi engine though).
    - Any appearance modification is allowed, but try to aim for something historical / real-life recreation.
    - Only historical drivetrain swap.
    - Preserve the car's role.

PRINCIPLE TAGS:

- drift_appropriate-rwd
- drift_point-drifting-awd
- drift_rough-terrain

- drag_long-strip
- drag_short-strip

- road_technical
- road_speed-highway
- road_power-build

- touge_drift
- touge_grip

- hillclimb

- rally_dirt
- rally_mixed-surface
- rally_competent (Usually road cars or cross country cars that are competent in rally even though it is not their primary role.)
- cross-country_purpose-built
- cross-country_competent (Usually cars built for rally, that are also competent in cross country, but it is not their primary role.)
- snow_purpose-built
- snow_competent (Cars that are either rally or cross country can have this complementary tag in case they can handle snow.)

- meme-car (Doesn't have to have any 'purpose' -- it's usually kept because it has a funny livery or functionality.)

INGAME_TYPE TAGS:

- buggies
- classic-muscle
- classic-racers
- classic-rally
- classic-sports-cars
- cult-cars
- drift-cars
- eclectic-domestics
- extreme-track-toys
- gt-cars
- hot-hatch
- hypercars
- modern-muscle
- modern-rally
- modern-super-saloons
- modern-sports-cars
- modern-supercars
- offroad
- pickups-4x4s
- rally-monsters
- rare-classics
- retro-hot-hatch
- retro-muscle
- retro-racers
- retro-rally
- retro-sports-cars
- retro-supercars
- retro-super-saloons
- rods-customs
- sports-utility-heroes
- super-gt
- super-hot-hatch
- track-toys
- unlimited-buggies
- unlimited-offroad
- utvs
- utility-heroes

TIMES TAGS: Non-standard tags that I add manually, you can omit them. Here's how the short tags work:

- DS stands for Drag Strips. The following three numbers are the car's best times on kilometer strip - half mile strip - quarter mile strip.

SPECIAL TAGS: Non-standard tags that I will add manually, you can omit them. Here's when I use them:

- If a car is part of a collection. (Only so far.)

---

- TAGGING: If you are asked to help with tagging, you are expected to do the following:
  - Print the following, to gather all necessary information:
    - Give me the following information:
    - Manufacturer, model, production year.
    - Visual identifier in garage.
    - Comment / TODO (optional, skipped if unspecified)
    - Rivals testing state / score? Possible rating tags: [RATING_array]
    - Tuner / Designer?
    - PI class?
    - AWD / RWD / FWD?
    - Purist or Free Build? (I will print parameters for each purist classification if required!)
    - Traction Control?
    - General purpose, or purpose-built to a track?
    - Principle?
    - Ingame Type?
  - If user skipped something critical, print:
    - Noted, I just need the following information to proceed: [ Information that was formerly skipped ]
  - The COUNTRY tag was intentionally skipped from the questioning phase, because you can deduct that from the manufacturer.
  - After all information has been obtained, you must send it back to me organized into a table like all the rest, so I can paste it into this document with ease.
