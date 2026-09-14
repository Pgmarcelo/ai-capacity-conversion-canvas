# Measurement Plan

This template separates four questions that are often combined in an AI business case:

1. Does the capability work?
2. Do the intended users adopt it?
3. Does the workflow improve?
4. Does the organization convert that improvement into a business result?

## 1. Define the unit of work

Choose a unit that can be counted consistently, such as a resolved case, processed invoice, completed report, qualified lead, fulfilled order, or closed incident.

**Unit of work:**  
**Start event:**  
**Completion event:**  
**Excluded cases:**  

## 2. Establish the baseline

Measure the original workflow before deployment. Record:

- observation period and dates;
- eligible volume;
- sample size;
- user groups;
- handling time and end-to-end cycle time;
- completion, rework, exception, and escalation rates;
- quality or accuracy;
- customer or employee experience measures; and
- relevant seasonal or operational changes.

Use medians and percentiles when averages could hide large variation.

## 3. Define the measurement layers

### Technical performance

Can the capability complete its assigned step reliably?

| Metric | Definition | Target |
|---|---|---:|
| Successful execution rate | Completed technical runs / attempted runs | |
| Response or execution time | Time required by the AI component | |
| Tool or integration failure rate | Failed external actions / attempted actions | |
| Evaluation score | Task-specific quality measure | |

### Adoption

Are the intended users incorporating the capability into real work?

| Metric | Definition | Target |
|---|---|---:|
| Eligible-user adoption | Active intended users / eligible users | |
| Workflow coverage | AI-assisted units / eligible units | |
| Repeat usage | Users returning during the measurement period | |
| Override or abandonment rate | Started uses that users reject or abandon | |

### Operational improvement

Did the workflow perform better?

| Metric | Definition | Target |
|---|---|---:|
| Handling time | Human effort per completed unit | |
| Cycle time | Elapsed time from trigger to completion | |
| First-pass completion | Units completed without rework | |
| Rework rate | Units requiring correction / completed units | |
| Escalation rate | Units sent to a higher-cost path / eligible units | |
| Throughput | Completed units per period | |
| Backlog | Eligible work not completed within the period | |

### Business result

Was the recovered capacity converted into an observable outcome?

| Capacity destination | Example evidence |
|---|---|
| Additional throughput | More completed work with acceptable quality |
| Faster service | Reduced wait time or service-level breaches |
| Higher quality | Fewer errors, complaints, returns, or corrections |
| More complex work | More expert cases completed or fewer avoidable escalations |
| Revenue activity | More qualified conversations, proposals, or timely follow-ups |
| Deferred work completed | A named backlog or improvement initiative is completed |

## 4. Estimate usable capacity

An illustrative calculation is:

```text
Gross usable hours =
eligible volume
× workflow adoption rate
× successful completion rate
× net human minutes saved per completed unit
÷ 60
```

Use observed values after deployment. Do not apply a financial value automatically.

Subtract new effort created by the solution, including:

- reviewing outputs;
- correcting errors;
- managing exceptions;
- maintaining knowledge and prompts;
- monitoring and evaluating performance; and
- operating integrations and controls.

The remaining time is still potential capacity until its destination produces measurable evidence.

## 5. Design the comparison

Use the strongest practical method available:

1. **Concurrent comparison:** similar users or work are measured with and without the capability during the same period.
2. **Staged rollout:** later groups provide a temporary comparison for earlier groups.
3. **Before and after:** use the same measures across representative pre-deployment and post-deployment periods.

Document changes in demand, staffing, policy, seasonality, or process that could influence the result.

## 6. Set guardrails

Define unacceptable outcomes before launch.

| Guardrail | Maximum or minimum allowed |
|---|---:|
| Error or rework rate | |
| Escalation rate | |
| Security or privacy incidents | |
| Unsupported consequential actions | |
| Customer complaints | |
| Unplanned operating cost | |

A productivity gain does not compensate for crossing a mandatory safety, security, legal, or quality boundary.

## 7. Review cadence

- **During pilot:** review failures, user feedback, and guardrails weekly.
- **At the pilot decision:** compare results with the baseline and agreed thresholds.
- **After scaling:** review operational performance, unit economics, and control effectiveness monthly or at a cadence appropriate to the risk.

## 8. Decision record

| Question | Evidence | Decision |
|---|---|---|
| Does it work reliably? | | |
| Do intended users adopt it? | | |
| Did the workflow improve? | | |
| Was capacity converted into value? | | |
| Are risks and costs acceptable? | | |
| Scale, redesign, or stop? | | |
