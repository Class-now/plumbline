# Plumbline privacy policy

Last updated: 9 November 2026

Plumbline ("the app") is a Forge app that runs on Atlassian's platform ("Runs on Atlassian"). This policy explains what the app reads and stores.

## What the app reads

When a person uses the app, it reads, as that person and with their permissions:

- Jira work items in the project (summary, description, links, and the app's own issue properties).
- Confluence pages the project's decisions point to, and the Teamwork Graph links between Confluence pages and Jira work.

The app sees only what the person using it can already see.

## What the app stores

The app stores, in Forge storage inside Atlassian:

- The project's decision records (decision text, who decided it as a name or role, date, status, evidence links).
- Which work items were already told about a changed decision, so nobody is told twice.
- A short-lived copy of the graph links it read, used when the graph cannot be read.

The app does not store Atlassian account passwords, emails or payment data.

## What the app sends

The app sends no data outside Atlassian. It has no external egress. When a person presses "Tell the selected work", it posts a comment on the chosen Jira work items, as that person.

## AI features

The Rovo agent and the MCP tools are read-only. The matching of questions to decisions is plain code, not a language model. Rovo's own processing is covered by Atlassian's terms.

## Deleting data

Uninstalling the app removes its Forge storage, under Atlassian's data retention rules for Forge apps. Comments the app posted stay in Jira until someone deletes them.

## Contact

Questions about this policy: open an issue at https://github.com/Class-now/plumbline/issues
