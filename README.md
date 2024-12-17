## Goals

1. Democratize data self service within organization. Make it open to wide audience.
2. Increase awareness and data leteracy within organization. Teach people what data and data content is available in the organization.
3. Transform data analysts routine from answering adhoc questions to manager of metadata and meanings

## The system

We are building an application which is going to have number of modules on boards. In a nutshell we make Assistante powered with LLMs and company context.

### Module: Context manager

The module to collect, store and made the full company context related to data available to be used while using LLMs.

Source for data context we envision:

1. Data models (dbt, ORM schemas etc, snow)
2. Communication tools  (Slack, Teams conversations)
3. BI tools (Metabase database)
4. Data catalogs (Datahub, Atlan etc)

### Module: LLM manager

The module to store and setup communication with different LLMs (including all the available tools)

1. API keys setups
2. Optimizers
3. Tools setup (create SQL, query DB, visualize)
4. System promts

### Module: Admin console

incl (Context manager, LLM manager). UI to setup all above

### Module: User experience

aka Conversation UI. The place were interaction between user and LLM happens.

1. User inputs text, gets replies
2. BYOConverstaion module, connect with slack, teams, anyother tool

## Use cases

Regular user interaction:
1. ask data related questions
2. get answers

Admin user interaction:
1. setup context sources
2. select tools
3. connect messengers







