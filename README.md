# non-equidistant-algorithm
This repository contains two versions of the non-equdistant algorithm. 
The master branch is with minor modifications from https://github.com/dcoeurjo/CorrectedNormalCurrent.
The no-GUI branch is as the name insist, no gui will show during the calculation, making it more convinient to be implemented in an automation progress.
This program works together with the the matlab .m file, and to avoid libstdc++.so.6 error in the matlab cmd window, the script should be ran in sudo mode. 

Further, to avoid entering the sudo passwd during the calculation progress, the files in /etc/sudoer.d should be modified, according to https://superuser.com/questions/869144/why-does-the-system-have-etc-sudoers-d-how-should-i-edit-it/869185

