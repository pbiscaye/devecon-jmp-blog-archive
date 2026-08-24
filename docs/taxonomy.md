# Classification Definitions

## Geography

- **Africa**: Use when the featured paper's substantive study scope is Africa as a continent or a broad Africa-wide setting that should not be described as Sub-Saharan Africa.
- **Global scope**: Use for truly global scope or cross-country scope where specific countries are not the main study settings.
- **Latin America and Caribbean**: Use when the study setting is regional or when country detail is unavailable but Latin America and Caribbean is substantively the setting.
- **Multi-country**: Use for studies spanning multiple countries. Also assign country:ISO3 values for known country settings so public country filters remain intuitive.
- **No geographic study setting or not applicable**: Use for papers with no geographic study setting, such as abstract methods, evidence synthesis, or document-level studies without a place-specific setting.
- **South Asia**: Use when the study setting is regional or when country detail is unavailable but South Asia is substantively the setting.
- **Sub-Saharan Africa**: Use when the study setting is regional or when country detail is unavailable but Sub-Saharan Africa is substantively the setting.

## Research method

- **Cross-sectional observational**: Cross-sectional observational empirical analysis where this is the main high-level design. Keep distinct from descriptive_measurement.
- **Descriptive / measurement**: Use only when descriptive analysis, measurement, data construction, validation, accounting, survey measurement, or related non-causal empirical work is itself a central methodological contribution. Do not tag merely because the paper includes descriptive statistics, constructed indices, or measurement exercises inside a broader causal design.
- **Difference-in-differences / event study**: Difference-in-differences, event-study implementations of DiD, or closely related treated/control changes over time. Do not separately tag event study when it is an implementation of DiD.
- **Instrumental variables**: Instrumental variables designs based on first-stage and exclusion-restriction logic.
- **Lab experiment**: Laboratory experiments and lab-in-the-field experiments. Do not distinguish lab vs lab-in-the-field as separate top-level public categories. May co-occur with rct when randomized treatment assignment is genuinely central to the featured paper.
- **Other quasi-experimental design**: A clearly causal or quasi-experimental design that does not fit RCT, DiD/event study, RD, IV, panel FE/TWFE, selection-on-observables, or cross-sectional observational analysis. This is not a vague default bucket.
- **Panel fixed effects / TWFE**: Panel fixed-effects or two-way fixed-effects observational designs when this is the useful high-level empirical design and there is not a clearer DiD/event-study design. Do not add automatically when a DiD regression contains fixed effects.
- **Randomized controlled trial**: Any randomized controlled trial or randomized experiment with randomized treatment assignment. Do not distinguish individual, cluster, field, encouragement, rollout, or audit/correspondence variants in the active public taxonomy; preserve those details in evidence or reviewer notes when useful. Do not infer RCT solely from experimental tasks or a lab setting.
- **Regression discontinuity**: Regression discontinuity or RDD designs where treatment changes discontinuously at a threshold or cutoff.
- **Research methods / econometrics**: Use when the featured paper's principal methodological contribution develops, evaluates, validates, or synthesizes research methodology itself. This includes econometric/statistical methodology, causal-identification or inference methods, partial identification/bounds, experimental-design methodology, meta-analysis/evidence-synthesis methodology, external-validity methodology, and research-practice infrastructure such as trial registration when these are central contributions. This category may co-occur with a substantive design such as RCT, IV, or descriptive_measurement when both are genuinely central. Do not use it merely because a paper applies standard econometric methods.
- **Selection on observables**: Selection-on-observables, matching, propensity-score, reweighting, balancing, or related conditional-on-observables strategies when this is the main identification strategy.
- **Structural / theoretical modeling**: Structural estimation, calibration, simulation, or substantive analytical/theoretical economic modeling when the model itself is a central methodological contribution of the featured paper. This includes papers whose primary contribution is developing and analyzing a theoretical model, including analytical results and model simulations. Do not tag papers merely because they contain a simple theoretical or equilibrium model used to interpret otherwise empirical results.

