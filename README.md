🧬 CaffeineForge Pro: Pharmacokinetic Response Simulator

CaffeineForge Pro uses a deterministic biological model to predict how the caffeine extracted in BrewForge interacts with your specific physiology. It visualizes the "Alertness Curve," accounting for metabolic half-life, receptor saturation, and diminishing returns.
🧪 The Biological Model

The simulator implements a Three-Phase Response Model:

    Phase 1: Growth (Sigmoid): Models the initial binding of caffeine to adenosine receptors.
    A=Abaseline​+(Apeak​−Abaseline​)⋅1+e−k⋅t1​

    Phase 2: Saturation: The "Goldilocks Zone" where receptors are optimally blocked.

    Phase 3: Negative Returns (Quadratic): Simulates the "over-caffeinated" state where jitteriness and anxiety override the cognitive benefits, modeled via a steepening decline curve.

🛠 Key Features

    Genetic Metabolism Profiles: Choose between Slow, Normal, or Fast metabolizers (modeling the CYP1A2 liver enzyme variants).

    Dynamic Alertness Graph: A real-time Plotly.js visualization of your stimulation levels based on total milligrams consumed.

    Tolerance & Condition Adjustments:

        Tolerance: Shifts the saturation point higher but lowers the peak alertness.

        Sleep Deprivation: Lowers the baseline, making the "spike" feel more intense but the crash more severe.

        Body Mass Scaling: Calculates the mg/kg concentration for more accurate dosing.

    Drink Preset Logic: A built-in database of common beverages (from Espresso to Matcha) to quickly log intake.

    Caffeine Timeline: Tracks the exponential decay (N=N0​⋅0.5t/h) of caffeine in your system throughout the day.
