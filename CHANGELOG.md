- Adds Cloud Storage for Firebase emulator
- Allows Hosting deploys with no `public` directory when dynamic rewrites or redirects are present. (#3349)
- Fixes error where Hosting gets in an undeployable state due to the hash cache having incorrect entries.
- Improves error handling for the throttler queue, to better diagnose Hosting deploys that fail during the file upload step.
