This is a thought experiment on "how much nuclear would we use in Oahu if we could?"

This is unrealistic in several ways:

- assumes nuclear can be built on Oahu, despite current moratorium
- assumes nuclear can be built in arbitrarily small slices, but modular nuclear hasn't been commercialized yet
- assumes nuclear can be ramped and cycled daily
- ignores other concerns about new nuclear (lack of a waste program, proliferation concerns, accident concerns, etc.)

Nevertheless, this gives an idea of what might be a least-cost balance between nuclear, wind, solar and renewables in the mainland context, especially in an area with good sun and moderate loads.

Costs here are based on the National Renewable Energy Laboratories Annual Technology Baseline (ATB). These include a 65% markup on the cost of solar in Oahu and 35% on the cost of wind. Nuclear was also marked up by 65% to make it a fair comparison.

This can be run by installing Python, then Switch 2.0.2 or later (`pip install switch-model`), then cloning this repository to a local folder. Then `cd` into that directory and execute `switch solve`. If you want to see a solution without nuclear power, just remove the nuclear entries from inputs/gen_build_costs.tab and solve again.
