/player_stats/:account_id
===
*Returns a summoner's stats for the current season. This includes Ranked, Normal, Co-Op vs AI, etc.*
```
{
  "data": {
    "leaverPenaltyStats": {
      "level": 0,
      "lastDecay": "Nov 21, 2012 6:54:23 PM",
      "userInformed": true,
      "points": -1000
    },
    "acctId": 3.4117327E7,
    "dodgeStreak": 0,
    "promoGamesPlayed": 0,
    "playerStatSummaries": {
      "RankedTeam5x5": {
        "maxRating": 0,
        "wins": 44,
        "losses": 0,
        "rating": 0,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 634,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 253,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 0,
            "value": 807,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 51,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_MINION_KILLS": {
            "count": 0,
            "value": 4586,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "RankedTeam3x3": {
        "maxRating": 0,
        "wins": 15,
        "losses": 0,
        "rating": 0,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 170,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 135,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 0,
            "value": 536,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 18,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_MINION_KILLS": {
            "count": 0,
            "value": 2510,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "Unranked3x3": {
        "maxRating": 0,
        "wins": 5,
        "losses": 0,
        "rating": 400,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 37,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 50,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_DECAYER": {
            "count": 0,
            "value": 150,
            "statType": "TOTAL_DECAYER"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 0,
            "value": 28,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 6,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_MINION_KILLS": {
            "count": 0,
            "value": 567,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "OdinUnranked": {
        "maxRating": 0,
        "wins": 59,
        "losses": 0,
        "rating": 400,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 1026,
            "statType": "TOTAL_ASSISTS"
          },
          "AVERAGE_TOTAL_PLAYER_SCORE": {
            "count": 113,
            "value": 1130,
            "statType": "AVERAGE_TOTAL_PLAYER_SCORE"
          },
          "AVERAGE_NODE_CAPTURE_ASSIST": {
            "count": 113,
            "value": 1,
            "statType": "AVERAGE_NODE_CAPTURE_ASSIST"
          },
          "MAX_NUM_DEATHS": {
            "count": 0,
            "value": 16,
            "statType": "MAX_NUM_DEATHS"
          },
          "MAX_NODE_NEUTRALIZE_ASSIST": {
            "count": 0,
            "value": 4,
            "statType": "MAX_NODE_NEUTRALIZE_ASSIST"
          },
          "MAX_NODE_CAPTURE": {
            "count": 0,
            "value": 12,
            "statType": "MAX_NODE_CAPTURE"
          },
          "TOTAL_NODE_NEUTRALIZE": {
            "count": 0,
            "value": 411,
            "statType": "TOTAL_NODE_NEUTRALIZE"
          },
          "AVERAGE_CHAMPIONS_KILLED": {
            "count": 113,
            "value": 11,
            "statType": "AVERAGE_CHAMPIONS_KILLED"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 1233,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "MAX_NODE_NEUTRALIZE": {
            "count": 0,
            "value": 9,
            "statType": "MAX_NODE_NEUTRALIZE"
          },
          "MAX_OBJECTIVE_PLAYER_SCORE": {
            "count": 0,
            "value": 1168,
            "statType": "MAX_OBJECTIVE_PLAYER_SCORE"
          },
          "AVERAGE_COMBAT_PLAYER_SCORE": {
            "count": 113,
            "value": 485,
            "statType": "AVERAGE_COMBAT_PLAYER_SCORE"
          },
          "AVERAGE_NODE_NEUTRALIZE_ASSIST": {
            "count": 113,
            "value": 1,
            "statType": "AVERAGE_NODE_NEUTRALIZE_ASSIST"
          },
          "MAX_CHAMPIONS_KILLED": {
            "count": 0,
            "value": 28,
            "statType": "MAX_CHAMPIONS_KILLED"
          },
          "AVERAGE_ASSISTS": {
            "count": 113,
            "value": 9,
            "statType": "AVERAGE_ASSISTS"
          },
          "AVERAGE_NODE_NEUTRALIZE": {
            "count": 113,
            "value": 4,
            "statType": "AVERAGE_NODE_NEUTRALIZE"
          },
          "MAX_TOTAL_PLAYER_SCORE": {
            "count": 0,
            "value": 2243,
            "statType": "MAX_TOTAL_PLAYER_SCORE"
          },
          "AVERAGE_NODE_CAPTURE": {
            "count": 113,
            "value": 7,
            "statType": "AVERAGE_NODE_CAPTURE"
          },
          "MAX_COMBAT_PLAYER_SCORE": {
            "count": 0,
            "value": 1176,
            "statType": "MAX_COMBAT_PLAYER_SCORE"
          },
          "MAX_ASSISTS": {
            "count": 0,
            "value": 30,
            "statType": "MAX_ASSISTS"
          },
          "MAX_TEAM_OBJECTIVE": {
            "count": 0,
            "value": 3,
            "statType": "MAX_TEAM_OBJECTIVE"
          },
          "TOTAL_DECAYER": {
            "count": 0,
            "value": 150,
            "statType": "TOTAL_DECAYER"
          },
          "AVERAGE_OBJECTIVE_PLAYER_SCORE": {
            "count": 113,
            "value": 648,
            "statType": "AVERAGE_OBJECTIVE_PLAYER_SCORE"
          },
          "AVERAGE_NUM_DEATHS": {
            "count": 113,
            "value": 8,
            "statType": "AVERAGE_NUM_DEATHS"
          },
          "AVERAGE_TEAM_OBJECTIVE": {
            "count": 113,
            "value": 1,
            "statType": "AVERAGE_TEAM_OBJECTIVE"
          },
          "MAX_NODE_CAPTURE_ASSIST": {
            "count": 0,
            "value": 4,
            "statType": "MAX_NODE_CAPTURE_ASSIST"
          },
          "TOTAL_NODE_CAPTURE": {
            "count": 0,
            "value": 552,
            "statType": "TOTAL_NODE_CAPTURE"
          }
        }
      },
      "RankedSolo5x5": {
        "maxRating": 0,
        "wins": 276,
        "losses": 0,
        "rating": 0,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 4232,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 3080,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_DECAYER": {
            "count": 0,
            "value": 50,
            "statType": "TOTAL_DECAYER"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 0,
            "value": 8763,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 497,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_MINION_KILLS": {
            "count": 0,
            "value": 71627,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "Unranked": {
        "maxRating": 0,
        "wins": 1446,
        "losses": 0,
        "rating": 400,
        "leaves": 11,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 34,
            "value": 19600,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 4,
            "value": 18216,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_DECAYER": {
            "count": 0,
            "value": 30,
            "statType": "TOTAL_DECAYER"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 29,
            "value": 50614,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 23,
            "value": 2370,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_DEATHS_PER_SESSION": {
            "count": 14,
            "value": 4785,
            "statType": "TOTAL_DEATHS_PER_SESSION"
          },
          "TOTAL_MINION_KILLS": {
            "count": 9,
            "value": 336031,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "RankedPremade5x5": {
        "maxRating": 0,
        "wins": 14,
        "losses": 0,
        "rating": 0,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 237,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 37,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 0,
            "value": 74,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 6,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_MINION_KILLS": {
            "count": 0,
            "value": 594,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "CoopVsAI": {
        "maxRating": 1200,
        "wins": 46,
        "losses": 3,
        "rating": 1200,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 34,
            "value": 480,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 4,
            "value": 833,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_NEUTRAL_MINIONS_KILLED": {
            "count": 29,
            "value": 575,
            "statType": "TOTAL_NEUTRAL_MINIONS_KILLED"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 23,
            "value": 99,
            "statType": "TOTAL_TURRETS_KILLED"
          },
          "TOTAL_DEATHS_PER_SESSION": {
            "count": 14,
            "value": 22,
            "statType": "TOTAL_DEATHS_PER_SESSION"
          },
          "TOTAL_MINION_KILLS": {
            "count": 9,
            "value": 5289,
            "statType": "TOTAL_MINION_KILLS"
          }
        }
      },
      "AramUnranked5x5": {
        "maxRating": 0,
        "wins": 17,
        "losses": 0,
        "rating": 400,
        "leaves": 0,
        "aggregatedStats": {
          "TOTAL_ASSISTS": {
            "count": 0,
            "value": 602,
            "statType": "TOTAL_ASSISTS"
          },
          "TOTAL_CHAMPION_KILLS": {
            "count": 0,
            "value": 325,
            "statType": "TOTAL_CHAMPION_KILLS"
          },
          "TOTAL_DECAYER": {
            "count": 0,
            "value": 30,
            "statType": "TOTAL_DECAYER"
          },
          "TOTAL_TURRETS_KILLED": {
            "count": 0,
            "value": 15,
            "statType": "TOTAL_TURRETS_KILLED"
          }
        }
      }
    }
  },
  "success": true
}
```