## Research topic

- **Agriculture and food systems**: Agriculture, farming, food production, agricultural markets, crop/livestock technology, food systems, and agricultural livelihoods.
- **Climate, environment, and natural resources**: Climate, weather shocks, pollution, environmental markets, conservation, natural resources, water, forests, soils, and environmental regulation.
- **Conflict, crime, and violence**: Conflict, crime, violence, coercion, insecurity, contentious politics, and safety when central to the featured paper. Violence outcomes such as IPV may also receive this topic when violence is the central object.
- **Education and human capital**: Education, learning, schooling, skills, training, human-capital accumulation, and education-system outcomes.
- **Firms, entrepreneurship, and productivity**: Firm behavior, entrepreneurship, management, business growth, productivity, and firm performance. Use industrial_organization instead or additionally when market structure, market power, or competition is central.
- **Gender**: Gender differences, gender norms, discrimination, women's or men's outcomes, representation, gendered access to opportunities, and gender-based constraints.
- **Health and nutrition**: Health, nutrition, disease, health systems, medical research, health-care access, health behavior, and health outcomes.
- **ICT and digitalization**: ICT, digital platforms, digital services, algorithms, digitization of markets or services, online work, mobile or internet technologies, and related digital transformation when central. Distinct from information/media and from technology adoption.
- **Industrial organization**: Competition, market structure, firm interaction, market power, monopsony, organization of production or markets, and strategic behavior by firms or employers. Do not use for generic firm outcomes.
- **Information and media**: Information provision, communication, media, transparency, social media, information exposure, belief updating through information, and related information frictions when central. Do not use merely because a paper communicates something as part of an intervention.
- **Infrastructure and energy**: Infrastructure, transport systems, roads, irrigation infrastructure, electrification, energy access, utilities, and public works.
- **Intrahousehold and family decision-making**: Bargaining, household or couple decision-making, allocation within households, fertility or family decisions when the intrahousehold mechanism is central, and spousal/parent-child dynamics. Papers may also receive gender when appropriate.
- **Labor markets**: Employment, wages, hiring, job search, labor supply, worker productivity, unions, labor regulation, and labor-market discrimination.
- **Migration and urbanization**: Migration, spatial mobility, urbanization, slums, city growth, urban form, and spatial sorting.
- **Networks**: Social or economic networks, network structure, referrals, contacts, diffusion through ties, and network-mediated opportunities when networks are substantively central. Do not use for incidental peer or contact mentions.
- **Political economy and governance**: Political behavior, accountability, state capacity, public administration, regulation, governance, elections, civic action, and public-sector institutions.
- **Poverty, inequality, and social protection**: Poverty dynamics, inequality, redistribution, social protection, cash or asset transfers, safety nets, and poverty traps.
- **Psychology and behavioral mechanisms**: Beliefs, aspirations, motivation, preferences, salience, behavioral biases, perceptions, norms, self-efficacy, agency beliefs, and psychological mechanisms when central to the featured paper.
- **Research methods / econometrics**: Research methodology and econometrics as a substantive subject of the paper, including causal inference and identification, statistical/econometric inference, experimental design, partial identification, meta-analysis/evidence synthesis, external validity, research transparency, trial registration, replication/credibility infrastructure, or closely related evaluation methodology when central. Do not assign it merely because a paper uses econometrics.
- **Risk, insurance, credit, and household finance**: Risk, insurance, credit, savings, household or small-business finance, financial constraints, risk preferences, and financial resilience.
- **Technology adoption**: Take-up, adoption, use, diffusion, or sustained use of technologies or practices when adoption behavior is central. Do not use for every paper involving a technology.
- **Trade and industrial policy**: Trade policy, trade shocks, imports/exports, globalization, tariffs, and industrial policy. Use industrial_organization separately when market structure or firm interaction is central.

## Study population

