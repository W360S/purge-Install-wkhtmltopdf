Remove existing installation:

sudo apt-get remove --purge wkhtmltopdf

Download wkhtmltopdf patched with qt using below command

sudo wget -P Downloads http://download.gna.org/wkhtmltopdf/0.12/0.12.1/wkhtmltox-0.12.1_linux-trusty-amd64.deb

Here, replace "trusty" with your OS name and if 64 bit only then keep "amd64" like that , otherwise change it to "i386" and down load the deb file.

After that execute the following commands,

cd ~/Downloads

sudo dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb

Now, check wkhtmltopdf version with below command,

wkhtmltopdf -V
