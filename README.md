# download_sequencing_data_lftp



lftp ftp://gslanalyzer.qb3.berkeley.edu:990 -e 'set ssl:verify-certificate no set ftp:ssl-protect-data true set ftp:ssl-force true; open -u $username,$password -e "mirror -c; quit'

