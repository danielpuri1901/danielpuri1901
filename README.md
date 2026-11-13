# Daniel Puri

Founder and AI engineer. I have founded four companies, each with paying customers.
I cofounded Routes AI, a route optimization platform for last mile logistics, where I closed our three paying enterprise design partners in two weeks.
Now I build AI systems at ArcelorMittal and publish my own agent tools here.
Relocating to New York. US and EU national.

[Website](https://danielpuri.com) · [Email](mailto:danielpuri1901@gmail.com) · [LinkedIn](https://linkedin.com/in/danielpuri)

## Current work

AI engineering intern at ArcelorMittal, June 2026 to present.

I am the only engineer on LeadSense, a go-to-market agent system for sheet piling.
In two months I rebuilt it, took it to five markets, and got eight times more leads.

- I built a self-improving evaluation harness with Strands Evals and Langfuse.
  Leads labeled by the sales team form separate training and holdout splits, stored in Fabric SQL.
  CI ships a change only if it wins on the untouched holdout.
  Precision rose from 60% to 92%.
  I am co-writing an AWS blog post about it.
- I replaced the scoring prompt with Jev, a decision model that returns typed, calibrated probabilities.
  The scoring path is 40 times cheaper and 20 times faster than the previous prompt.
  DSPy and GEPA tune its questions per market.
  A new market now needs two weeks of labeled data rather than two months.
- I replaced fixed research queries with a LangGraph deep-research workflow.
  A planner creates topics for each country and a supervisor coordinates parallel research agents.
  Episodic memory improves queries across runs and cut duplicate leads from 16.8% to 0%.
- I moved four legacy workflows, built on Excel, SharePoint, and knowledge in people's heads, into full-stack apps with agents.
  One agent took over work that would otherwise have gone to outside contractors.
- I am building a virtual machine per agent, so computer-use agents can run outreach and inbound across legacy systems without reliable APIs.
  The work includes scoped credentials and logged actions, with evaluation checks, drift detection, and Teams escalation.


## Public projects

| Project | What it does |
| --- | --- |
| [Twin Mind](https://github.com/danielpuri1901/twin-mind) | Uses private history to support daily briefs, meeting preparation, and Telegram conversations. |
| [AgentLab](https://github.com/danielpuri1901/agentlab) | Turns selected research papers into narrated videos, with preview checks before delivery. |
| [Erdős proof checker](https://github.com/danielpuri1901/erdos-lean-checker) | Rebuilds submitted Lean proofs and checks their statements outside the proof agent's repository. |
| [optimaze](https://github.com/danielpuri1901/optimaze-agent) | An agent that tunes Gurobi solver parameters. On MIPLIB it solves 20 to 50% faster than the defaults, up to 85% at peak. Also on [PyPI](https://pypi.org/project/optimaze/). |
| [AIRLOCK](https://github.com/danielpuri1901/airlock) | Offline second factor for AI agent payments. A quantized classifier on the phone checks for prompt injection and holds one key of a 2-of-2 Algorand multisig, so a hijacked agent cannot pay. Demoed on TestNet. |
| [OpenApply](https://github.com/danielpuri1901/openapply) | Finds matching jobs and prepares forms in Chrome. Human review and submission are the default. |
| [app-access-cli](https://github.com/danielpuri1901/app-access-cli) | Gives agents bounded access to application data, with typed responses and source information. |

## Recent private experiments

Black Hole Flight Lab compares learned flight plans with checks based on relativistic equations.
It includes an interactive 3D cockpit and a separate experiment with exact rational escape certificates.
The numerical flight checker is not a formal safety proof.

My proof-formalization harness translates published human proofs into Lean.
The public checker verifies submissions against frozen statements.
The experiment concerns known results, not claims of new mathematical discoveries.

## Earlier work

- Routes AI, February 2026 to May 2026, through the Xlerate accelerator.
  I ran workshops, POCs, and onboarding for our three paying enterprise design partners.
  We connected each customer's OMS, TMS, Excel sheets, and dispatcher knowledge into one system with agents on top.
  I led architecture on the four-agent loop; my cofounder led optimization.
  We cut the lead customer's delivery cost by 15% and ran up to 2,400 parcels and 169 pick-up points a day.
  We wound it down voluntarily.
- Blaire, September 2025 to February 2026.
  I cofounded a clothing marketplace and built its payment and virtual try-on flows.
  It facilitated 300 transactions with no paid acquisition.
- [Readable](https://github.com/ReadableLabs/readable-vscode), built with my twin brother at Puri Chapman Software.
  I owned logging and observability for a VS Code extension used by 26,000+ developers.
- [a tiny gesture](https://github.com/danielpuri1901/tinygesture), our Odyssey Hackathon team project.
  I drove 51 pre-sales before we built and shipped it in 29 hours.

## More projects

- [Amsterdam housing predictor](https://github.com/danielpuri1901/amsterdam-housing-predictor), an educational regression project using generated sample data.
- [Park and bike hub placement](https://github.com/danielpuri1901/mobian-optimization), a mixed-integer optimization model.
- [Network routing demo](https://github.com/danielpuri1901/uber-network-routing-demo), a vehicle-routing test model.
- [Timor-Leste healthcare placement](https://github.com/danielpuri1901/timor-leste-healthcare), a model for placing hospitals under coverage and budget constraints.

Earlier private work also includes a face-analysis prototype.

## Tools I use

Python, TypeScript, SQL, and C.
LangGraph, agent SDKs from OpenAI, Anthropic, and Strands, MCP, and DSPy with GEPA.
AWS, PostgreSQL, and Docker.
Langfuse, Strands Evals, Braintrust, LangSmith, and Arize for evaluation.
Gurobi for optimization.

BSc Business Administration, University of Amsterdam, 2026.
GPA 4.0/4.0, the US equivalent of 8/10 on the Dutch scale.
Minor in Entrepreneurship.
English and Spanish native; French proficient.

Open to Applied AI / Forward-Deployed / Founding Engineer roles in the US and EU.
