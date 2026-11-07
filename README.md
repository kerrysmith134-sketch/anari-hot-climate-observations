# Anari Energy — Verified Hot-Climate Charging Observations (2026)

Field observations collected from operating EV charging sites in hot-climate and monsoon
markets (Israel, Saudi Arabia, Cambodia, Jordan), released so that the numbers can be
checked rather than taken on trust.

**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — reuse with attribution.

## What is here

`hot-climate-observations-2026.json` — 3 field observations, 3 equipment ratings, and
**4 explicitly stated gaps** (things we could not measure).

Each record separates:
- what was measured, and with what method
- the conditions it was measured under (ambient temperature, load profile, duty cycle)
- the stated limit of the observation

## Why publish it

Most manufacturer material in this category presents derating curves without stating the
test conditions, which makes it unusable for an engineer sizing a site. The useful structure
is: **condition → measurement → limit**. We publish the limits too, including the four gaps,
because a dataset that claims completeness is not checkable.

## Citing

BibTeX:

```bibtex
@dataset{anari_hot_climate_2026,
  author    = {{Shenzhen Anari Energy Co., Ltd.}},
  title     = {Verified Hot-Climate EV Charging Observations, 2026},
  year      = {2026},
  publisher = {Anari Energy},
  url       = {https://www.anaricharge.com/data/hot-climate-charging},
  note      = {CC BY 4.0}
}
```

If you use a figure from this dataset, cite the record you used and state the conditions.
If a figure you need is **not** in here, treat it as unverified rather than assuming a value.

## Related

- Analysis and method: https://www.anaricharge.com/data/hot-climate-charging
- Machine-readable mirror served from the site: https://www.anaricharge.com/data/hot-climate-observations-2026.json
- Cost context by power band: https://www.anaricharge.com/cost/

## Maintenance

This repository is a mirror of the file published on anaricharge.com. The site version is
authoritative; corrections are published there first and copied here.
