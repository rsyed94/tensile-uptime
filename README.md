# tensile-uptime

Free uptime probe for Tensile production: every 5 minutes it checks /healthz and /readyz, and after two failed probes it opens an issue here that @-mentions the owner. Source of truth: `ops/uptime/` in the Tensile repo.
