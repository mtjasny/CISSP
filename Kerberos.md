User authenticates to the workstation.
Client/[[TGS]] key genrated
These credentials are forwarded to Authentication Service on the [[KDC]]
[[KDC]] returns time-stamped [[TGT]] encrypted with [[TGS]] secret key (symetric key encrypted a hash of user's password) + session key
[[TGT]] is presented to [[TGS]] which returns the [[service ticket]] encrypted with service secret key.
Workstation present the service key to the service - mutual authentication occurs.
Realm trust - 
Shotcut trust - transitive trust between parts of domain tree or forest that shortens the trust path
Forest trust - transitive trust between two forest root domains
External trust - nontrasitive trust between AD domains in separate forests

Single-sign on
[[AES]] is encryption used to encrypt username and password

[[KDC]] = AS + [[TGS]]

Time sensitive (max. 5 minutes differnece allowed)