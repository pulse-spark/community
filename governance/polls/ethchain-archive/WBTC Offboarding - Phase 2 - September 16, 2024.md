---
title: Offboarding Parameters for WBTC Collateral Types - Phase 2 - September 16, 2024
summary: Signal your support or opposition to the WBTC-A, WBTC-B, and WBTC-C offboarding parameter changes included herein.
discussion_link: https://forum.makerdao.com/t/wbtc-changes-and-risk-mitigation-10-august-2024/24844/26
parameters:
    input_format: single-choice
    victory_conditions:
        - { type : plurality }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-09-16T16:00:00
end_date: 2024-09-19T16:00:00
---
# Poll: Offboarding Parameters for WBTC Collateral Types - Phase 2 - September 16, 2024

The Governance Facilitators have placed a Governance Poll into the voting system on behalf of the Ecosystem team. This Governance [Poll](https://sky-atlas.powerhouse.io/#A.1.9.1_Operational_Weekly_Cycle-b189fa17-57a9-4d4e-9780-0ce4efd94211|0db30308) will be active for three days beginning on Monday, September 16 at 16:00 UTC.

**This is a binary vote.**

- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community can vote in this poll to express support or opposition to the WBTC collateral types offboarding parameters described below.

The WBTC collateral types offboarding will take place progressively over the course of several Executive Votes. The tentative starting date for the Executive Vote corresponding to this Governance Poll can be found below under _Outcomes_.

### Legacy Vaults

- Set [Linear Interpolation (LERP)](https://manual.makerdao.com/module-index/module-lerp) for [Liquidation Ratios](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-ratio):
  - Increase WBTC-A LERP from 150% to **500% over 30 days**.
  - Increase WBTC-B LERP from 150% to **500% over 30 days**.
  - Increase WBTC-C LERP from 170% to **500% over 30 days**.
- Reduce [Local Liquidation Limit (`ilk.hole`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-local-liquidation-limit) parameters:
  - Reduce WBTC-A Local Liquidation Limit from 10 million DAI to **3 million DAI**.
  - Reduce WBTC-B Local Liquidation Limit from 5 million DAI to **3 million DAI**.
  - Reduce WBTC-C Local Liquidation Limit from 10 million DAI to **3 million DAI**.

### SparkLend

- Reduce [Liquidation Threshold](https://docs.aave.com/risk/asset-risk/risk-parameters#liquidation-threshold) from 70% to **65%**
- Update [Cap Automator](https://sky-atlas.powerhouse.io/#A.3.8.1.5.4_Cap_Automators-f9f321a3-b09d-453b-8726-d20f059faa1c|57eaf45219be6088) parameters:
  - Reduce Supply Cap `gap` from 200 WBTC to **100 WBTC**.
  - Reduce Supply Cap `max` from 5,000 WBTC to **3,500 WBTC**.
- Update [Interest Rate Model (IRM)](https://sky-atlas.powerhouse.io/#A.3.8.1.5.1.3_Interest_Rate_Model_Definition-83e3f4f2-5e8e-4383-95e5-3af1bfb19210|57eaf45219be608847d6) parameters:
  - Increase base rate from 0% to **5%**.
  - Increase slope 1 from 2% to **20%**.


For more details on the Cap Automator parameters, please visit this [forum post](https://forum.makerdao.com/t/feb-22-2024-proposed-changes-to-sparklend-for-upcoming-spell/23739).

Please review the discussion [thread](https://forum.makerdao.com/t/wbtc-changes-and-risk-mitigation-10-august-2024/24844/26) to help inform your position before voting.

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option then the following actions will be taken:**

- This change will be included in an upcoming Executive Vote with tentative starting date October 17, 2024.
- It is expected that this Executive Vote will take place within 30 days of this poll passing, absent external factors.
- If the Executive Vote passes, then these changes will become active in the Sky Protocol after the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay) has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option then no further action will be taken at this time.**

---

## Resources

If you are new to voting in the Sky Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [Sky Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