- **Children**: Children, minors, infants, or adolescents when substantively central.
- **Communities**: Communities, local populations, villages, neighborhoods, or localities as the substantive population, especially for place-based studies with broad community-level effects.
- **Entrepreneurs or firm owners**: Entrepreneurs, firm owners, business owners, retailers, traders, importers, or managers when substantively central. Use free_text_detail for narrower groups.
- **Farmers**: Farmers and agricultural producers generally. Preserve narrower descriptions such as smallholder farmers, cocoa farmers, or tenant farmers in free_text_detail.
- **Firms**: Firms, businesses, establishments, plants, shops, or other firms as the substantive population of interest. Distinct from entrepreneurs_firm_owners, which is for owners or entrepreneurs as people.
- **Health-care providers**: Doctors, nurses, health workers, medical researchers as providers, or health-care professionals.
- **Households**: Households or families as the substantive population of interest. Can be used for intrahousehold papers without requiring a more specific couple or dyad population.
- **Low-income households**: Poor, low-income, vulnerable, or poverty-targeted households.
- **Migrants**: Migrants, internal migrants, international migrants, prospective migrants, or migrant households.
- **No substantive population / not applicable**: Use when the paper's substantive object is research methods, estimands, studies, experimental units, or research practice rather than a meaningful human, firm, or community population.
- **Other**: Use when the featured paper does not fit the current controlled categories.
- **Public officials**: Public officials, bureaucrats, civil servants, public employees, elected officials, or public administrators.
- **Refugees or displaced people**: Refugees, internally displaced people, or forcibly displaced populations.
- **Rural residents**: Rural residents, rural households, rural communities, or rural populations when rural status is substantively meaningful. Do not use merely to fill the population field.
- **Students**: Students, pupils, trainees, or learners.
- **Teachers**: Teachers or educators.
- **Urban residents**: Urban residents, urban households, city residents, commuters as urban residents, or slum residents when urban status is substantively meaningful. Do not use merely to fill the population field.
- **Voters**: Voters, citizens as voters, or electoral participants.
- **Women**: Women or girls when substantively central to the paper.
- **Workers**: Workers, employees, jobseekers, applicants, laborers, gig workers, platform workers, sex workers, commuters as workers, or other labor-market participants. Use free_text_detail for narrower groups.

## Unit of analysis

- **Administrative region**: Districts, counties, provinces, states, or other administrative regions as observed units.
- **Child or student**: Children, students, pupils, or learners as observed units.
- **Community**: Villages, neighborhoods, municipalities, localities, or similar local communities when the relevant empirical unit is a local community.
- **Country**: Countries or economies as observed units.
- **Document, text, or media item**: Documents, texts, research articles, posts, media items, social-media content, or other textual/media units.
- **Farmer or farm**: Farmers, farms, or agricultural producers as observed units.
- **Firm or establishment**: Firms, plants, shops, restaurants, establishments, or businesses as observed units.
- **Health facility**: Hospitals, clinics, health centers, or other health facilities as observed units.
- **Household**: Households, families, or household-level observations as observed or analyzed units. Use household and/or individual as appropriate for intrahousehold papers; do not use a separate dyad unit.
- **Individual**: People as individual observations when a more specific person-level unit is not appropriate.
- **Institution or organization**: Organizations, institutions, agencies, NGOs, public bodies, or other organizational entities.
- **Local government**: Municipalities, local governments, or local public administrations as observed units.
- **Market**: Markets, market segments, or market-level units as observed or analyzed units.
- **Other**: Use when the featured paper does not fit the current controlled categories.
- **Plot or parcel**: Land plots, parcels, fields, or farms' spatial production units.
- **School**: Schools or educational institutions as observed units.
- **Spatial cell**: Grid cells, pixels, or other constructed spatial units.
- **Transaction or contract**: Transactions, contracts, loans, trades, purchases, or agreements as observed units.
- **Worker**: Workers, jobseekers, applicants, or laborers as observed units.
