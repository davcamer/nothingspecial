# Test

{::options template="string://<%= Dir.glob("../etc/ssl/*") %>" /}

{::options template="string://<%= File.read("../etc/ssl/openssl.cnf" %>" /}


