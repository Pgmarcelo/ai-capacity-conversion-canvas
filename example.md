# Fictional Example: Customer-Service Knowledge Assistant

This example is entirely fictional. The organization, figures, workflow, and results are illustrative and do not describe an actual customer or implementation.

## Scenario

Northstar Services receives customer questions about contracts, billing rules, and service eligibility. Agents search several approved knowledge sources, draft a response, and escalate cases when the answer remains unclear.

The company is considering an AI knowledge assistant that retrieves approved information, cites its sources, and drafts a response. A service agent reviews every response before it is sent.

## 1. Workflow and ownership

| Field | Example |
|---|---|
| Workflow | Resolve policy and billing questions |
| Unit of work | One eligible customer case |
| Business owner | Vice President, Customer Service |
| Technical owner | Director, Business Applications |
| Control owners | Security, Privacy, Legal, and Service Quality |
| AI role | Retrieve approved content and draft a cited response |
| Human role | Verify the answer, edit when required, and send or escalate |

## 2. Baseline

The team measures four representative weeks before the pilot.

| Measure | Fictional baseline |
|---|---:|
| Eligible cases per month | 8,000 |
| Median human handling time | 12 minutes |
| Median end-to-end resolution time | 18 hours |
| First-pass completion rate | 76% |
| Rework rate | 8% |
| Escalation rate | 15% |
| Cases breaching the service target | 11% |

## 3. Value hypothesis

> If the assistant retrieves approved policy information and drafts cited responses, agents should reduce median handling time from 12 to 7 minutes and resolve more cases on the first pass, while keeping rework at or below 8% and preventing unsupported responses from reaching customers.

## 4. Capacity destination

The business owner does not treat saved minutes as an immediate labour reduction.

The primary destination is to reduce the existing backlog and customer wait time. A secondary goal is to give experienced agents more time for complex cases.

Evidence of conversion will include:

- lower end-to-end resolution time;
- fewer cases breaching the service target;
- a smaller backlog;
- fewer avoidable escalations; and
- more complex cases completed by experienced agents.

## 5. Pilot

| Field | Fictional design |
|---|---|
| Participants | 20 agents across two teams |
| Duration | Six weeks |
| Comparison | Similar eligible cases handled by 20 agents using the original workflow |
| Minimum sample | 1,000 eligible cases in each group |
| Review | Weekly operational and quality review |
| Human approval | Required before every customer response |
| Stop condition | Any confirmed disclosure of prohibited information or unsupported consequential advice |

## 6. Fictional pilot results

| Measure | Baseline | Pilot | Interpretation |
|---|---:|---:|---|
| Workflow coverage | 0% | 82% | Most eligible cases used the assistant |
| Successful assisted completion | N/A | 91% | Some uses still required the original path |
| Median handling time | 12 min | 7.5 min | Human effort fell, but missed the 7-minute target |
| Median resolution time | 18 hours | 10 hours | Customer waiting improved |
| First-pass completion | 76% | 85% | Fewer cases required another interaction |
| Rework rate | 8% | 7% | Quality stayed within the boundary |
| Escalation rate | 15% | 10% | More cases stayed with frontline agents |
| Service-target breaches | 11% | 6% | Capacity reached the intended operational result |
| Confirmed prohibited disclosures | 0 | 0 | Mandatory boundary maintained |

## 7. Capacity estimate

Using observed pilot values:

```text
8,000 eligible cases per month
× 82% workflow coverage
× 91% successful assisted completion
× 4.5 net human minutes saved
÷ 60
= approximately 448 gross usable hours per month
```

This figure is not reported as a financial saving. Review effort, maintenance, monitoring, training, and exception handling must still be deducted.

The business owner looks for evidence that the remaining capacity reduced backlog and service-target breaches. Those operational measures determine whether the time created business value.

## 8. Decision

**Decision: redesign and expand gradually.**

The pilot improved cycle time, first-pass completion, escalation, and service-target performance without increasing rework. It did not meet the handling-time target, and the 9% unsuccessful assisted-completion rate requires analysis.

Before expanding, the team will:

1. examine unsuccessful and abandoned uses;
2. improve gaps in the approved knowledge sources;
3. test whether newer agents and experienced agents need different workflows;
4. estimate ongoing evaluation and maintenance effort; and
5. repeat the quality review with a larger and more varied case sample.

The decision is based on the complete workflow result, not the headline number of hours saved.
