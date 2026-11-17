# Search Queries for Job Scraper

<!-- Configured for Joaquín Buttini: Argentine engineering (income base) + motorsport/UK (active target). -->
<!-- Joaquín is globally mobile ("the farther the better") — do NOT filter results by distance. -->

## Search Sites

**Motorsport / international (Priority 1):**
- **linkedin.com/jobs** - filter UK / Motorsport Valley / worldwide
- **motorsportjobs.com**, **thersa? / racecar-engineering job boards**, **f1jobs / teams' career pages** (Mercedes, Red Bull, McLaren, Williams, Alpine, Aston Martin, Haas, and F2/F3 & junior-formula teams and suppliers)
- UK postgrad programmes (context, not jobs): Cranfield, Oxford Brookes, University of Bolton

**Argentina engineering (Priority 2-4):**
- **linkedin.com/jobs** - filter Argentina / region
- **bumeran.com.ar**, **computrabajo.com.ar**, **zonajobs.com.ar**
- Company career pages via Google `site:` (YPF, Tecpetrol, Pan American Energy, Vista, Techint, Schneider Electric, Mastellone, plus Neuquén/Vaca Muerta operators and service companies)

## Query Categories

Grouped by priority. Combine with location terms where the site supports it, but remember location is **not** a filter for this profile.

### Priority 1: Motorsport / Vehicle Dynamics (active target — push now)

```
site:linkedin.com/jobs "graduate design engineer" motorsport
site:linkedin.com/jobs "junior mechanical design engineer" motorsport UK
site:linkedin.com/jobs "vehicle dynamics engineer" (graduate OR junior)
site:linkedin.com/jobs "simulation engineer" motorsport
site:motorsportjobs.com design engineer
site:motorsportjobs.com graduate
"race team" "graduate engineer" OR "junior engineer" careers
```

### Priority 2: Oil & Gas / Energy Engineering (Argentina — income base)

```
site:linkedin.com/jobs "ingeniero de planta" Argentina
site:linkedin.com/jobs "ingeniero de mantenimiento" (Neuquén OR "Vaca Muerta" OR Argentina)
site:linkedin.com/jobs "ingeniero electromecánico" oil gas Argentina
site:computrabajo.com.ar ingeniero mantenimiento petrolera
site:bumeran.com.ar ingeniero electromecánico
"ingeniero eléctrico" "media tensión" Neuquén OR "Río Negro"
```

### Priority 3: Industrial / Process / Oficina Técnica (Argentina)

```
site:linkedin.com/jobs "ingeniero de procesos" Argentina
site:linkedin.com/jobs "oficina técnica" ingeniero (SolidWorks OR Inventor) Argentina
site:linkedin.com/jobs "ingeniero de proyectos" industrial Argentina
site:computrabajo.com.ar ingeniero diseño mecánico
site:bumeran.com.ar ingeniero de planta OR ingeniero de producción
```

### Priority 4: Adjacent / Technical-Commercial (wider net — activate Andino profile)

```
site:linkedin.com/jobs "ingeniero comercial" OR "technical sales engineer" Argentina
site:linkedin.com/jobs "ingeniero de confiabilidad" Argentina
site:linkedin.com/jobs "field engineer" oil gas Argentina
site:linkedin.com/jobs "graduate engineer" (rotational OR international)
```

## Location Filter

**Global mobility — no distance filter.** Joaquín will relocate anywhere. Instead of excluding by distance, *prioritize* by strategic value:
- **Ideal:** UK motorsport hubs (Motorsport Valley), any race-team/supplier role anywhere; international oil & gas rotations; English-speaking or relocation-heavy roles that build toward the motorsport move.
- **Strong:** Neuquén / Vaca Muerta and other Argentine oil & gas hubs; large industrial employers anywhere in Argentina.
- **Fine:** San Rafael / Cuyo and remote/hybrid.
- Flag visa/work-permit requirements for international roles as practical notes, never as reasons to exclude.

## Date Filter

Only include jobs posted within the last 14 days, or with a deadline not yet passed. If a date can't be determined, include it flagged "date unknown".

## Adapting Queries

If the user runs `/scrape motorsport`, run all Priority 1 queries plus 2-3 custom ones for the named focus. `/scrape neuquen` → Priority 2 with Neuquén/Vaca Muerta terms. `/scrape broad` → all categories.
