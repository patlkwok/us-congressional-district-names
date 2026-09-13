# If U.S. Congressional Districts Had Names

**A UK/Canada-style geographic naming scheme for all 435 congressional districts, using boundaries in effect for the 2026 elections.**

American congressional districts are numbered. British and Canadian constituencies are named after places — *Sheffield Hallam*, *Vancouver Kingsway*, *North East Somerset*. This project asks what the 435 would be called if the United States adopted that convention, and works through every one of them.

The answer turned out to be less interesting than the difficulty of arriving at it. Districts that resist naming are, with striking consistency, districts drawn to ignore geography. A seat running two hundred miles from west Memphis to the Nashville exurbs has no honest name, and the convention's failure to produce one is informative.

The full list is in **[districts.md](districts.md)**, or **[districts.csv](districts.csv)** for machine-readable form.

---

## ⚠ Boundaries change

These names describe specific maps, several of them contested. Texas, Louisiana and Tennessee were in live litigation as of September 2026. Missouri's 2025 map was blocked from use this cycle and goes to voters as Proposition A in November; Maryland has a constitutional amendment on the same ballot that would permit a redraw from 2027. Each state section notes which map it uses. Anything here can be superseded by a court, and some of it probably will be.

Corrections are welcome — see [Contributing](#contributing).

---

## The Naming Rules

These were not written in advance. They accumulated as the 435 districts were worked through state by state, and each one exists because some particular district broke the previous version. They are set out here in the order a reader needs them, not the order they were discovered.

### What a district is named for

**1. At-large states take the state name.** Alaska, Delaware, North Dakota, South Dakota, Vermont, Wyoming. (Compare *Nunavut*, *Na h-Eileanan an Iar*.)

**2. A district inside one city takes city + qualifier** — *Chicago North Side*, *Seattle Central*. (Compare *Edmonton Centre*, *Islington North*.) Two cases complicate what counts as "the city":

- **Smaller than the municipality — New York City.** The borough is the operative unit. Compass qualifiers attach to Manhattan, Brooklyn, Queens, the Bronx or Staten Island, never to New York City as a whole.
- **Larger than the municipality — Las Vegas.** Where the city limit is not what people mean by the name, the urban area governs. The Strip lies outside the city of Las Vegas, and the valley's largest communities — Paradise, Spring Valley, Sunrise Manor, Enterprise — are unincorporated, so *Las Vegas North* denotes the north of the metropolitan area. The municipal reading is kept where the surrounding communities are incorporated cities the list already names: *Miami South* means the southern part of the city of Miami, not the metro.

**3. Districts spanning several places take two to three anchors joined by em dashes** — *Flint—Saginaw*, *Escondido—Temecula—Palm Springs*. The em dash marks distinct communities; a hyphen would imply a single place name. Four anchors is permitted where nothing else describes the district (*Montmagny—L'Islet—Kamouraska—Rivière-du-Loup* is the Canadian precedent), but Elections Canada discourages it and so does this list. Nine of 435 names use four.

**4. Rural and multi-county districts take a regional name** where one is in genuine use — *Acadiana*, *Southern Illinois*, *Central Illinois*, *Western Minnesota*.

**5. "and" links a place to a region containing or adjoining it** — *Pasadena and the San Gabriel Valley*, *Spokane and Eastern Washington*, on the model of *Cities of London and Westminster*. The place comes first. Anchors of the same kind take em dashes instead.

**6. No district is named for a person.** Place names derived from people are fine, since they name the place: Houston, Compton, Bakersfield, Vacaville, Wickenburg.

**7. Anchors within a name take the same unit.** Counties pair with counties, cities with cities. Where a county name would otherwise read as a city, the first anchor carries "County" and the second inherits it — *Camden County—Gloucester North*, *Lancaster County—York South*. Inheritance disambiguates: *Lancaster County—York South* reads as two counties, while *Harrisburg—York—Carlisle* reads as three cities.

### How compass directions work

**8. Compass directions follow a city or county, and precede a state or region.** *Phoenix North*, *Gloucester North*, *Tucson East* — but *Western Montana*, *Eastern Idaho*, *Southern Illinois*.

- **North, South, East and West are relative.** They say where the district sits among the others sharing the city, not where it sits in absolute terms. *Miami North* and *Miami South* mean the northern and southern of the two districts holding Miami.
- **"Central" is not relative — it is a claim.** A district named *[City] Central* must contain that city's downtown. A boundary running through the CBD does not defeat the claim, provided the district holds the bulk of it including the civic and commercial core: CA-34 has City Hall and most of downtown Los Angeles, with 7th Street dividing it from CA-37; WA-07 has downtown Seattle bar the International District; NY-07 has Downtown Brooklyn bar DUMBO. Arlington's center is diffuse, but TX-06 contains the axis its street numbering divides on, which is enough. Where no district can make the claim, the city's districts take compass qualifiers only. IL-07 shows the stronger alternative — holding the Loop, it names it outright rather than calling itself Chicago Central.

**9. Established regional names override Rule 8 and are kept exactly as used locally** — *Northwest Arkansas*, *Northwest Indiana*, *North Shore*, *Southern Tier*, *Lowcountry*, *South Los Angeles*, *West Bronx*.

- **Test for establishment:** the name must be in genuine local use *and* have a Wikipedia article under that title. The article shows notability; it does not show currency, and tourism-board coinages can have one without the other. Where the halves disagree, currency governs: *Neighbor Islands* has no article but is the house style of Hawaii's press and appears in federal documents, so it qualifies. The article test exists to catch invented names, not to disqualify spoken ones.
- **A region must lie within one state.** This retired more names than any other test. The Inland Northwest, Ohio Valley, Merrimack Valley, Cache Valley, Quad Cities, Tri-Cities (Tennessee), Ozarks, Blue Ridge, Shenandoah Valley, Permian Basin and Eastern Shore are all real regions; none of them describes a district in one state. Washington's Tri-Cities passes because it sits wholly in Benton and Franklin counties.
- **A name must be unique within the list.** *Fox Valley* served both Illinois and Wisconsin; *North Shore* both Massachusetts and New York. Both were resolved by anchoring.
- **The name is not used where the district cuts across it.** Rule 9 protects a name when the district *is* that region. PA-02 and PA-03 divide Center City, North Philadelphia and South Philadelphia between them, with City Hall on the line, so they take the coined *Philadelphia East* and *Philadelphia West* rather than falsely claiming a section. This applies only to areas with definite extents: *Southeast Queens* has no settled boundary and describes exactly the part of the borough NY-05 holds, so it stands.

**10. Coined compass regions take the adjectival form** — *Western Minnesota*, *Central Illinois*, *North Central Pennsylvania*. The short form is reserved for names that already exist, which is why *Northwest Oregon* and *Western Idaho* sit side by side without inconsistency: the short form signals a name, the long form a description.

### Choosing and ordering anchors

**11. Anchors should bound the district, not merely list its largest towns.** Where two candidates are comparable, the more peripheral wins, because it does more descriptive work: CA-08 takes Vacaville over the comparably sized Fairfield, giving *Richmond—Vallejo—Vacaville*. Ashburn was dropped from VA-10 for sitting five miles from Leesburg.

**12. Order by size, then by the district's shape.**

- **Two anchors:** the larger leads — *Bridgeport—Stamford*.
- **Three, largest at an end:** it leads, the others follow in travel order.
- **Three, largest in the middle of a line:** traverse from the larger endpoint, giving 2-1-3 — *Richmond—Vallejo—Vacaville*. This case is far commoner than expected.
- **Triangular arrangement:** travel direction is undefined, so plain 1-2-3 by size — *Torrance—Inglewood—Compton*. But a triangle can still have a determinate traverse if only one route stays inside the district, as in TX-27.
- **Arcs and horseshoes:** the largest anchor leads and the other two follow the internal path. The 2-1-3 traverse does not apply, since it exists to describe extent on a linear district and would only bury the principal city on a curved one.

**13. A compass suffix confers no priority.** It leads in most names for a structural reason: a city large enough to be split is usually the largest place in any district it touches, while smaller cities fit inside one district and are never qualified. Louisiana shows the difference — New Orleans sits almost entirely in LA-02 while Baton Rouge is divided, so *New Orleans—Baton Rouge West* orders on size.

**14. Where a city is split, order on the whole city's population**, not the fragment inside the district. The anchor names the city, and whole-city figures are checkable in a way in-district shares are not: *Chesapeake North—Norfolk—Newport News* leads on Chesapeake's full population.

**15. Near-ties go to the more prominent place**, prominence meaning regional standing rather than headcount. St. Cloud trails Blaine by 1,341 people but is a regional center and university town against a suburb, so MN-06 is *St. Cloud—Blaine—Chaska*; Myrtle Beach trails Florence by 8% and leads on fame alone. The clause fires only where standing genuinely differs: Fort Payne and Jasper are comparable small towns 355 people apart, so the figure decides.

**16. A split city takes a compass qualifier only where two district names compete for it.** CA-28 makes no claim on Rancho Cucamonga, so CA-33 takes it unqualified. Where both claim it, both are qualified — *Kansas City West* and *Kansas City East*, *Greensboro East* and *Greensboro West*.

---

## Limits of the Rules

**The rules were built while the list was being written, so earlier names do not all satisfy later rules.** Several states were finished before the multistate test, the unit-matching rule or the arc clause existed. Where a conflict was noticed it was fixed, but the early states were audited against a thinner rulebook than the late ones, and some names surely survive that a fresh pass would change.

**Strict compliance is often impossible.** The rules pull against each other — extent against size, established name against accuracy, brevity against completeness — and on a difficult district at least one has to give. The nine four-anchor names are the visible cases; there are more where three anchors were made to serve because a fourth would have been unreadable.

**Population figures are from the 2020 census**, which is what a 2026 boundary review would have as its last complete count. Several Texas suburbs have grown by more than half since then, so some orderings reflect a city that no longer exists at that size. Any real convention would face this, and would revisit names at each review.

**Three things make naming hard, and gerrymandering is only one.**

- *Districts drawn to ignore geography.* TN-05 joins west Memphis to Franklin; CA-02 runs Redding to Marin; IL-02 goes from Kenwood to Danville. The names read as lists of unrelated places because that is what the districts are.
- *Unusual municipal boundaries.* Chicago's suburbs interlock so irregularly that Elmhurst splits East and West across two districts and Aurora North and South across two more — compass qualifiers doing work at a scale Westminster never contemplates, where the split unit is a suburb of 45,000.
- *Districts with no dominant place.* New Jersey outside Newark and Jersey City, and much of suburban Pennsylvania, consist of many similar mid-sized towns with no hierarchy among them. Counties are the answer there, which is what Westminster does with *Mid Bedfordshire* and *North East Somerset*. Rural districts have the same problem in reverse: a dozen towns of 20,000 and no reason to prefer any three.

**Naming is not neutral.** Capping anchors at three means most places in a district never appear in its name, and both British and Canadian commissions receive formal representations from towns arguing to be included. Selections here follow Rules 11 and 12 — geometry and population, nothing else — and imply nothing about the relative standing of the places involved.

## The Districts

The full list of all 435 names is in **[districts.md](districts.md)**, organized by state, with a note on which map each state uses.

Machine-readable form: **[districts.csv](districts.csv)**.

## Regional Names Considered and Retired

**Retired as coined here, never in genuine use:** Trinity Corridor (TX-33), Colorado Valley (TX-10), Muskingum Valley (OH-12), Maumee Valley (OH-05), West Branch (PA-15), Lake Ontario Shore (NY-24), Cascade Foothills (WA-08), Skylands (NJ-07) — the last documented as a tourism designation but not spoken locally.

**Retired as established, but for an area crossing the state line:** Ohio Valley (IN-09, OH-06), Piney Woods (TX-01), Permian Basin (TX-11), Red River (TX-04), Blue Ridge (NC-11), Cumberland Valley (PA-13), Monongahela Valley (PA-14), Shenandoah Valley (VA-06), Tri-Cities (TN-01), Ozarks (MO-08), Northwoods (WI-07), Eastern Shore (MD-01), Quad Cities (IL-17), Merrimack Valley (MA-03), Cache Valley (UT-02), Inland Northwest (WA-05). Each names a real region; none is contained within one state. Washington's Tri-Cities (WA-04) passes the same test and is retained.

**Retired as duplicated inside the list:** Fox Valley served both IL-14 and WI-06; North Shore both MA-06 and NY-03. Resolved by anchoring the Illinois and Massachusetts districts.

**Retired for naming an area the district does not correspond to:** Northeast Philadelphia and West Philadelphia (PA-02, PA-03), where the districts cut across Center City, North Philadelphia and South Philadelphia alike; Northwestern Washington (WA-02), which as commonly used covers four counties excluding the Everett end of the district.

**Retired during state audits, having survived an earlier pass:** Texas Hill Country (TX-21), Texas Panhandle (TX-13), Coastal Bend (TX-27), Upper Peninsula (MI-01), Iron Range (MN-08), Pee Dee (SC-07), Salish Sea (WA-02), West Tennessee (TN-08). All were sound names; each lost to anchor towns that bounded its district better.

**Retained in the final list:** Mother Lode and Eastern Sierra (CA-05), Big Sur (CA-19), Mojave (CA-23), Imperial and Coachella Valleys (CA-25), Antelope Valley (CA-27), San Gabriel Valley (CA-28), South Los Angeles (CA-37), Western Slope (CO-03), Big Bend (FL-02), Space Coast (FL-08), Florida Keys (FL-28), Neighbor Islands (HI-02), Chicago Southland (IL-02), Jackson Purchase and the Pennyrile (KY-01), Bluegrass (KY-06), Acadiana (LA-03), Berkshires (MA-01), North Shore (MA-06), Cape Cod and the Islands (MA-09), The Thumb (MI-09), Arrowhead (MN-08), The Delta (MS-02), Seacoast (NH-01), South Shore and North Shore (NY-02 to NY-04), Southern Tier and Catskills (NY-19), Adirondacks (NY-21), Western North Carolina (NC-11), Northwest Oregon (OR-01), Columbia Gorge (OR-03), Lehigh Valley (PA-07), Poconos (PA-08), Lowcountry (SC-01), Tri-Cities (WA-04), Lower Columbia (WA-03), Olympic Peninsula (WA-06), Wiregrass (AL-02), Tennessee Valley (AL-05), Northwest Arkansas (AR-03), Northwest Indiana (IN-01).

---

---

## Contributing

Corrections are the point of publishing this. The most useful ones are:

- **A district doesn't contain the place named.** The commonest error, and the hardest to catch without a map.
- **A better anchor exists.** Usually a town that bounds the district's extent better than the one chosen (Rule 11).
- **The ordering is wrong.** Population figures, or a reading of the district's shape (Rule 12).
- **A regional name fails a test.** Not in genuine local use, crosses a state line, or duplicates another name in the list (Rule 9).
- **The map has changed.** Litigation moves fast.

Open an issue using the district correction template. Please include the district number, the current name, what you propose, and why — the reasoning matters more than the suggestion, because the rules have to stay consistent across all 435.

Disagreements about the rules themselves are also welcome. Several of the current rules exist because someone pointed out that the previous version produced a bad name.

## License

Released under CC0 1.0 — public domain dedication. No attribution required, no conditions on reuse.

## How This Was Made

The starting point was a first draft covering all 435 districts, written from general knowledge of American geography. That draft turned out to be substantially wrong, and the interesting part of the project was finding out how.

Each state was then audited district by district against its current boundary map. Names were checked for three things: whether the district actually contains the places named, whether the anchors bound its extent, and whether the ordering follows from population and shape. Most states needed corrections. Several needed rebuilding from scratch — Missouri, Ohio, Illinois and Texas bore almost no resemblance to their drafts.

The rules were not written in advance. They accumulated during the audit, and each exists because a particular district broke the previous version. The compass-ordering convention came from Arizona. The rule that a regional name must lie within one state came from Washington, where "Inland Northwest" turned out to include Idaho. The limit on established names came from Philadelphia, where two districts divide Center City between them and neither can honestly claim it. Sixteen rules survive; several earlier ones were absorbed or discarded.

Two failure modes recurred often enough to be worth naming.

**Invented regions.** Where the draft lacked real knowledge, it generated plausible-sounding regional names rather than admitting the gap. "Trinity Corridor" for a district between Fort Worth and Dallas reads exactly like a real region. It is not one. Seven such names were caught and retired; the establishment test in Rule 9 exists to catch them.

**Established names for the wrong area.** Sixteen genuine, well-documented regional names were retired because they describe areas crossing state lines — the Ohio Valley, the Ozarks, the Blue Ridge, the Merrimack Valley. These pass every test for being real names. They simply cannot describe a district in one state.

Populations are from the 2020 census, which is what a boundary review conducted in 2026 would have as its last complete count.

### On the collaboration

This list was produced through an extended exchange with Claude, an AI assistant made by Anthropic. The division of labor was consistent throughout: the model drafted names and applied the rules; a human checked every district against an interactive boundary map and corrected what was wrong.

That division reflects a real limitation rather than a stylistic choice. The model could not see the maps. It knew the general shape of American political geography well enough to produce names that looked right, and not well enough to produce names that were right. Almost every substantive correction in this document came from the human side of the exchange. Most of the rules did too.

The rules themselves were genuinely joint work, and the document records where each came from.
