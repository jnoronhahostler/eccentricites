# eccentricites
c++ code to calculate eccentricites of initial conditions

this code assumes events are in files called ic1.dat, ic2.dat etc... the first event number is ev1 and the last is ev2 (so it assumes that they are sequential).
then the input files should be of the format: x y rho*
where rho could be energy density, entropy density (it doesn't matter)
To run the code:
c++ eccCM.cpp -o eccCM
./eccCM INPUTFILE_NAME Event_first Event_final 
if there is a first line of a header run it as:
./eccCM INPUTFILE_NAME Event_first Event_final head
the input could easily be changed and comments are in the code on how to do that

ec22     psi22       ec23     psi23      ec24     psi24      ec25     psi25      ec26     psi26      ec15     psi15      ec33     psi33      ec34     psi34      ec35     psi35      ec36     psi36  ec12     psi12     ec44     psi44     ec13     psi13   <radius^2>
