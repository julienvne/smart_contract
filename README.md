##################################################################################################
#                                         README
#
#  Welcome to Reputezos, a reputation-based life simulation game. Your aim throughout 
#  the game will be to look after your character and help him or her gain reputation.
#
#  When creating your character, you'll need to bet a number of tez (minimum 1). 
#  If, at the end of the month, you're the person with the highest reputation in the 
#  game, you'll be able to claim and double your initial bet will be sent to you.
#
#  Throughout the game, you'll be able to perform various actions according to your role,
#  in an attempt to improve your reputation.
#
#   Let's look in detail at the different roles and how to gain or lose reputation.
#
#  Citizen:                                       Employe:
#  It's the default role, you can:                It is obtained by applying to job offers, you can:
#    - Sleep (1x per day)                           - Sleep (1x per day)
#    - Apply for a job (1x per day)                 - Work (1x per day)
#    - Carry out assignments                        - Resign
#                                                   - Carry out assignments
#      Reputation-boosting actions:
#      - Carry out assignments                    Reputation-boosting actions:
#                                                 - Work
#      Reputation-destroying actions              - Carry out assignment
#      - Carry out assignments
#                                                 Reputation-destroying actions:
#                                                 - Work
#                                                 - Carry out assignment
#
#  Boss:                                          Mayor:
#  It is obtained by applying to job offers,      It is obtained by the first player to join  
#  or by being promoted because you are the       the game, or by the player with the highest 
#  employee with the greatest reputation when     reputation if he resigns. You can:
#  the boss resigns. You can:                        - Sleep (1x per day)
#     - Sleep (1x per day)                           - Crisis management (1x per week)
#     - Pay employees according to the               - Pardon a prisoner (1x per mandate)
#       number of hours they work and                - Resign
#       give the expected number for                 - Carry out assignments
#       the following week (1x per week)          
#     - Resign                                       Reputation-boosting actions:
#     - Carry out assignments                        - Pardon a prisoner
#                                                    - Crisis management (big gain)
#     Reputation-boosting actions:                   - Carry out assignments
#     - pay employees                                
#     - Carry out assignments                        Reputation-destroying actions:
#                                                    - Crisis management (big loss)
#     Reputation-destroying actions:                 - Carry out assignments
#     - forgot to pay employees
#
#  Policeman:                                    Prisoner:
#  it is obtained by applying to                 it is obtained when one is arrested with 
#  job offers, you can:                          more than 10 crimes, you can:
#     - Sleep (1x per day)                           - Sleep (1x per day)
#     - Arresting people (2x per week)               - Try to escape (3 trials)       <- not enough time to implement it
#     - Release the prisoners
#     - Resign      
#     - Carry out assignments
#      
#      Reputation-boosting actions:
#      - Arresting people
#      - Carry out assignments
#
#      Reputation-destroying actions:
#      - Forgot to release prisoners
#      - Carry out assignments
#
#  The duration (in seconds) of a day in the game must be initialized at the start of the playerController
#
#  Now that you know a little more about how to play Reputezos, you're free to try it out and adopt it. 
#
#  (At the beginning of the implementation we thought we could use randoms, but we saw that this 
#  wasn't possible in the end, so we created our own version which does the trick in our case)
#
##################################################################################################
