# autoMetasploit
Ruby script to automate metasploit scanning, exploitation, and post-exploitation

Configuration:

To do most of job, install pentest plugin first.

mkdir –p $HOME/.msf4/plugins

cd $HOME/.msf4/plugins

wget https://raw.github.com/darkoperator/Metasploit-Plugins/master/pentest.rb

To create the final report, download the report's XSLT template from my other project at:
https://github.com/paulosgf/metasploitReportTemplate

To send PDF report email (Gmail), use my Metasploit plugin reportEmail at:
https://github.com/paulosgf/reportEmail

Install the ldap-utils package to enumerate LDAP users no targeet too.
