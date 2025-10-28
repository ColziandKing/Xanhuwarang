//poli
    {
        "name": "Humor",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 0,
            "Diplomatic": 0,
            "Domination": 10,
            "Scientific": 0
        },
        "uniques": [
            "[+1 Happiness] per [2] population [in all cities]",
		 "Adopt [Comedic Journalism]", 
        ],
        "policies": [
            {
                "name": "Comedic Journalism",
                "uniques": [
                    "[+2 Happiness] from every [Broadcast Tower]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Gelotology",
                "uniques": [
                    "[+1 Happiness] from every [Medical Lab]","[+1 Happiness] from every [Hospital]"
                ],
				"requires": [
					"Comedic Journalism"
				],
                "row": 2,
                "column": 3
            },
            {
                "name": "Kabarett",
                "uniques": [
                    "[+2 Culture, +1 Happiness] from every [Amphitheater]","[+2 Culture, +1 Happiness] from every [Theatre]"
                ],
				"requires": [
					"Comedic Journalism"
				],
                "row": 2,
                "column": 5
            },
            {
                "name": "Political Cartoon",
                "uniques": [
                    "[+1 Happiness] from all [Culture] buildings <when below [-10] [Happiness]>"
                ],
				"requires": [
					"Comedic Journalism"
				],
                "row": 2,
                "column": 1
            },
            {
                "name": "Political Satire",
                "uniques": [
                    "[+1 Happiness] per every [8] [Culture]"
                ],
				"requires": [
					"Gelotology"
				],
                "row": 3,
                "column": 3
            },
			//JL
            {
                "name": "Resource Contracts",
                "requires": ["Kabarett"],
                "uniques": [
		    "Influence of all other civilizations with all city-states degrades [25]% faster", "Triggers the following global alert: [Our influence with City-States has started dropping faster!]"
                ],
                "row": 3,
                "column": 1
            },
            {
                "name": "World Expo",
                "requires": ["Political Cartoon"],
                "uniques": [
                    "Science gained from research agreements [+50]%", 
            "When declaring friendship, both parties gain a [15]% boost to great person generation",
                ],
                "row": 3,
                "column": 5
            },
            {
                "name": "Humor Complete",
                "uniques": [
                    "[+2 Happiness, +1 Culture] per [2] population [in all cities]"
                ]
            }
        ]
    },
    {
        "name": "Voluntarism",
        "era": "Future era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 0,
            "Diplomatic": 0,
            "Domination": 10,
            "Scientific": 0
        },
        "uniques": [
			"Comment [Obsolete with [Civ V Brave New World]]",
			"Unavailable",
			"Will not be displayed in Civilopedia",
			"[-100]% weight to this choice for AI decisions",
		],
        "policies": [
            {
                "name": "Anarchism",
                "uniques": [
                    "[-50]% unhappiness from the number of cities"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Black Bloc",
                "uniques": [
                    "No movement cost to pillage",
                    "Empire enters golden age <upon declaring war on [Major] Civilizations>",
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Insurgent Army",
                "uniques": [
                    "[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Mutual Aid",
                "uniques": [
                    "Allied City-States provide [Gold] equal to [+30]% of what they produce for themselves","Allied City-States provide [Food] equal to [+40]% of what they produce for themselves"
                ],
                "row": 2,
                "column": 1
            },
            {
                "name": "Self-Organization",
                "uniques": [
                    "[+15]% [Production] [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
			//JL
            {
                "name": "Foreign Aid",
                "uniques": [
                    "Gain [15] Influence with a [Military] gift to a City-State", "Military Units gifted from City-States start with [+10] XP"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Mercenary Opportunism",
                "uniques": [
                    "When defeating a [Military] unit, earn [10] Gold and recruit it <with [15]% chance>", "[Gold] cost of purchasing [Military] units [-25]%",
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Colonialism",
                "uniques": [
                    "Gain a free [Governor's Mansion] [in this city] <upon founding a city>",
                    "Free [Worker] appears <upon founding a city>",
                ],
                "requires": ["Foreign Aid"],
                "row": 2,
                "column": 2
				},
            {
                "name": "Counter Intelligence",
                "uniques": [
			"Comment [-25% enemy spy effectiveness in all cities] <when espionage is enabled>",
			"Comment [+1 [Happiness] in all cities] <when espionage is disabled>",
                    "[-25]% enemy spy effectiveness [in all cities] <when espionage is enabled> <hidden from users>",
		    "[+1 Happiness] [in all cities] <when espionage is disabled> <hidden from users>",
		    "Comment [+50% [Production] when constructing defensive buildings]",
		    "[+50]% Production when constructing [Walls] buildings [in all cities] <hidden from users>",
		    "[+50]% Production when constructing [Castle] buildings [in all cities] <hidden from users>",
		    "[+50]% Production when constructing [Arsenal] buildings [in all cities] <hidden from users>",
		    "[+50]% Production when constructing [Military Base] buildings [in all cities] <hidden from users>",
		    "[+50]% Production when constructing [Air Defense System] buildings [in all cities] <hidden from users>"
                ],
                "requires": ["Mercenary Opportunism"],
                "row": 2,
                "column": 4
            },
            {
                "name": "State Logistics",
                "uniques": [
                    "[-25]% maintenance on road & railroads", "Improves movement speed on roads"
                ],
                "requires": ["Black Bloc"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Market Economy",
                "uniques": ["[-50]% maintenance cost for [all] buildings [in all cities]"],
                "requires": ["Colonialism"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Voluntarism Complete",
                "uniques": [
                ]
            }
        ]
	},
  //event
	{
		"name": "New Policy",
		"text": "Don't be shy, choose a policy. You have reached this era, behold the machinery and a new age for mankind!",
		"presentation": "Alert",
		"choices": [
			{
				"text": "Resource Contracts",
				"uniques": [
		 			"Adopt [Resource Contracts]",
				]
			},
			{
				"text": "Colonialism",
				"uniques": [
		 			"Adopt [Colonialism]",
				]
			},
			{
				"text": "Counter Intelligence",
				"uniques": [
		 			"Adopt [Counter Intelligence]",
				]
			},
			{
				"text": "Black Bloc",
				"uniques": [
		 			"Adopt [Black Bloc]",
				]
			},
			{
				"text": "State Logistics",
				"uniques": [
		 			"Adopt [State Logistics]",
				]
			},
			{
				"text": "Mercenary Opportunism",
				"uniques": [
		 			"Adopt [Mercenary Opportunism]",
				]
			},
			{
				"text": "Market Economy",
				"uniques": [
		 			"Adopt [Market Economy]",
				]
			},
			{
				"text": "Foreign Aid",
				"uniques": [
		 			"Adopt [Foreign Aid]",
				]
			},
			{
				"text": "World Expo",
				"uniques": [
		 			"Adopt [World Expo]",
				]
			}
		]
	},
