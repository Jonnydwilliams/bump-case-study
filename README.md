# BUMP — Building meaningful connections from real-world encounters

**Independent product concept and working MVP · Product discovery, consumer onboarding, trust and community**

## The problem
People meet at events, through friends and in everyday life, but those encounters don't always become lasting connections. Existing networking products often rely on cold outreach or ongoing messaging.

**Product hypothesis:** A lightweight way to preserve real-world encounters and request introductions through people you actually know can make connecting feel more natural and trustworthy.

## Intended audience
People who attend creative, cultural and community events and want to remain connected or meet others through trusted relationships. Event organisers may also benefit if stronger connections encourage repeat attendance; that commercial hypothesis has not yet been validated.

## MVP approach
I chose a **mobile-first, QR-led flow** so people can initiate a connection while together in person, rather than remembering to find each other on another platform.

The current implementation documents:
- Temporary QR codes and scan links
- Guest participation and a path to later signup
- First-degree connections (people met in real life)
- Second-degree relationships and requests for trusted introductions
- A lightweight dashboard for connections and introduction requests

## Product decisions and trade-offs
| Decision | Reasoning / hypothesis |
|---|---|
| Start with people who meet in person | Anchors the network in real interactions rather than cold requests |
| Let guests participate | Reduce friction at the moment of meeting |
| Use temporary QR access | Make the exchange situational and intentional |
| Prioritise introductions over in-app chat | Test the core value of trusted connection before investing in messaging |
| Build mobile-first | Reflect the setting where the key interaction happens |
| Keep the first pilot narrow | Make it possible to observe usage and learn before expanding into event discovery or broader social features |

## What I'd measure in a pilot
These are **proposed metrics, not observed outcomes**:
1. **Activation:** percentage of QR scans that result in a completed connection
2. **Conversion:** percentage of guests who later claim/sign up for their connection
3. **Engagement:** number of eligible introduction requests initiated and completed
4. **Retention:** percentage of connected users who return after the event
5. **Quality:** qualitative feedback on trust, usefulness and whether meaningful contact happened offline

I'd pair funnel analysis with short interviews to understand which actions represent genuine value rather than superficial activity.

## My contribution
I shaped the product idea, scope, user journeys and MVP constraints, and used modern development tools and AI-assisted coding to turn those decisions into an application. The private codebase uses Next.js, TypeScript and Supabase.

## Status and next steps
**In development.** The repository documents an implemented QR-led flow and a branch prepared for preview deployment. A public launch, user adoption, retention or commercial results should not be inferred from this case study.

Next: test the QR connection flow with a small group in a suitable real-world setting; observe where people drop off; validate whether trusted introductions are appealing; revisit the event-organiser value proposition only when there is user evidence.

---
*This is a product case study rather than a public source-code repository. Screenshots and a demo link can be added after a safe preview is available.*
