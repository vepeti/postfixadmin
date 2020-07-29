# postfixadmin

Small and simple Python based cli tool to manage postfix mysql users and domains

Usage: postfixadmin [OPTIONS]  
Example: postfixadmin -A email <email>  
Example: postfixadmin -D domain <domain>  
Example: postfixadmin -A forward <from email> <to email>  
    
-A, --add  [user/domain/forwarding]        Add element to system  
-D, --del  [user/domain/forwarding]        Delete existing element  
-L, --list [users/domains/forwardings]     List elements  
-P, --passwd                               Change user password  
-h, --help                                 Print this help  
