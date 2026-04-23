# Veteran Connect / DVA Virtual Advocate project pack

## What this pack is
This pack consolidates the build history, completed work, current state, and remaining backlog across the Android app, backend services, website, shared Swift iOS foundation, MAUI migration, security and account planning, AI planning, and the newer Provider Services stream.

## Current confirmed state
Primary working repo path: `C:\dev\DVA-Virtual-Advocate`  
Source-of-truth branch: `main`  
Current web branch: `web/claim-starter-pack-steps`  
Current MAUI branch: `maui/phase0-shell`  
Public GitHub repo reserved for broader build/project management: `pezacide/Veteran-Connect`

Android remains the behavioural reference. The website claim starter pack flow is working. The shared Swift core exists and has been tested on Windows. The MAUI baseline was restored and is building again. Provider Services is the newest requested module stream.

## Date basis
Dates in this pack are thread-confirmed working dates or decision dates taken from the project conversations. They should be treated as project-log dates, not guaranteed Git commit timestamps.

## Timeline
| Date | Stream | Milestone | Status | Category | Notes |
|---|---|---|---|---|---|
| 2026-03-07 | Android / Docs | Install guide update requested | Completed | Support content | User requested Android install instructions be added to the guide. |
| 2026-03-12 | Android | Android release baseline confirmed | Completed | Implementation | Working Android app with app id com.dvavirtualadvocate.app and release baseline versionCode 8 / versionName 1.3.7 noted in conversation. |
| 2026-03-19 | Release / Beta | Beta communication assets prepared | Completed | Planning | One-pager, social post, invite copy, phase-based timeline and testing communications requested and drafted. |
| 2026-04-02 | Web | Website stream started | Completed | Planning | Decision to start building a website that can do the same core job as the apps. |
| 2026-04-02 | Web | Wireframe direction for website | Completed | Planning | Website wireframe work was initiated. |
| 2026-04-06 | AI / Web | Website AI integration assessed | Completed | Planning | AI feasibility for website discussed. |
| 2026-04-07 | Auth / Security | Cross-platform login and subscriptions architecture planned | Completed | Planning | User requested beginner-friendly step-by-step guidance using existing Google Cloud services where possible. |
| 2026-04-07 | Security / Privacy | Privacy and security design stream started | Completed | Planning | Security and privacy guidance merged with account management stream. |
| 2026-04-13 | Repo / Architecture | Source-of-truth repo and branch strategy confirmed | Completed | Decision | C:\dev\DVA-Virtual-Advocate on main confirmed as source of truth; website work on web/claim-starter-pack-steps; future iOS shell under ios. |
| 2026-04-13 | iOS / Shared Swift | Shared Swift core established and tested on Windows | Completed | Implementation | Reusable Swift domain models and business logic created; native iPhone shell not yet built. |
| 2026-04-13 | Android | Android app state recorded as behavioral reference for MAUI | Completed | Decision | Android app with Cloud Run-backed SoP lookup, claim starter pack generation, DOCX export and GCS upload treated as behavioral baseline. |
| 2026-04-13 | Branding | Project rename to Veteran Connect | Completed | Decision | Veteran Connect became the forward project/app name for the MAUI stream and broader platform. |
| 2026-04-13 | Architecture | Overview diagram and stack design documentation requested | Completed | Planning | Cross-platform stack documentation stream was initiated. |
| 2026-04-15 | AI / Docs | AI for documentation integration planned with Azure migration direction | Completed | Planning | Backend migration target shifted toward Azure for future AI/document workflows. |
| 2026-04-17 | MAUI | Dashboard rollback and known-good baseline restored | Completed | Stabilisation | Windows and Android builds succeeded after failed dashboard merge was fully rolled back. |
| 2026-04-17 | MAUI | Working CQRS slices confirmed in MAUI baseline | Completed | Implementation | Condition search, SoP detail loading, draft save/load/update/delete, and claim pack generation confirmed present. |
| 2026-04-20 | MAUI | Physicians Initial Liability form layout adjustment work | In Progress | Implementation | Responsive layout adjustment work underway in InitialLiabilityMedicalReportPage.xaml. |
| 2026-04-20 | MAUI | Login/dashboard navigation crash debugging and styling preservation | In Progress | Stabilisation | Need to keep new brand styling while fixing page navigation / shell routing issues. |
| 2026-04-23 | Provider Services | Provider Services module foundation requested | Open | Implementation | Need minimum structural foundation so Provider Services can exist as a first-class module inside Veteran Connect. |
| 2026-04-23 | GitHub Project | Project import script hit duplicate-content error | Open | Project setup | PowerShell GitHub project import partially created issues but failed adding some content already in project. |

## Suggested GitHub Project fields
| Field | Suggested values |
|---|---|
| Status | Done / In Progress / Open / Blocked |
| Stream | Android / Web / MAUI / iOS / Backend / Auth / Security / AI / Provider Services / Docs / Ops |
| Platform | Android / Web / MAUI / iOS / Shared Swift / Backend / Cross-platform / GitHub |
| Priority | Critical / High / Medium / Low |
| Type | Epic / Task / Bug / Historical record / Planning |
| Confirmed Date | Conversation-confirmed date for the item or decision |

## Suggested first project views
| View | Purpose |
|---|---|
| Roadmap | Whole-program view across all streams |
| Current Build Focus | Only active Critical and High work |
| MAUI Recovery + Build | Shell, dashboards, forms, regression and Provider Services work |
| Web Claim Pack | Portal-alignment and export work |
| Security + Auth | Login, subscriptions, privacy and security implementation |
| Historical Done | Completed work preserved as permanent project history |
