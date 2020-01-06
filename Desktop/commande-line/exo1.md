mkdir cli_tmp
mkdir cli_tmp/je_suis_dans_tmp.txt
cd cli_tmp ; touch in_cli_tmp
mkdir in_cli_tmp
rm -rf je_suis_dans_tmp.txt
cd .. ; rm -rf cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissance
cd grand frere
touch bachir
mv bachir ../ ami
cd .. ; cp -r ami parent
cd grand frere ; rm -rf bachir
pwd
cd ..
rm -rfcli_tmp