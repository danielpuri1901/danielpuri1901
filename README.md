# Daniel Puri

I cofounded Routes AI, a route optimization platform for last mile logistics.
I led the agent platform architecture and worked with customers from demos through onboarding.
Now I build AI systems at ArcelorMittal and publish my own agent tools here.

[Email](mailto:danielpuri1901@gmail.com) · [LinkedIn](https://linkedin.com/in/danielpuri)

## Current work

AI engineering intern at ArcelorMittal, June 2026 to present.

I rebuilt LeadSense, a system that finds and qualifies sales leads, across five markets.
The rebuild produced eight times more leads over two months.

- I built a production evaluation harness with Strands Evals and Langfuse.
  Sales labels and scores are stored in Fabric SQL.
  Training examples stay separate from the held-out examples used to check each change.
  CI promotes changes only when they pass those checks.
- I replaced the scoring prompt with Jev, a decision model that returns typed, calibrated probabilities.
  The scoring path is 40 times cheaper and 20 times faster than the previous prompt.
  DSPy and GEPA tune its questions per market.
  A new market now needs one week of labeled data rather than two months.
- I replaced fixed research queries with a LangGraph research workflow.
  A planner creates topics for each country and a supervisor coordinates parallel research agents.
  Episodic memory improves queries across runs.
  Short-term memory reduced duplicate leads from 7.8% to 0% in the recorded evaluation.
- I am building a virtual machine per agent for long-running outreach across applications without reliable APIs.
  The work includes limited credentials and logged actions, with evaluation checks, drift detection, and Teams escalation.

I am co-writing an AWS blog post about the evaluation work.

## Public projects

| Project | What it does |
| --- | --- |
| [Twin Mind](https://github.com/danielpuri1901/twin-mind) | Uses private history to support daily briefs, meeting preparation, and Telegram conversations. |
| [AgentLab](https://github.com/danielpuri1901/agentlab) | Turns selected research papers into narrated videos, with preview checks before delivery. |
| [Erdős proof checker](https://github.com/danielpuri1901/erdos-lean-checker) | Rebuilds submitted Lean proofs and checks their statements outside the proof agent's repository. |
| [optimaze](https://github.com/danielpuri1901/optimaze-agent) | Tunes Gurobi solver parameters and records trials against a default baseline. Also on [PyPI](https://pypi.org/project/optimaze/). |
| [AIRLOCK](https://github.com/danielpuri1901/airlock) | Demonstrates offline payment approval on a phone, with a required second signature on Algorand TestNet. |
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

- Routes AI, February 2026 to May 2026.
  We had three paying enterprise design partners.
  I led the agent platform architecture and customer work; my cofounder led optimization.
  The platform served up to 2,400 parcels per day before we wound it down voluntarily.
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

Python and TypeScript.
LangGraph, AWS, PostgreSQL, and Docker.
Langfuse and Strands Evals for evaluation.
Gurobi for optimization.

BSc Business Administration, University of Amsterdam, 2026.
Minor in Entrepreneurship.
English and Spanish native; French proficient.

Open to Applied AI / Forward-Deployed / Founding Engineer roles in the US and EU.
