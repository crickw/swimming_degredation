# swimming_degredation
graphical representation of physical degradation for master swimmers by age for gender and stroke.


USMS doesn't publish qualifying times split by age group for the overall NQT standard (that's flat across ages), but the Spring Nationals meet documents do include an age-group breakdown table — that's what I used: men's 100 free, SCY, 2024 Spring Nationals, ages 18-24 through 80-84 (85+ has "NO TIME," insufficient data).

The curve isn't perfectly smooth — 25-34 actually gets slightly faster than 18-24 (competitive peak), then degradation is roughly flat through the 40s, and accelerates sharply after 55, hitting over 4.5%/year by the late 70s. That acceleration pattern matches known masters-swimming and general aging-physiology literature.

Since these times come from small age-group cohorts (Top-10 based), there's some sampling noise — to get a cleaner curve, I used the USA Swimming/USMS "age-grading" factor tables (built by fitting smoothed decline curves).

A key finding is that USMS doesn't publish an official, regularly updated age-grading factor table. The closest thing is a 2006 USMS article by David Nordstrom, built from 2004 Top-10 5th-place times across 18 events, expressed as ratios to each event's peak age-group time (1.000 = peak). It's dated, but it's genuinely USMS's own age-grading work and covers per-event, per-gender data — which the NQT table can't provide.

So the chart uses this ratio (not raw time) as the y-axis, since it directly represents "fraction of peak performance retained" and lets men's and women's curves and different events sit on the same 0–1 scale. Dropdowns let you flip between Men/Women and 18 events (all Free, Back, Breast, Fly, and IM distances in that dataset). The bottom panel recomputes the annualized %-slower-per-year rate live for whatever's selected.

Click any stroke pill (colored when active) to add/remove it from the comparison, up to 8 at once — defaults to 100 Free, Fly, Breast, Back for men. The top chart overlays lines (color + dash pattern + marker shape per stroke, so it's readable without color alone), and the bottom chart stacks each stroke's annualized decline rate per age band.
