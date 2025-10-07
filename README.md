# meteor-madness-impact-simulator
Asteroid Impact Simulation Tool for NASA Space Apps 2025

Google Colab Links: https://colab.research.google.com/drive/1Fv546Q9iyld-4twZziL1g9r_FdDVYByZ?usp=sharing 
                    https://colab.research.google.com/drive/1__i5KbnFWaGwABwo2v9dk8rKn8lP14V_?usp=sharing


## Features

###  1. Simulation Engine
Simulates asteroid deflection scenarios based on:
- Time to impact
- Velocity of deflection
- Energy absorption
- Crater size
- Resulting seismic magnitude

###  2. Linear Programming Optimization
Uses `scipy.optimize.linprog` to:
- Minimize mission cost
- Subject to constraints on deflection time, energy required, and mission feasibility

### 3. Policy-Aligned Risk Classification
Defines categories of risk based on simulation outputs to guide:
- Public preparedness
- Resource prioritization
- Early warning system investment

### 4. Visualization
Generates:
- Energy vs. crater size graphs
- Risk classification overlays
- Planning-oriented takeaways for decision-makers

### 5. OpenMDAO Integration
Includes a bonus file modeling a simplified version of the LP problem using NASA Glenn's [OpenMDAO](https://openmdao.org/) framework.

This lays the ground work for:
- More sophisticated multi-disciplinary optimization
- Potential NASA engineering pipeline integration

---

## Tools Used

- Python (NumPy, Matplotlib, SciPy)
- Google Colab
- OpenMDAO
- GitHub
- Linear Programming & Decision Modeling

---

## Why This Matters

- Public understanding of asteroid impact risks is often vague or alarmist.
- NASA’s mission planning can benefit from educationally friendly simulations.
- Optimization strategies support efficient resource use in space missions.
- A policy-aligned framing helps guide public funding, education, and early warnings.

This project bridges science, data, and public decision-making — all in under 200 lines of code.

---

##  Future Work

- Use real NEO (Near Earth Object) data from NASA CNEOS or JPL Horizons
- Extend the LP model with more constraints (launch windows, material limits)
- Create a Streamlit app for interactive simulations
- Contribute full OpenMDAO modules to the NASA GitHub ecosystem
- Publish policy recommendations with simulation-based evidence

---

##  Team

- **[Preethika Yetukuri](https://www.linkedin.com/in/preethika-yetukuri/)** — Mathematical Sciences (B.S.), Clemson University
- **[Pradhyun Yetukuri](linkedin.com/in/pradhyun-yetukuri-7b843836b/)** — High School Sophomore, Indian Land High School

---

## Contact

Interested in our work? Want to collaborate or learn more?

Reach out via:
- GitHub Issues
- LinkedIn (see profiles above)
- Emails: preethika.yetukuri@gmail.com ; pradhyun.yetukuri@gmail.com

---

## Judges, Reviewers, and Visitors

Thank you for checking out our project. We hope it inspired both technical curiosity and civic imagination.
