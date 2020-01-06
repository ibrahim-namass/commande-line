pwd
ls
mkdir conteneur
mkdir conteneur/voitures ustensiles electronique
cd conteneur ; cd voitures ; touch mes_voitures.txt
echo "benz toyota honda">>mes_voitures.txt
cd .. ; cd ustensiles
touch cuisine.txt ; echo "casserole passoire poele">>cuisine.txt
cat cuisine.txt
cd .. ;  ls -alts