# incorta_copy_core_site

This script will copy core-site.xml to the needed directories for Intelligent ingest


#Linux usage

Copy cp_core.py to server with Incorta installed

chmod 755 cp_core.py

#Create INCORTA_HOME varible in bashrc pointing to your file path

vi ~/.baschrc
export INCORTA_HOME=/home/incorta/IncortaAnalytics/

source ~/.baschrc

./cp_core.py /path/to/yourfile/core-site.xml

#Windows usage
This script does not run in windows grasshopper