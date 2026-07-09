# Appendix A: Survey of Federal and State Household-Technology Incentives

This folder holds the Appendix A supplementary data for the accompanying manuscript. See the repository-root `README.md` for the full paper citation and `CITATION.cff` for machine-readable citation metadata.

The material documents the U.S. federal and state incentive programs that support household adoption of durable technologies and codes each program against the four structural features of the forward-looking durable-goods adoption model estimated in the paper.

## Files

`Household_Incentive_Survey.pdf` is the narrative appendix. It states the scope and method, defines the four-feature coding scheme, summarizes the federal layer after Public Law 119-21, describes the state layer, and reports the generalizability pattern across technologies. It contains two tables: principal federal incentives (Table 1) and feature coding by technology category (Table 2).

`Household_Incentive_Survey_Matrix.xlsx` is the machine-readable matrix with three sheets:

- `Read me`: the coding scheme and coverage notes.
- `All programs`: the full program-level matrix, one program per row.
- `Summary`: counts by technology, mechanism, program status, and feature.

## Coverage

The survey catalogues 221 programs: 16 federal programs and 205 state and major-utility programs across all fifty states. Program identification draws on the Database of State Incentives for Renewables and Efficiency (DSIRE), administering-agency program pages, and U.S. Department of Energy and Internal Revenue Service guidance current to June 2026. State coverage captures each jurisdiction's flagship statewide and large-utility programs by technology category and represents each state's regime at that level. It does not enumerate every municipal or cooperative-utility line item.

## Column definitions (sheet: All programs)

| Column | Definition |
|---|---|
| Jurisdiction | Federal or State. |
| State | Two-letter postal code (US for federal entries). |
| Program | Program or instrument name. |
| Administrator | Agency or utility that administers the program. |
| Technology | Eligible technology or technologies. |
| Mechanism | Incentive instrument: tax credit, rebate, net metering, performance payment, grant, loan, tax exemption, or bill subsidy. |
| Amount / rate | Dollar amount, percentage, or per-unit rate, as published. |
| Eligibility | Eligibility conditions such as income limits, customer class, or geography. |
| Status (June 2026) | Program status as of June 2026: active, terminated, sunsetting, or waitlisted. |
| NPV durable good | Feature 1 code: Y, Partial, or No. |
| Time-varying path | Feature 2 code: Y, Partial, or No. |
| Visibility / peer | Feature 3 code: Y, Partial, or No. |
| Forward-looking timing | Feature 4 code: Y, Partial, or No. |
| Source URL | Hyperlink to the authoritative source. The visible cell text reads "link"; the URL is the cell's hyperlink target. |

## Coding scheme

Each program is coded on four structural features. Codes are `Y` (feature present), `Partial` (present but attenuated), and `No` (absent). The NPV and visibility codes are assigned by technology; the time-path and timing codes follow from the incentive mechanism and the program's current status. These codes are analyst codings that support qualitative pattern-matching. Program administrators do not assign them.

1. NPV durable good: the incentive targets a durable asset whose adoption rests on the net present value of a future benefit stream weighed against an upfront cost.
2. Time-varying incentive path: the incentive amount changes over time through a scheduled step-down, a statutory sunset, or budget-driven exhaustion.
3. Visibility and peer effects: the adopted technology is observable to neighbors, generating the channel through which adoption propagates.
4. Forward-looking timing: the incentive creates an intertemporal reason to time adoption, through announced deadlines, scheduled declines, or first-come budget constraints.

## Caveats

Dollar amounts and program statuses change with program years and budget cycles; the linked source governs any individual figure. State coverage is representative at the flagship level. Federal entries reflect the changes enacted by the One Big Beautiful Bill Act (Public Law 119-21, July 4, 2025).

## License and citation

This data is released under the Creative Commons Attribution 4.0 International License (CC-BY-4.0). See the `LICENSE` file at the repository root. Reuse is free with attribution. Please cite the accompanying manuscript; the citation metadata is in `CITATION.cff` at the repository root.

## Sources

Database of State Incentives for Renewables and Efficiency (DSIRE), N.C. Clean Energy Technology Center, https://www.dsireusa.org/. Internal Revenue Service guidance on Public Law 119-21, https://www.irs.gov/newsroom/. U.S. Department of Energy, Home Energy Rebates Programs, https://www.energy.gov/scep/home-energy-rebates-programs. Administering-agency and utility program pages. All current to June 2026.
