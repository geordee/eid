# Validate Emirates ID

Emirates ID is an identity card issued by Federal Authority for Identity and Citizenship of United Arab Emirates. This script validates Emirates ID format and check digit. A practical constraint is included to allow birth years between 1900 and 2099 only.

## Program Logic

1. Validate Emirates ID using the regular expression ```/784[-]*(19|20)\d{2}[-]*\d{7}[-]*\d/```
2. Use Luhn algorithm to calculate check digit and compare

## References

- https://u.ae/en/information-and-services/visa-and-emirates-id/emirates-id
- https://www.ica.gov.ae/en/services/e-services/id-card-status.aspx
- https://en.wikipedia.org/wiki/Luhn_algorithm
