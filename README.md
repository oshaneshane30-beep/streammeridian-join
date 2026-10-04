# Meridian Join Continuity Site

This repository hosts Meridian's low-dependency early-signup and continuity entry point.

## Purpose
- stable QR/link destination for join.streammeridian.com
- - no-payment service-readiness signup
  - - referral-code preservation
    - - fallback path when the full Meridian account runtime is unavailable
      - - fail-closed browser-player shell while provider support is being qualified
       
        - ## Security boundaries
        - - no Eagle/provider administrator secrets
          - - no customer passwords, OTPs, card data or banking credentials
            - - no live provider credentials in URLs or client-side JavaScript
              - - browser playback remains fail-closed until Meridian has a secure HTTPS playback-session backend and provider/content permission
               
                - ## Operational URLs
                - - primary: https://join.streammeridian.com/
                  - - GitHub Pages fallback: https://oshaneshane30-beep.github.io/streammeridian-join/
                    - - readiness form: https://form.jotform.com/262766730209057
                     
                      - The customer-facing runtime can change without changing the stable Meridian entry point.
                      - 
