# Engineering Handover

## Project State
We are building out the `rangesensei_web` repository. We just executed a successful set of infrastructure and front-end milestones taking the static page into a live, interactive ecosystem.

**Critical URLs:**
- **Live Staging/Prod Host:** Vercel (Auto-deploying from `main` branch).
- **Domains:** `rangesensei.io` (Primary App), `rangesensei.com` (permanently redirecting to `.io`).
- **Waitlist Data Pipeline:** A Google Apps script currently handles raw GET requests carrying user email strings from the `index.html` form. The data pools into a Google sheet and sends a daily digest to `adaptivesensing@gmail.com`.

**Important Files:**
- `index.html`: Contains all primary UI and inline JavaScript (including the non-CORS fetch to Google Macros).
- `docs/environmental_config.md`: Holds organization and networking truths.
- `env.local`: Keep secrets here—never commit.

## Immediate Next Steps For Next Session
1. **Verification Phase:** Validate that the Spaceship DNS records fully propagated to Vercel and SSL certificates activated successfully.
2. **Action Items:** Review the `implementation_plan.md` to begin mapping out post-launch web analytics or the welcome-email logic on Google Apps Script. 
3. Resume development strictly following the project manifest conventions while utilizing standard JavaScript optimization.
