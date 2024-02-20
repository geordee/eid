# Validate Emirates ID

Emirates ID is an identity card issued by Federal Authority for Identity and Citizenship of United Arab Emirates. This script validates Emirates ID format and check digit.

## Program Logic

1. Validate Emirates ID using the regular expression ```/^784[-]*\d{4}[-]*\d{7}[-]*\d$/```
2. Use Luhn algorithm to calculate check digit and compare

## References

- https://u.ae/en/information-and-services/visa-and-emirates-id/emirates-id
- https://learn.microsoft.com/en-us/purview/sit-defn-uae-identity-card-number
- https://en.wikipedia.org/wiki/Luhn_algorithm
