# Proposed Rules of Engagement (Not Approved)

Status: draft derived from the supplied project scope. It is not an authorization to test any deployed or third-party system. The user has not supplied a named target or written owner approval; therefore campaign execution is not authorized and remains not started.

## Safe default scope

Until the system owner approves a specific environment in writing, activity is limited to planning and a locally run synthetic/mock assistant that has no network access, real user data, credentials, production integrations, or external tools. Use only benign synthetic prompts and fictitious data. Do not send requests to an unnamed target, public service, production system, or any third-party endpoint.

If an owner later authorizes a staging target, record the exact hostname/application, environment and model/persona identifiers, test account, authorized dates, allowed categories, prohibited actions, request/rate limits, data rules, contacts, and stop conditions before testing. Obtain written approval from the system owner and safety contact. A general repository permission or requester assertion is not a substitute.

## Permitted local simulation categories

The mock harness may exercise high-level behaviors using harmless synthetic content: instruction-priority handling, treatment of quoted/untrusted text as data, roleplay instruction boundaries, clearly simulated tool-result text, multi-turn context consistency, and appropriate refusal or safe redirection. These are evaluation categories, not attack payloads or evidence about a deployed model.

## Prohibited activity

No production or public-target testing; no endpoint discovery or scanning; no credential or secret collection; no real personal or confidential data; no actual tool invocation or external side effects; no persistence, availability-impacting load, or attempts to evade monitoring; no testing outside approved accounts, dates, personas, or categories. Do not place operational attack instructions or sensitive raw transcripts in this public repository.

## Stop and escalation conditions

Stop immediately if a test reaches a non-approved system, exposes real sensitive data, causes an external action, risks service disruption, exceeds the approved rate, or produces an unexpected harmful outcome. Preserve only the minimum evidence needed, redact identifiers and secrets, notify the named owner through the approved channel, and do not continue until written clearance is received.

## Evidence and reporting rules

For each approved run, record timestamp and timezone, environment/version, case identifier, approved category, safe reproduction reference, observed result, expected criterion, evidence location, reviewer, limitations, and approval status. Keep raw evidence in an owner-approved restricted location. Publish only sanitized summaries. Classify a bypass as confirmed only when a pre-agreed criterion is demonstrably violated and the authorized reviewer confirms the evidence. Propose mitigations only for confirmed findings and retest only within the approved scope.

## Approval record (must be completed by system owner before staging tests)

- Owner and safety approver: pending
- Named staging target and version: pending
- Approved dates/time window: pending
- Allowed personas/categories: pending
- Prohibited actions and data boundary: pending
- Rate/request limits: pending
- Stop conditions and escalation contact: pending
- Written approval reference: pending

Until the fields above are approved, status remains preparation only; no live tests may be performed under this draft.
