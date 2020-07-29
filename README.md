# postfixadmin

Small and simple Python based cli tool to manage postfix mysql users and domains

# Requirements
- python3 (>=3.5)
- python3-passlib (>=1.7)
- python3-mysqldb (>=1.3)

# Installation
Run the postfixadmin.deb file, or copy files manually. Place the config file into /etc/postfixadmin folder

# Usage
postfixadmin [OPTIONS]  
Example: postfixadmin -A email <email>  
Example: postfixadmin -D domain <domain>  
Example: postfixadmin -A forward <from email> <to email>  
    
-A, --add  [email/domain/forwarding]       Add element to system  
-D, --del  [email/domain/forwarding]       Delete existing element  
-L, --list [email/domains/forwardings]     List elements  
-P, --passwd                               Change user password  
-h, --help                                 Print this help  
