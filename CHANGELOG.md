## 0.2.2
 * New get-cn-from-x500-principal function to extract the CN from a DN stored in an `X500Principal` object
 * New get-extensions function retrieve extension OIDs and values on an object which implements `X509Extension`  

## 0.2.1
 * New pem->public-key function

## 0.2.0
 * New pem->crl and crl->pem! functions for working with CRLs
 * New pem->cert and cert->pem! functions for working with a certificate
 * Remove issued-by? and has-subject? functions from API

## 0.1.5
 * New predicate functions for checking the types of various objects
 * Deployment artifacts now include a source jar, which contains the java sources
 * Explicitly target JDK 1.6 when compiling java files