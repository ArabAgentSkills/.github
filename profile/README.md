

       ###    ####  #####  #   #  #####
      #   #  #      #      ##  #    #
      #####  #  ##  ####   # # #    #
      #   #  #   #  #      #  ##    #
      #   #   ####  #####  #   #    #

       ####  #   #  #####  #       #        ####
      #      #  #     #    #       #       #
       ###   ###      #    #       #        ###
          #  #  #     #    #       #           #
      ####   #   #  #####  #####   #####  ####`

**Agent-ready skills for Arab and MENA APIs.**

Arab Agent Skills is an open-source ecosystem for giving AI coding agents the regional API knowledge they usually miss: local payment gateways, government rails, logistics APIs, SMS and WhatsApp providers, e-invoicing flows, open banking references, identity APIs, commerce platforms, HR systems, Arabic NLP, and open data.

## Start Here

| Repo | Purpose |
| --- | --- |
| [Skills](https://github.com/ArabAgentSkills/Skills) | Public install repo for generated agent skills, vendor files, eval prompts, and source-backed references. |
| [Arab Payments Skill Atlas](https://github.com/ArabAgentSkills/arab-payments-skill-atlas) | The original payments skill by Mohamed Waleed that sparked the broader project. |

## Install

`ash
npx skills add ArabAgentSkills/skills
`

## Why This Exists

General-purpose agents often know global APIs better than Arab and MENA APIs. This organization exists to maintain practical, source-backed skills that help agents integrate regional systems without inventing endpoints, credentials, compliance claims, or webhook behavior.

## Origin

Mohamed Waleed built [Arab Payments Skill Atlas](https://github.com/ArabAgentSkills/arab-payments-skill-atlas) while working on a project and using agents for regional payment API work. He showed it to Fady Azzouny, and the idea expanded: why not build skills for Arab agents across more categories?

Fady Azzouny and Mohamed Waleed built Arab Agent Skills from that starting point.

## What We Maintain

- Payments and BNPL
- Logistics and delivery APIs
- Communications: SMS, WhatsApp, voice
- E-invoicing and tax rails
- Open banking and finance APIs
- Identity and government APIs
- Commerce, POS, and accounting platforms
- HR and payroll systems
- Arabic NLP and language tooling
- Arab open data portals

## Principles

- Source every vendor claim.
- Prefer official docs, developer portals, OpenAPI specs, Postman collections, and official SDK repos.
- Mark unknowns honestly.
- Keep SKILL.md files short and procedural.
- Keep high-risk workflows safe: payments, refunds, payouts, identity, tax, and open banking need explicit approval and sandbox/production separation.
- Make generated updates reviewable.

## Contribute

The best contribution is a better source: official docs, API references, SDK repos, OpenAPI files, Postman collections, or a clear docs-drift report.

Open a vendor request or docs update in [ArabAgentSkills/Skills](https://github.com/ArabAgentSkills/Skills/issues).
