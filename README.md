# Ethan Vault

> Personal operating system and persistent knowledge base for Ethan and ATLAS.

This Vault is designed to preserve durable context, decisions, projects, relationships, and operating knowledge across AI sessions and tools.

ATLAS should treat this Vault as persistent organizational memory.

---

# Startup Protocol

At the beginning of a new working session, read these files first:

1. [[agent-persona]]
2. [[memory-summary]]
3. [[identity/founder-profile]]
4. [[identity/decision-style]]

Then read only the additional files relevant to the current task.

Do not load the entire Vault unless necessary.

---

# Core Files

## [[agent-persona]]

Defines:

- Who ATLAS is
- Role as CEO Chief of Staff
- Working relationship with Ethan
- Challenge behavior
- Communication style
- Core operating principles

Question answered:

> Who am I and how should I work with Ethan?

---

## [[memory-summary]]

Defines:

- Current priorities
- Important active situations
- Major working hypotheses
- Current unknowns
- Important operating decisions

Question answered:

> What matters right now?

This file should remain concise and current.

---

# Identity

Folder:

`identity/`

Contains durable information about Ethan.

## [[identity/founder-profile]]

Defines:

- Ethan's role
- Professional context
- Working preferences
- Expectations of ATLAS

Question answered:

> Who is the CEO I am supporting?

## [[identity/decision-style]]

Defines:

- How Ethan makes decisions
- Risk tolerance
- Challenge preferences
- Evidence standards
- Decision closure behavior

Question answered:

> How should I help Ethan make decisions?

---

# Context

Folder:

`context/`

Contains business and operating context.

## [[context/company-overview]]

Durable business context.

Includes:

- Business model
- Market
- Channels
- Product categories
- Commercial philosophy
- Long-term operating principles

Question answered:

> What business are we building?

## [[context/current-context]]

Current operating situation.

Includes:

- Current commercial stage
- Market signals
- Active strategic hypotheses
- Current priorities
- Important unknowns

Question answered:

> What is happening in the business right now?

Update this file when the operating situation materially changes.

---

# Memory

Folder:

`memory/`

Stores durable decisions and lessons that should survive changes in current context.

Use this folder for:

- Major strategic decisions
- Important methodology decisions
- Commercial decisions
- Lessons learned
- Significant changes in direction

Prefer one important decision or lesson per file.

Example:

`memory/2026-09-01-channel-pricing-decision.md`

Do not store routine conversation transcripts here.

---

# Projects

Folder:

`projects/`

Stores active work with a defined objective, progression, and eventual completion.

Examples:

- Partner pilot
- Channel expansion
- Product launch
- Research manuscript
- Experimental project

A project may contain:

- Objective
- Current status
- Decisions
- Next actions
- Risks
- Dependencies
- Results

When a project ends, preserve important lessons or decisions before archiving it.

---

# People

Folder:

`people/`

Stores durable context about important external or internal relationships.

Use for:

- Business partners
- Important customers
- Suppliers
- Advisors
- Collaborators
- Key professional contacts

A people file should capture information useful for future interaction, not irrelevant personal details.

Possible content:

- Role
- Organization
- Relationship context
- Important preferences
- Commercial history
- Commitments
- Open issues

---

# Operations

Folder:

`operations/`

Stores durable operating information that does not belong to a specific project.

Examples:

- Business processes
- Commercial structures
- Inventory systems
- Pricing architecture
- Administrative knowledge
- Recurring operational data

Do not use this folder as a miscellaneous dumping ground.

---

# SOP

Folder:

`sop/`

Stores repeatable procedures.

Use when a task is expected to occur repeatedly.

Examples:

- Partner evaluation process
- Meeting preparation
- Product launch checklist
- Research data verification
- Weekly business review
- Decision-record procedure

SOPs should be executable, not theoretical essays.

---

# Information Routing

When new information appears, classify it before storing it.

### If it changes who Ethan is or how he works:
→ `identity/`

### If it describes durable business reality:
→ `context/company-overview.md`

### If it describes the current business situation:
→ `context/current-context.md`

### If it is currently important across multiple activities:
→ `memory-summary.md`

### If it is a durable decision or lesson:
→ `memory/`

### If it belongs to a defined initiative:
→ `projects/`

### If it concerns an important relationship:
→ `people/`

### If it is recurring operational knowledge:
→ `operations/`

### If it is a repeatable procedure:
→ `sop/`

Do not duplicate the same detailed information across multiple files.

Use links instead.

---

# Reading Strategy

ATLAS should use progressive disclosure.

Default:

README
→ Agent Persona
→ Memory Summary
→ Relevant Context
→ Relevant Project / Person / Memory / SOP

Avoid reading unrelated material simply because it exists.

The objective is sufficient context, not maximum context.

---

# Writing Strategy

When modifying the Vault:

1. Determine whether the information is durable.
2. Identify the correct source-of-truth file.
3. Update existing information instead of creating unnecessary duplicates.
4. Preserve important decisions and their reasoning.
5. Remove or replace obsolete current-state information.
6. Keep root files concise.
7. Link related files where useful.

Do not store every conversation.

Store knowledge that is likely to matter again.

---

# Source of Truth Rules

When information conflicts:

1. Prefer direct evidence over assumptions.
2. Prefer more recently verified information.
3. Prefer the dedicated source-of-truth file over summaries.
4. Treat `memory-summary.md` as a summary, not the full historical record.
5. Never silently convert an estimate into a fact.

If uncertainty remains, surface it.

---

# Current Vault Structure

```text
ethan vault/
│
├── README.md
├── agent-persona.md
├── memory-summary.md
│
├── identity/
│   ├── founder-profile.md
│   └── decision-style.md
│
├── context/
│   ├── company-overview.md
│   └── current-context.md
│
├── memory/
├── operations/
├── people/
├── projects/
└── sop/