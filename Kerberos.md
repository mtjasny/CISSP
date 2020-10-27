User authenticates to the workstation.
These credentials are forwarded to Authentication Service on the [[KDC]]
[[KDC]] returns [[TGT]] encrypted with [[TGS]] secret key
[[TGT]] is presented to [[TGS]] which returns the [[service ticket]] encrypted with service secret key.
Workstation present the service key to the service - mutual authentication occurs.