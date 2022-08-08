# WEED - What EEs Different  
![This is an image](docs/WEED.svg)

Have you ever pushed to production only to find out that the permissions between staging and production environments are out of sync? resulting in access errors in a live environment? Well we have, we got frustrated, learned  and created WEED!!!


## What is WEED?

WEED is a CLI tool that assures permissions are synced between development and production environmentsץ
WEED discovers differences in permissions between staging and production environments.
WEED maps permissions on both environments checking for discrepancies that might cause access errors in production  

### Components 

***WEED CLI***  - 
Discovers Diff in permissions between environments to avoid those pesky 403 erors in production.

***IMenforcer*** – 
Acts as a validation layer, assuring permissions discrepancies that were discovered by WEED are resolved before pushing to production
 

   

# Prerequisites

 - AWS Account 
 - Hands (minimum of 1) 
 - Role in AWS?

## CLI Installation 

