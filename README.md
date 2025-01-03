bind "F10" "toggleconsole; play ui/helpful_event_1; wait 100; play player/survivor/voice/mechanic/askready03" 
bind "F9" "openserverbrowser; play doors/latchunlocked1"
bind "F4" "disconnect"
"cl_interp "0.0333
cl_interp_ratio "-1
rate "300000"
cl_cmdrate "30"
cl_updaterate "30"
bind p "toggle fov_desired 120 120; toggle cl_viewmodelfovsurvivor 180 120"
bind "TAB" "+scoregraph"
alias +scoregraph "+showscores; net_graph 4"
alias -scoregraph "-showscores; net_graph 0"
bind "l" "say_team go go vamos vamos
bind "ñ" "say_team !bonus"
fps_max 120
bind i "toggle fov_desired 150 150; toggle cl_viewmodelfovsurvivor 150 70"
bind u "toggle fov_Desider 150 150; toggle cl_viewmodelfovsurvivor 51  45"
bind o "toggle fov_desired 150 150; toggle cl_viewmodelfovsurvivor 100 100"
bind "x" "+left"
bind "C" "+right"
cl_showpos 1
clear

//Sound

play ui/pickup_misc42; wait 180; play player/survivor/voice/producer/niceshot02.wav

//Text Printing in Console

echo "
echo "       .---------------------------------------------------------------."
echo "       |                                                               |"
echo "       |                 => Brandy autoexec loaded <=                  |"
echo "       |                                                               |" 
echo "     --|---------------------------------------------------------------|--"
echo "       |                                                               |"
echo "                                      __                               "
echo "       X                             / /\                             X"
echo "                                    / / /\                             "
echo "                                   / / /\ \                            "
echo "                                  / / /\ \ \                           "
echo "                       __________/_/_/__\ \ \__________                "
echo "       X              /\ \_______________\ \ \_________\              X"
echo "                      \ \ \_______________\ \ \________/               "
echo "                       \ \ \  / / /        \ \ \  / / /                "
echo "                        \ \ \/ / /   Y    D \ \ \/ / /                 "
echo "                         \ \/ / /  D   A     \ \/ / /                  "
echo "       X                  \/ / /     E     Z  \/ / /                  X"
echo "                          / / /\  D     A     / / /\                   "
echo "                         / / /\ \    L    D  / / /\ \                  "
echo "                        / / /\ \ \  X   S   / / /\ \ \                 "
echo "                       /_/_/__\ \ \________/_/_/__\ \ \                "
echo "                      /________\ \ \_______________\ \ \               "
echo "       X              \_________\ \ \_______________\_\/              X"
echo "                                 \ \ \  / / /                          "
echo "                                  \ \ \/ / /                           "
echo "                                   \ \/ / /                            "
echo "                                    \/ / /                             "
echo "       X                             \/_/                             X"
echo "                                                                      
echo
echo
echo " 1 => [Our Discord] : https://discord.com/invite/mCuZSWZrCf              "
echo
echo
echo
echo " 2 => [Steam Group] : https://steamcommunity.com/groups/ApocalypseSector "
echo
echo
echo
echo " 3 =>   [YouTube]   : https://youtube.com/@--Brandy.dll--?si=ih9Xz14CmMRPVNSc"
echo
Alias cleanup0 "cl_destroy_ragdolls"
alias cleanup1 "cl_destroy_ragdolls"
alias cleanup19 "cl_destroy_ragdolls"
alias cleanupPart0 "cleanup1; wait 1; cleanupPart18"
alias cleanupPart18 "cleanup19; wait 1; cleanup0; wait 1; cleanupRestart"
alias cleanupRestart "cleanupPart0"
cleanupPart0
