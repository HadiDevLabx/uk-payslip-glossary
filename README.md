# What every code on your payslip means

UK payslips are dense with abbreviations and almost none of them are explained
on the slip itself. This is the lot — PAYE, NI category letters, SSP and SMP,
AEO and DEA, SL and PGL, BIK, YTD, salary sacrifice, net pay arrangement and
the rest.

**Live:** <https://uk-payslip-glossary.netlify.app/>

One static page with a filter. No framework, no dependencies, no tracking.
Every term stays in the HTML whatever is typed — the filter only hides — so
the page is complete with scripting off and still one find-in-page away.

## The line worth checking first

**YTD.** A single month can look wrong and be right: National Insurance is
calculated per pay period and never smoothed, so a bonus month always looks
punitive, while income tax is cumulative and self-corrects. If the
year-to-date figures are right, the month almost certainly is too.

## Related

[Payroll deadlines](https://dev-lab-x.github.io/uk-payroll-dates/) ·
[Tax code decoder](https://hadidevlabx.github.io/uk-tax-code/) ·
[Student loan plan finder](https://uk-student-loan-plan.vercel.app/) ·
[Rates as JSON](https://github.com/HadiDevLabx/uk-tax-rates)

If a figure looks wrong, the
[payslip checker](https://truetakehome.co.uk/payslip-checker/) on
[True Take-Home](https://truetakehome.co.uk/) reconciles a slip line by line.

**Not tax advice.** Payslip layouts vary by employer and software; a label
here may appear differently on yours.

MIT licensed.
