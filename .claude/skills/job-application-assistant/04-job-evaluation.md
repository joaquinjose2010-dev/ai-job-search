# Job Evaluation Framework

## Scoring Dimensions

Evaluate each job posting against these five dimensions.

### 1. Technical Skills Match (0-100)

| Score | Meaning |
|-------|---------|
| 80-100 | Core requirements are primary skills |
| 60-79 | Most requirements match, 1-2 gaps that are learnable |
| 40-59 | Partial match, significant upskilling needed |
| 0-39 | Fundamental mismatch |

**Strong match areas:** mechanical/hydraulic/electrical design & calculation; SolidWorks/Inventor/AutoCAD; ASME/API/ISO/IEC documentation; industrial maintenance (preventive/corrective, planning); PLC/automation; 5S/continuous improvement; medium/low-voltage distribution & microgrid; technical purchasing.
**Moderate match areas:** reliability engineering; project/process engineering; FEA (basic); technical-commercial/sales (via Andino); MATLAB; vehicle dynamics (self-taught, sim-based).
**Weak / aspirational areas:** formal motorsport/race-team experience; advanced CFD/aero; large-team people-management at scale; specialized software he hasn't used (name the specific gap when it appears).

### 2. Experience Match (0-100)

| Score | Meaning |
|-------|---------|
| 80-100 | Direct experience in the same domain and role type |
| 60-79 | Related experience, transferable skills clear |
| 40-59 | Adjacent experience, would need to make the case |
| 0-39 | Unrelated experience |

**Strong:** oil & gas equipment engineering, plant/maintenance engineering, mechanical design, technical documentation (ASME/API).
**Moderate:** process/reliability/project engineering, electrical MV projects, technical sales.
**Entry-level:** motorsport engineering (via transferable design + self-taught vehicle dynamics + committed UK postgrad plan).

### 3. Behavioral/Culture Fit (0-100)
See `02-behavioral-profile.md`. Strong fit: ownership, autonomy, greenfield projects, travel/relocation, fast pace, hands-on design. Friction: purely administrative or maintenance-only roles with no design/improvement scope, low-autonomy hierarchies.

### 4. Location & Logistics (Pass/Fail + Notes)
- **Joaquín is fully relocation-flexible worldwide — location is essentially never a FAIL.** Do NOT filter jobs out for distance.
- International travel / rotation / relocation: **PASS and a positive** (aligns with his stated preference).
- Note visa/work-permit implications for international roles (esp. UK motorsport) as a practical flag, not a disqualifier.

### 5. Career Alignment & Motivation (0-100)

| Score | Meaning |
|-------|---------|
| 80-100 | Strongly aligned with career direction, clear growth path |
| 60-79 | Good role but only partially aligned with long-term goals |
| 40-59 | Decent job but doesn't build toward career goals |
| 0-39 | Dead end or backwards step |

**Career goals:**
- **Now:** grow in large-scale engineering (oil & gas / industrial / plant / process), using global mobility as an advantage — this funds and de-risks the next step.
- **Medium-term (actively pushing now):** break into **motorsport engineering** (F1/junior formulae/suppliers), via a **UK Motorsport Engineering postgrad** (Motorsport Valley).
- **Always:** roles with real design/technical ownership and a steep learning curve.

**Motivation filter:**
- Tasks that energize: design & calculation, understanding *why* systems behave, large/high-stakes projects, new environments/travel, vehicle dynamics.
- Tasks that drain: purely administrative work, maintenance-only with no improvement/design scope, static roles with no growth.
- **Scoring bias:** a role that is a stepping stone toward motorsport/UK (international exposure, vehicle-adjacent design, simulation, English-speaking environment, relocation) should score higher on Career Alignment even if the domain differs.

**Life-situation alignment:**
- **Security:** employed; can afford to be selective; growth > short-term pay.
- **Flexibility:** no location or travel constraints.
- **Professional development:** prioritizes learning, project quality, brand, and anything that advances the motorsport goal.

### 6. Salary Benchmark (region-relative)
- **No hard salary floor.** Always relativize to the job's region and cost of living. Example given by Joaquín: 5,000,000 ARS is high in San Rafael but normal in Neuquén.
- For a posting, judge pay against *local* norms for the role, not a fixed number. Flag clearly under- or over-market offers.
- `salary_data.json` is not configured — skip the automated `salary_lookup.py` step unless it is later added.

## Output Format

```
## Job Fit Evaluation: [Role] at [Company]

| Dimension | Score | Notes |
|-----------|-------|-------|
| Technical Skills | XX/100 | ... |
| Experience Match | XX/100 | ... |
| Behavioral Fit | XX/100 | ... |
| Location | PASS | fully mobile |
| Career Alignment | XX/100 | ... (note motorsport-stepping-stone bonus if any) |

**Overall Score: XX/100**

### Verdict: [Strong / Good / Moderate / Weak / Poor Fit]
### Key Strengths for This Role
### Gaps to Address
### Recommendation
### Company Research Checklist
- [ ] Website (mission, values, recent news)
- [ ] Reviews (Glassdoor / local equivalents)
- [ ] LinkedIn (team, recent hires, connections)
- [ ] Media (restructuring, growth, issues)
- [ ] Visa/work-permit note if international
```

## Weighting
- Technical Skills: 30%
- Experience Match: 25%
- Behavioral Fit: 15%
- Career Alignment: 30%

(Location is pass/fail and, for Joaquín, effectively always PASS.)

## Thresholds
- **Strong Fit** (75+): Definitely apply, tailor everything
- **Good Fit** (60-74): Apply, address gaps in cover letter
- **Moderate Fit** (45-59): Consider — but bump up if it's a genuine motorsport/international stepping stone
- **Weak Fit** (30-44): Probably skip unless strategic (e.g. gets a foot into a race team)
- **Poor Fit** (<30): Skip
