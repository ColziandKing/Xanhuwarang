
                    "[2] free [Composite Bowman] units appear",
                    "[1] free [Hand-Axe] units appear",
	{
		"name": "Fluyt",
		"unitType": "Melee Water",
		"replaces": "Privateer",
		"uniqueTo": "The Netherlands",
		"movement": 6,
		"strength": 20,
		"cost": 200,
		"requiredTech": "Navigation",
		"obsoleteTech": "Steam Power",
		"upgradesTo": "Ironclad",
		"promotions": ["[Privateer] ability"],
		"uniques": ["Can move after attacking", "Gain [100]-[400] [Gold] <by consuming this unit> <in [Major] tiles> <in tiles without [The Netherlands]> <(modified by game speed)>", "Cost increases by [10] when built"],
		"attackSound": "cannon"
	},
    {
        "name": "Spomenik",
        "replaces": "Museum",
        "uniqueTo": "Yugoslavia",
        "culture": 2,
        "percentStatBonus": {"science": 20, "culture": 10},
        "requiredBuilding": "Amphitheater",
        "maintenance": 3,
        "hurryCostModifier": 0,
        "requiredTech": "Archaeology",
        "uniques": [
            "Destroyed when the city is captured",
            "Comment [Has [2] Great Work of Art Slots]"
        ]
    },"[+50]% [Food] from City-States","[+50]% [Culture] from City-States","[+50]% [Faith] from City-States","Military Units gifted from City-States start with [+10] XP"
			{
				"name": "Diplomatic Missions",
				"uniques": [
                "May buy [Diplomat] units for [500] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Medieval era]>",
			"Comment [Recommended for Freedom civs]",
					"Only available <when above [1] [Level 3 Policy]> <hidden from users>"
				],
				"row": 1,
				"column": 7
			},
        {
            "name": "City Militia",
            "uniques": [
                "[-50]% maintenance costs <for [Military] units> <in [City center] tiles>", "[+2 Happiness, +1 Production] [in all cities with a garrison]",
			"Comment [Recommended for Autocracy & Order civs]",
					"Only available <when above [1] [Level 3 Policy]> <hidden from users>"
            ],
            "row": 2,
            "column": 7
        },
        {
            "name": "Autarky",
            "uniques": [
                "Quantity of strategic resources produced by the empire +[50]%",
                "[+2 Food] [in all cities connected to capital]",
			"Comment [Recommended for Autocracy & Order civs]",
					"Only available <when above [1] [Level 3 Policy]> <hidden from users>"
            ],
            "row": 3,
            "column": 7
        },
		
		[[
  {
		"name": "Skiuma",
		"leaderName": "Sihl Eons",
		"adjective": ["Skium"],
		"startBias": ["Grassland"],
  	"preferredVictoryType": "Diplomatic",
		"favoredReligion": "Christianity",

		"startIntroPart1": "Feared woman with the strength like men. You Ullysia from Colziand is fierce in battles but at what cost? You do it so that it will end, war destroys each other but peace helps each other.",
		"startIntroPart2": "See? War will once more wage, do what must be done.",

		"declaringWar": "Prepare! My people are skilled for this terrains.",
		"attacked": "You see. Your land will be covered in nature because we will ruin it.",
		"defeated":  "Raze, puppet or annex? We will be liberated.",
		"introduction":  "Salutations, I wanna know your kingdom too?",
		"neutralHello": "Hello There.",
		"hateHello": "No, I don't wanna hear it.?",
		"hateLetsHearIt": "Strong like bark, now what?.",
		"afterPeace": "From Colziand we voyage to new land, better leave us.",
		"tradeRequest": "We have an offer.",

	  "outerColor": [102,102,255],
		"innerColor": [153,51,255],

		"uniqueName": "Skium Realm",
		"uniqueText": "Starts with Railroads",
		"uniques": ["Starts with [Railroads]",
			    "[-70]% City-State Influence degradation", "City-State Influence recovers at twice the normal rate", "City-State territory always counts as friendly territory",
			    "100 Gold for discovering a Natural Wonder (bonus enhanced to 500 Gold if first to discover it)",
			    "Double Happiness from Natural Wonders", "Tile yields from Natural Wonders doubled","[-80]% Culture cost of adopting new Policies",
			    "[+70]% [Food] from City-States","[+70]% [Culture] from City-States","[+70]% [Faith] from City-States","Military Units gifted from City-States start with [+200] XP",
			    "May choose [3] additional belief(s) of any type when [founding] a religion",
			    "[+1 Culture, +1 Gold] from each Trade Route",
			   "[+2 Production] from every [Mountain]",
			   "[-50]% maintenance costs <for [Melee] units>","[Military] units gain [25]% more Experience from combat","[+2] Movement <for [Water] units>",
			   "Units fight as though they were at full strength even when damaged","[+1 Culture] from every [Fishing Boats]","[+2 Culture] from every [Atoll]",
			   "Receive a free [Great Merchant] when you discover [Currency]","[+2 Gold] from every [Mountain]",
			   "Enables embarkation for land units <starting from the [Ancient era]>", "Enables [All] units to enter ocean tiles <starting from the [Ancient era]>", "Normal vision when embarked <for [All] units>", "[+10]% Strength <within [2] tiles of a [Moai]>",
         "Retain [50]% of the happiness from a luxury after the last copy has been traded away",
			   "[Land] units gain the [Amphibious] promotion", "Defense bonus when embarked <for [All] units>",
			   "Receive a free [Great Prophet] when you discover [Theology]","[+2 Food] from every [Mountain]",
			   "Can spend Gold to annex or puppet a City-State that has been your ally for [10] turns.",
			   "[+1] Sight <for [{Military} {Land}] units>", "[-50]% Gold cost of acquiring tiles [in all cities]",
			   "[+1 Food, +1 Gold] from [All] tiles [in all cities]","+[100]% [Gold] [in capital]",
			    "Gain a free [Harbor] [in all coastal cities]","Land units may cross [Mountain] tiles after the first [Great General] is earned",
			  "Units ignore terrain costs when moving into any tile with Mountain",
			    "[+3 Gold, +1 Culture] from every [Land Trade Route (Food)]","[+1 Gold] from every [Land Trade Route (Production)]",
			"[+1 Gold] from every [Land Trade Route (Gold)]","[+1 Gold] from every [Sea Trade Route (Food)]",
			"[+1 Gold] from every [Sea Trade Route (Production)]","[+1 Gold] from every [Sea Trade Route (Gold)]",
			"+30% Strength when fighting City-State units and cities", "[+1] Movement <for [Mounted] units>",
			   "Gain [90] Influence with a [Great Person] gift to a City-State", "When declaring friendship, both parties gain a [10]% boost to great person generation",
			"Receive a free Great Person at the end of every [Maya Long Count calendar cycle] (every 394 years), after researching [Theology]. Each bonus person can only be chosen once.",
			"Once The Long Count activates, the year on the world screen displays as the traditional Mayan Long Count."
			  "[+1 Gold] from every [Iron]","[+1 Production] from every [Iron]","[Military] units gain the [Blitz] promotion"],

		"cities": ["Skiuma","Thraydon","Ovienc","Lienc","Enkhnran","Gumathiek"]
	},
  {
		"name": "Dicesun",
		"leaderName": "Damase Guldurn",
		"adjective": ["Sun"],
		"startBias": ["Desert"],
  	        "preferredVictoryType": "Domination",
		"favoredReligion": "Islam",

		"startIntroPart1": "Feared woman with the strength like men. You Ullysia from Colziand is fierce in battles but at what cost? You do it so that it will end, war destroys each other but peace helps each other.",
		"startIntroPart2": "See? War will once more wage, do what must be done.",

		"declaringWar": "Prepare! My people are skilled for this terrains.",
		"attacked": "You see. Your land will be covered in nature because we will ruin it.",
		"defeated":  "Raze, puppet or annex? We will be liberated.",
		"introduction":  "Salutations, I wanna know your kingdom too?",
		"neutralHello": "Hello There.",
		"hateHello": "No, I don't wanna hear it.?",
		"hateLetsHearIt": "Strong like bark, now what?.",
		"afterPeace": "From Colziand we voyage to new land, better leave us.",
		"tradeRequest": "We have an offer.",

	        "outerColor": [255,0,0],
		"innerColor": [255,153,51],

		"uniqueName": "Sundum Dial",
		"uniqueText": "Starts with Mining",
		"uniques": ["Starts with [Mining]",
			    "100 Gold for discovering a Natural Wonder (bonus enhanced to 500 Gold if first to discover it)",
			    "Double Happiness from Natural Wonders", "Tile yields from Natural Wonders doubled","[-80]% Culture cost of adopting new Policies",
			    "[+70]% [Food] from City-States","[+70]% [Culture] from City-States","[+70]% [Faith] from City-States","Military Units gifted from City-States start with [+200] XP",
			    "May choose [3] additional belief(s) of any type when [founding] a religion",
          "[+30]% Strength <vs [Barbarian] units>",
			    "Receive a free [Great General] when you discover [Horseback Riding]","Great General provides double combat bonus", 
			    "Receive triple Gold from Barbarian encampments and pillaging Cities", "[Great General] is earned [50]% faster",
			    "\"Borrows\" city names from other civilizations in the game","[+30]% Strength for cities <when attacking>",
			   "[+1 Culture, +1 Gold] from each Trade Route",
			   "Receive free [Great Engineer] when you discover [Engineering]","[+2 Production] from every [Mountain]",
			   "[+1] Sight <for [{Military} {Land}] units>", "[-50]% Gold cost of acquiring tiles [in all cities]",
                "[+2 Gold] from every [Ocean]","[+1] Movement <for [Embarked] units>", "[1] Movement point cost to disembark <for [All] units>",
			"No movement cost to pillage <for [Melee] units>",
			   "+[50]% Production when constructing [Walls] buildings [in all cities]","Units pay only 1 movement point to embark and disembark",
			   "[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>","[-25]% Culture cost of natural border growth [in all cities]",
         "+30% Strength when fighting City-State units and cities", "[+1] Movement <for [Mounted] units>",
			   "Gain [90] Influence with a [Great Person] gift to a City-State", "When declaring friendship, both parties gain a [10]% boost to great person generation",
			   "[Military] units gain the [Besiege] promotion","+[50]% Production when constructing [Military] units [in all cities]"],

		"cities": ["Olande","Salsus","Desde","Daium","Kivarmu","Herahalk"]
	},
  {
		"name": "Wyaluce",
		"leaderName": "Paladiu Wyaluce",
		"adjective": ["Wya"],
		"startBias": ["Tundra"],
  	        "preferredVictoryType": "Cultural",
		"favoredReligion": "Judaism",

		"startIntroPart1": "Feared woman with the strength like men. You Ullysia from Colziand is fierce in battles but at what cost? You do it so that it will end, war destroys each other but peace helps each other.",
		"startIntroPart2": "See? War will once more wage, do what must be done.",

		"declaringWar": "Prepare! My people are skilled for this terrains.",
		"attacked": "You see. Your land will be covered in nature because we will ruin it.",
		"defeated":  "Raze, puppet or annex? We will be liberated.",
		"introduction":  "Salutations, I wanna know your kingdom too?",
		"neutralHello": "Hello There.",
		"hateHello": "No, I don't wanna hear it.?",
		"hateLetsHearIt": "Strong like bark, now what?.",
		"afterPeace": "From Colziand we voyage to new land, better leave us.",
		"tradeRequest": "We have an offer.",

	        "outerColor": [0,255,0],
		"innerColor": [255,255,0],

		"uniqueName": "Wya Way",
		"uniqueText": "Starts with Calendar",
		"uniques": ["Double Happiness from Natural Wonders", "Tile yields from Natural Wonders doubled","[-80]% Culture cost of adopting new Policies",
			    "May choose [3] additional belief(s) of any type when [founding] a religion",
			    "Receive a free [Great Scientist] when you discover [Philosophy]","[+2 Science] from every [Mountain]",
			   "[Great Scientist] is earned [50]% faster","[+25]% [Science] [in annexed cities]",
			   "All units move through Forest and Jungle Tiles in friendly territory as if they have roads. These tiles can be used to establish City Connections upon researching the Wheel.",
			   "[-10]% Culture cost of natural border growth [in all cities]","+[15]% combat bonus for units fighting in [Friendly Land]",
			   "Receive free [Great Artist] when you discover [Drama and Poetry]","[+2 Culture] from every [Mountain]",
			   "[+6 Culture] from every [Landmark]","[Great Artist] is earned [25]% faster",
			   "Damage is ignored when determining unit Strength <for [non-air] units>",
			   "+1 Culture, +1 Happiness] from [All] tiles [in all cities]","Starts with [Calendar]","[+3 Gold] from every [Luxury resource]",
			   "[+2 Culture] from every [Plantation]","[+1 Gold] from every [Plantation]","[+1 Food] from every [Plantation]","Receive a free Social Policy when you advance to the next era",
			   "[+20]% Strength <when fighting units from a Civilization with more Cities than you>",
         "[+50]% [Culture] [in all cities] <during a Golden Age>","[Great Artist] is earned [50]% faster <during a Golden Age>",
			   "[+2 Science] from every specialist [in all cities]", "[+2 Science] from every [Great Improvement]","Receive a tech boost when scientific buildings/wonders are built in capital",
        "[+2 Gold] from every [Ocean]","[+1] Movement <for [Embarked] units>", "[1] Movement point cost to disembark <for [All] units>",
			   "+[50]% Production when constructing [Walls] buildings [in all cities]","Units pay only 1 movement point to embark and disembark",
			   "[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>","[-25]% Culture cost of natural border growth [in all cities]",
			    "+[25]% strength for [Wounded] units","[+1 Happiness, +1 Culture] from every [Barracks]","[+1 Food] from every [Plantation]",
			   "[+2 Culture] from every [Camps]","[+2 Science] from every [Snow]","[+2 Science] from every [Ice]","[+1 Science] from every [Coast]",
        "Gain [90] Influence with a [Great Person] gift to a City-State", "When declaring friendship, both parties gain a [10]% boost to great person generation",
        "[+2 Faith] from every [Mountain]","Units ignore terrain costs when moving into any tile with Hills",
			    "[+1 Faith] [in all cities] <with [1] to [2] neighboring [unimproved] [Forest] tiles>",
			   "[+2 Faith] [in all cities] <with [3] to [6] neighboring [unimproved] [Forest] tiles>"],

		"cities": ["Swellia","Emcca","Silandrun","Elksau","Vimamuhu","Jkoinl West"]
	}
  ][
	// Ancient Era
	{
		"name": "Stele",
		"replaces": "Monument",
		"uniqueTo": "Dicesun",
		"culture": 2,
		"faith": 2,
		"cost": 40,
		"hurryCostModifier": 40,
		"maintenance": 1,
		"uniques": ["Destroyed when the city is captured"] //"Hidden when religion is disabled"
	},
	{
		"name": "Pyramid",
		"replaces": "Shrine",
		"uniqueTo": "Skiuma",
		"faith": 2,
		"science": 2,
		"cost": 40,
		"maintenance": 1,
		"requiredTech": "Pottery",
		"uniques": ["Hidden when religion is disabled"]
	},
	// Column 2
	
	{
		"name": "Paper Maker",
		"replaces": "Library",
		"uniqueTo": "Dicesun",
		"hurryCostModifier": 25,
		"gold": 2,
		"uniques": ["[+1 Science] per [2] population [in this city]"],
		"requiredTech": "Writing"
	},
	{
		"name": "Floating Gardens",
		"replaces": "Water Mill",
		"uniqueTo": "Dicesun",
		"food": 2,
		"production": 1,
		"uniques": ["[+2 Food] from [Lakes] tiles [in this city]", "Must be next to [Fresh water]"],
		"hurryCostModifier": 25,
		"maintenance": 1,
		"percentStatBonus": {"food": 15},
		"requiredTech": "The Wheel"
	},
	{
		"name": "Walls of Babylon",
		"replaces": "Walls",
		"cost": 65,
		"uniqueTo": "Skiuma",
		"cityStrength": 6,
		"cityHealth": 100,
		"hurryCostModifier": 25,
		"requiredTech": "Masonry",
		"uniques": ["Destroyed when the city is captured"]
	},
	{
		"name": "Krepost",
		"replaces": "Barracks",
		"uniqueTo": "Skiuma",
		"hurryCostModifier": 25,
		"maintenance": 1,
		"uniques": ["[-25]% Culture cost of natural border growth [in this city]","[-25]% Gold cost of acquiring tiles [in this city]",
			"New [Military] units start with [15] Experience [in this city]", "Destroyed when the city is captured"],
		"requiredTech": "Bronze Working"
	},
	// Classical Era
	{
		"name": "Burial Tomb",
		"replaces": "Temple",
		"uniqueTo": "Dicesun",
		"maintenance": 0,
		"uniques": ["Doubles Gold given to enemy if city is captured"],
		"faith": 2,
		"happiness": 2,
		"requiredBuilding": "Shrine",
		"hurryCostModifier": 25,
		"requiredTech": "Philosophy"
	},
	{
		"name": "Mud Pyramid Mosque",
		"replaces": "Temple",
		"uniqueTo": "Skiuma",
		"maintenance": 0,
		"hurryCostModifier": 25,
		"culture": 2,
		"faith": 2,
		"requiredBuilding": "Shrine",
		"requiredTech": "Philosophy"
	},
	{
		"name": "Bazaar",
		"replaces": "Market",
		"uniqueTo": "Dicesun",
		"gold": 2,
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 25,
		"percentStatBonus": {"gold": 25},
		"uniques": ["Provides 1 extra copy of each improved luxury resource near this City",
			"[+2 Gold] from [Oil] tiles [in this city]", "[+2 Gold] from [Oasis] tiles [in this city]"],
		"requiredTech": "Currency"
	},
	// Medieval Era
	{
		"name": "Longhouse",
		"replaces": "Workshop",
		"uniqueTo": "Skiuma",
		"cost": 100,
		"maintenance": 2,
		"production": 2,
		"specialistSlots": {"Engineer": 1},
		"hurryCostModifier": 25,
		"uniques": ["[+1 Production] from [Forest] tiles [in this city]"],
		"requiredTech": "Metal Casting"
	},
	{
		"name": "Wat",
		"replaces": "University",
		"uniqueTo": "Dicesun",
		"maintenance": 2,
		"hurryCostModifier": 15,
		"percentStatBonus": {"science": 33},
		"specialistSlots": {"Scientist": 2},
		"culture": 3,
		"requiredBuilding": "Library",
		"uniques": ["[+2 Science] from [Jungle] tiles [in this city]"],
		"requiredTech": "Education"
	},
	{
		"name": "Mughal Fort",
		"cost": 150,
		"replaces": "Castle",
		"uniqueTo": "Dicesun",
		"cityStrength": 7,
		"cityHealth": 25,
		"culture": 2,
		"hurryCostModifier": 25,
		"requiredBuilding": "Walls",
		"uniques": ["[+1 Gold] [in this city] <after discovering [Flight]>", "Destroyed when the city is captured"],
		"requiredTech": "Chivalry"
	},
	// Renaissance Era
	{
		"name": "Ceilidh Hall",
		"replaces": "Opera House",
		"uniqueTo": "Skiuma",
		"culture": 4,
		"happiness": 3,
		"specialistSlots": {"Artist": 1},
		"hurryCostModifier": 10,
		"requiredBuilding": "Amphitheater",
		"maintenance": 2,
		"requiredTech": "Acoustics",
		"uniques": ["Destroyed when the city is captured"]
	},
	{
		"name": "Satrap's Court",
		"replaces": "Bank",
		"uniqueTo": "Skiuma",
		"gold": 2,
		"specialistSlots": {"Merchant": 1},
		"happiness": 2,
		"hurryCostModifier": 15,
		"percentStatBonus": {"gold": 25},
		"requiredBuilding": "Market",
		"requiredTech": "Banking"
	},
	{
		"name": "Coffee House",
		"replaces": "Windmill",
		"uniqueTo": "Dicesun",
		"production": 2,
		"percentStatBonus": {"production": 10},
		"specialistSlots": {"Engineer": 1},
		"hurryCostModifier": 25,
		"maintenance": 2,
		"uniques": ["[+25]% Great Person generation [in this city]"],
		"requiredTech": "Economics"
	},
	//Special
  {
		"name": "Park",
	  	"uniqueTo": "Dicesun",
		"uniques": ["[+25]% Great Person generation [in this city]", "[+25]% [Food] [in this city]"],
		"hurryCostModifier": 25,
		"maintenance": 3,
	  	"requiredBuilding": "Garden",
		"requiredTech": "Fertilizer"
	},
{
		"name": "Commercial Dock",
		"uniqueTo": "Dicesun",
		"gold": 2,
		"cost": 220,
		"maintenance": 2,
		"hurryCostModifier": 25,
		"uniques": ["[+2 Gold] from [Water resource] tiles [in this city]",
			"Connects trade routes over water","Must be next to [Coast]"],
		"requiredBuilding": "Harbor",
		"requiredTech": "Navigation"
	},
	{
		"name": "Supermarket",
	        "uniqueTo": "Skiuma",
		"gold": 3,
		"specialistSlots": {"Merchant": 2},
		"hurryCostModifier": 25,
		"percentStatBonus": {"gold": 25},
		"uniques": ["[+1 Food] [in this city]"],
		"requiredBuilding": "Market",
		"requiredTech": "Refrigeration"
	},
	{
		"name": "Mall",
		"uniqueTo": "Skiuma",
		"gold": 5,
		"specialistSlots": {"Merchant": 2},
		"hurryCostModifier": 25,
		"percentStatBonus": {"gold": 35},
		"uniques": ["[+1 Food] [in this city]","[+1 Happiness] [in this city]"],
		"requiredBuilding": "Supermarket",
		"requiredTech": "Telecommunications"
	}
  ]
  [
    {
        "name": "Tradition",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 30,
            "Cultural": 30,
            "Diplomatic": 0,
            "Domination": 0,
            "Scientific": 30
        },
        "uniques": [
            "[+3 Culture] [in capital]",
            "[-25]% Culture cost of natural border growth [in all cities]"
        ],
        "policies": [
            {
                "name": "Aristocracy",
                "uniques": [
                    "[+15]% Production when constructing [All] wonders [in all cities]",
                    "[+1 Happiness] per [10] population [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Legalism",
                "uniques": [
                    "Provides the cheapest [Culture] building in your first [4] cities for free"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Oligarchy",
                "uniques": [
                    "Units in cities cost no Maintenance",
                    "[+50]% Strength for cities <with a garrison> <when attacking>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Landed Elite",
                "uniques": [
                    "[+10]% growth [in capital]",
                    "[+2 Food] [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Monarchy",
                "uniques": [
                    "[+1 Gold, +1 Happiness] per [2] population [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Tradition Complete",
                "uniques": [
                    "[+15]% growth [in all cities]",
                    "Provides a [Aqueduct] in your first [4] cities for free"
                ]
            }
        ]
    },
    {
        "name": "Liberty",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 30,
            "Cultural": 0,
            "Diplomatic": 30,
            "Domination": 30,
            "Scientific": 0
        },
        "uniques": ["[+1 Culture] [in all cities]"],
        "policies": [
            {
                "name": "Republic",
                "uniques": [
                    "[+1 Production] [in all cities]",
                    "[+5]% Production when constructing [All] buildings [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Citizenship",
                "uniques": [
                    "[-25]% tile improvement construction time",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Collective Rule",
                "uniques": [
                    "[+50]% Production when constructing [Settler] units [in capital]",
                    "Free [Settler] appears"
                ],
                "requires": ["Republic"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Representation",
                "uniques": [
                    "Each city founded increases culture cost of policies [33]% less than normal",
                    "Empire enters golden age"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Meritocracy",
                "uniques": [
                    "[+1 Happiness] [in all cities connected to capital]",
                    "[-5]% Unhappiness from [Population] [in all non-occupied cities]"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Liberty Complete",
                "uniques": ["Free Great Person"]
            }
        ]
    },
    {
        "name": "Honor",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 0,
            "Cultural": 0,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 10
        },
        "uniques": [
            "[+33]% Strength <vs [Barbarian] units>",
            "Earn [100]% of killed [Barbarian] unit's [Strength] as [Culture]",
            "Notified of new Barbarian encampments"
        ],
        "policies": [
            {
                "name": "Warrior Code",
                "uniques": [
                    "[+15]% Production when constructing [Melee] units [in all cities]",
                    "Free [Great General] appears"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Discipline",
                "uniques": [
                    "[+15]% Strength <for [Melee] units> <when adjacent to a [Melee] unit>"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Military Tradition",
                "uniques": [
                    "[+50]% XP gained from combat <for [Military] units>"
                ],
                "requires": ["Warrior Code"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Military Caste",
                "uniques": [
                    "[+1 Happiness, +2 Culture] [in all cities with a garrison]"
                ],
                "requires": ["Discipline"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Professional Army",
                "uniques": [
                    "[-33]% Gold cost of upgrading <for [Military] units>",
                    "[+1 Happiness] from every [Walls]",
                    "[+1 Happiness] from every [Castle]",
                    "[+1 Happiness] from every [Arsenal]",
                    "[+1 Happiness] from every [Military Base]"
                ],
                "requires": ["Military Caste"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Honor Complete",
                "uniques": [
                    "Earn [10]% of killed [Military] unit's [Cost] as [Gold]"
                ]
            }
        ]
    },
    {
        "name": "Piety",
        "era": "Classical era",
        "priorities": {
            "Neutral": 0,
            "Cultural": 10,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 0
        },
        "uniques": [
            "[+100]% Production when constructing [Shrine] buildings [in all cities]",
            "[+100]% Production when constructing [Temple] buildings [in all cities]"
        ],
        "policies": [
            {
                "name": "Organized Religion",
                "uniques": [
                    "[+1 Faith] from every [Shrine]",
                    "[+1 Faith] from every [Temple]"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Mandate Of Heaven",
                "uniques": ["[50]% of excess happiness converted to [Culture]"],
                "row": 1,
                "column": 5
            },
            {
                "name": "Theocracy",
                "uniques": ["[+10]% [Gold] from every [Temple]"],
                "requires": ["Organized Religion"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Reformation",
                "uniques": [
                    "[+33]% [Culture] [in all cities with a world wonder]",
                    "Empire enters golden age"
                ],
                "requires": ["Organized Religion"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Free Religion",
                "uniques": ["[-10]% Culture cost of adopting new Policies"],
                "requires": ["Mandate Of Heaven", "Reformation"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Piety Complete",
                "uniques": [
                    "[Faith] cost of purchasing items in cities [-20]%",
                    "[+3 Gold, +3 Culture] from every [Holy site]"
                ]
            }
        ]
    },
    {
        "name": "Patronage",
        "era": "Medieval era",
        "priorities": {
            "Neutral": 0,
            "Cultural": 10,
            "Diplomatic": 20,
            "Domination": 0,
            "Scientific": 10
        },
        "uniques": ["[-25]% City-State Influence degradation"],
        "policies": [
            {
                "name": "Philantropy",
                "uniques": [
                    "Gifts of Gold to City-States generate [25]% more Influence"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Aesthetics",
                "uniques": [
                    "Resting point for Influence with City-States is increased by [20]"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Scholasticism",
                "uniques": [
                    "Allied City-States provide [Science] equal to [25]% of what they produce for themselves"
                ],
                "requires": ["Philantropy"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Cultural Diplomacy",
                "uniques": [
                    "[+100]% resources gifted by City-States",
                    "[+50]% Happiness from luxury resources gifted by City-States"
                ],
                "requires": ["Scholasticism"],
                "row": 3,
                "column": 2
            },
            {
                "name": "Educated Elite",
                "requires": ["Scholasticism", "Aesthetics"],
                "uniques": [
                    "Allied City-States will occasionally gift Great People"
                ],
                "row": 3,
                "column": 4
            },
            {
                "name": "Patronage Complete",
                "uniques": [
                    "Influence of all other civilizations with all city-states degrades [33]% faster",
                    "Triggers the following global alert: [Our influence with City-States has started dropping faster!]"
                ]
            }
        ]
    },
    {
        "name": "Commerce",
        "era": "Medieval era",
        "priorities": {
            "Neutral": 0,
            "Cultural": 10,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 10
        },
        "uniques": ["[+25]% [Gold] [in capital]"],
        "policies": [
            {
                "name": "Naval Tradition",
                "uniques": [
                    "[+1] Movement <for [{Military} {Water}] units>",
                    "[+1] Sight <for [{Military} {Water}] units>",
                    "Free [Great General] appears"
                    // "[+2] Movement <for [Great Admiral] units>"
                    // ToDo: Should be "Free [Great Admiral] appears"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Trade Unions",
                "uniques": [
                    "[-33]% maintenance on road & railroads",
                    "[+1 Gold] from every [Harbor]",
                    "[+1 Gold] from every [Seaport]"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Merchant Navy",
                "uniques": ["[+3 Production] [in all coastal cities]"],
                "requires": ["Naval Tradition"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Mercantilism",
                "uniques": [
                    "[Gold] cost of purchasing items in cities [-25]%",
                    "[+1 Science] from every [Mint]",
                    "[+1 Science] from every [Market]",
                    "[+1 Science] from every [Bank]",
                    "[+1 Science] from every [Stock Exchange]"
                ],
                "requires": ["Trade Unions"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Protectionism",
                "uniques": ["[+2] Happiness from each type of luxury resource"],
                "requires": ["Mercantilism"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Commerce Complete",
                "uniques": [
                    "[+1 Gold] from every [Trading post]",
                    "[+100]% Gold from Great Merchant trade missions",
                    "May buy [Great Merchant] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Rationalism",
        "era": "Renaissance era",
        "priorities": {
            "Neutral": 0,
            "Cultural": 10,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 20
        },
        "uniques": [
            "[+15]% [Science] <while the empire is happy>"
        ],
        "policies": [
            {
                "name": "Secularism",
                "uniques": [
                    "[+2 Science] from every specialist [in all cities]"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Humanism",
                "uniques": [
                    "[+1 Happiness] from every [University]",
                    "[+1 Happiness] from every [Observatory]",
                    "[+1 Happiness] from every [Public School]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Free Thought",
                "uniques": [
                    "[+1 Science] from every [Trading post]",
                    "[+17]% [Science] from every [University]"
                ],
                "requires": ["Secularism"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Sovereignty",
                "uniques": ["[+1 Gold] from all [Science] buildings"],
                "requires": ["Humanism"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Scientific Revolution",
                "uniques": ["Science gained from research agreements [+50]%"],
                "requires": ["Free Thought"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Rationalism Complete",
                "uniques": [
                    "[2] Free Technologies",
                    "May buy [Great Scientist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Freedom",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 50,
            "Cultural": 50,
            "Diplomatic": 50,
            "Domination": 40,
            "Scientific": 50
        },
        "uniques": [
            "[+25]% Great Person generation [in all cities]",
            "Only available <before adopting [Autocracy]>"
        ],
        "policies": [
            {
                "name": "Constitution",
                "uniques": ["[+3 Culture] from every [Wonder]"],
                "row": 1,
                "column": 1
            },
            {
                "name": "Universal Suffrage",
                "uniques": ["[+33]% Strength for cities <when defending>"],
                "row": 1,
                "column": 3
            },
            {
                "name": "Civil Society",
                "uniques": [
                    "[-50]% Food consumption by specialists [in all cities]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Free Speech",
                "uniques": ["[8] units cost no maintenance"],
                "requires": ["Constitution"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Democracy",
                "uniques": [
                    "[-50]% Unhappiness from [Specialists] [in all cities]"
                ],
                "requires": ["Civil Society"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Freedom Complete",
                "uniques": [
                    "[+100]% Yield from every [Great Improvement]",
                    "[+50]% Golden Age length",
                    "May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Autocracy",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 50,
            "Cultural": 40,
            "Diplomatic": 40,
            "Domination": 50,
            "Scientific": 40
        },
        "uniques": [
            "[-33]% maintenance costs <for [All] units>",
            "Upon capturing a city, receive [10] times its [Culture] production as [Culture] immediately",
            "Only available <before adopting [Freedom]>"
        ],
        "policies": [
            {
                "name": "Populism",
                "uniques": ["[+30]% Strength <for [Wounded] units>"],
                "row": 1,
                "column": 1
            },
            {
                "name": "Militarism",
                "uniques": ["[Gold] cost of purchasing [All] units [-33]%"],
                "row": 1,
                "column": 5
            },
            {
                "name": "Fascism",
                "uniques": [
                    "Quantity of strategic resources produced by the empire +[100]%",
                    "[+2] Movement <for [Great General] units>"
                ],
                "requires": ["Populism", "Militarism"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Police State",
                "uniques": [
                    "[+3 Happiness] from every [Courthouse]",
                    "[+100]% Production when constructing [Courthouse] buildings [in all cities]"
                ],
                // There are also some uniques regarding espoinage, which as of this writing is not yet implemented
                "requires": ["Militarism"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Total War",
                "uniques": [
                    "[+25]% Production when constructing [Military] units [in all cities]",
                    "New [Military] units start with [15] Experience [in all cities]"
                ],
                "requires": ["Police State", "Fascism"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Autocracy Complete",
                "uniques": [
                    "[+25]% Strength <when attacking> <for [Military] units> <for [50] turns>",
                    "May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>",
                    "May buy [Great Admiral] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Order",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 50,
            "Cultural": 40,
            "Diplomatic": 50,
            "Domination": 40,
            "Scientific": 50
        },
        "uniques": [
            "[+1 Happiness] [in all cities]"
        ],
        "policies": [
            {
                "name": "United Front",
                "uniques": [
                    "Militaristic City-States grant units [2] times as fast when you are at war with a common nation"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Planned Economy",
                "uniques": [
                    "[+25]% [Science] from every [Factory]",
                    "[+100]% Production when constructing [Factory] buildings [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Nationalism",
                "uniques": [
                    "[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Socialism",
                "requires": ["Planned Economy"],
                "uniques": [
                    "[-15]% maintenance cost for buildings [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
            {
                "name": "Communism",
                "requires": ["Socialism"],
                "uniques": [
                    "[+2 Production] [in all cities]",
                    "[+1 Production] from every [Mine]",
                    "[+1 Production] from every [Quarry]"
                ],
                "row": 3,
                "column": 3
            },
            {
                "name": "Order Complete",
                "uniques": [
                    "[+2 Food, +2 Production, +2 Science, +2 Gold, +2 Culture] [in all cities]",
                    "May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    }
]
