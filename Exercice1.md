mkdir cli_tmp
touch je_suis_dans_tmp.txt
cd cli_tmp
touch in_cli_tmp
rm -rf je_suis_dans_tmp
rm -rf je_suis_dans_tmp.txt
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir
mv bachir ../ami
cd cli_tmp
cp -r ami parent
rm -rf bachir
pwd
cd ~
rm -rf cli_tmp