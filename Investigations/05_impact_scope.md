## Impact & Scope

The impact of this activity is assessed as high due to the presence of a root-level persistent execution mechanism on a Linux database server. The systemd timer enables repeated execution without user interaction, increasing the risk of sustained system compromise and unauthorized access to sensitive resources. At the time of investigation, the activity was confirmed on a single host; however, the automated nature of the persistence presents a risk of further expansion if additional payloads are introduced.
