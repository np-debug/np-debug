# Nathaniel Perez

Forward-deployed engineer in Charlotte, NC. I embed with a business, find the workflow that actually runs it, and ship the AI system that changes it. Then I stay until people use it. I build with Claude Code every day. English / Español.

## Running in production

**Field-service migration for a trades company** · Jul 2026 – now
Moved a $3M, 26-person landscaping company, where I'd once worked on a crew, from paper route sheets and a binder of hand-typed invoices onto field-service software. The system now bills **$160–180K every month, recurring** ($339K in its first eight weeks, and growing with each monthly run). Python pipelines parsed 30,728 QuickBooks invoice rows and cross-checked six datasets. Where the software had no API, I automated it through the browser with idempotent Claude-driven runners that re-read every save.

**Agent platform for a consulting practice** · Apr 2026 – now
Claude on Supabase/Postgres and Netlify Functions, used daily by a non-technical team. One trace ID follows every model call to the database write it caused. Agents auto-apply changes at ≥0.85 confidence and hand off to a person below it. Daily spend caps, a job queue with a dead-letter queue, and one kill switch for all model traffic.

## Open source

**[healthcare-agent-governance-framework](https://github.com/np-debug/healthcare-agent-governance-framework)**: a spec, JSON schemas, six policy templates, and a Python eval harness for agent identity, scope, delegation, and revocation. Distilled from the platform above.

## Contact

[LinkedIn](https://linkedin.com/in/nathaniel-perez-252a30373) · np@ruthsconsulting.com

Client code stays private. I'm glad to walk through any of it live.
