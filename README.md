# Generate Storage Report via Self Service

Can be used in an Self Service policy for an end-user to show his 5 biggest directores when bootdisk has less then 15% storage left.

Usage;
- Create smartgroup Storage: Boot volume more than 85% used
- Create Self Service policy scoped to smartgroup above and add the script with the before option
- In the same policy flush the user caches.
