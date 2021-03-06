# Awesome Risk Quantification

Risk quantification attempts to assign numeric values to risks, instead of qualitative labels such as "Critical"
and "High".

Doing this makes it easier to prioritize the different risks we need to mitigate. Also, "you can't
improve what you can't measure"!

This repository focuses primarily on cybersecurity related risks.

## Open Source Projects

- [Raven](https://github.com/idaholab/raven) - a "flexible and multi-purpose uncertainty quantification, regression analysis, probabilistic risk assessment, data analysis and model optimization framework" from the Idaho National Laboratory
- [riskquant](https://github.com/Netflix-Skunkworks/riskquant) - a library for computing risk, using different distributions, from Netflix
- [evaluator](https://github.com/davidski/evaluator) - R package for quantitative risk assessment, based upon [OpenFAIR](https://www.opengroup.org/certifications/openfair)
- [collector](https://github.com/davidski/collector/) - R package for "conducting quantitative risk assessment interviews"

## Blog Posts and Papers

- [7 techniques for assessing frequency when quantifying cybersecurity risks](https://medium.com/@veeralpatel/7-techniques-for-assessing-frequency-when-quantifying-risk-2fdd0bf26c77) - describes 7 techniques I either came up with, or found while researching risk quantification, for estimating the frequency of bad events
- [Open-Sourcing riskquant, a library for quantifying risk](https://netflixtechblog.com/open-sourcing-riskquant-a-library-for-quantifying-risk-6720cc1e4968) - demonstrates how to use
  their [riskquant](https://github.com/Netflix-Skunkworks/riskquant) library
- [2018 in Review: How Our Bug Bounty Program Guided Prioritizing Work](https://hackerone.engineering/posts/2018-in-review-how-our-bug-bounty-program-guided-prioritizing-work) - discusses how HackerOne uses bug bounty related metrics, like time to resolution, to prioritize certain security initiatives
- [Forecasting Risk inside an Organization](https://wardolphin.party/2020/01/24/Forecasting-risks-inside-an-organisation.html) - a post on how Atlassian attempts to forecast the chance of detecting red team operations, with the goal of improving detection over time.
- [Simple Risk Measurement](https://magoo.github.io/simple-risk/) - in-depth guide covering scenarios, calibration, panels, Brier scores, Monte Carlo simulations, and a lot more. Check out his [reading list](https://magoo.github.io/simple-risk/reading.html) as well.
- [Ryan McGeehan's blog](https://scrty.io/) - has 30+ posts on measuring risk and forecasting.
- [Risk Management: Out with the Old, In with the New!](https://exploringpossibilityspace.blogspot.com/2013/08/risk-management-out-with-old-in-with-new.html) - proposes we think of risks as parts of an interconnected system, not as isolated entities
- [A New Approach for Managing Operational Risk](https://www.soa.org/globalassets/assets/files/research/projects/research-new-approach.pdf) - expounds on the approach in the article above, applying it to financial risk specifically
- [Developing expert political judgment](http://journal.sjdm.org/16/16511/jdm16511.pdf) - describes a cognitive debiasing course sponsored by the intelligence community which increased Brier scores by 6 to 11%
- [Ten commandments for superforecasters](https://fs.blog/2015/12/ten-commandments-for-superforecasters/) - lists ten practical tips for producing more accurate predictions
- [Weather analysis and forecasting](https://www.ametsoc.org/ams/index.cfm/about-ams/ams-statements/statements-of-the-ams-in-force/weather-analysis-and-forecasting/) - a high-level overview of how meteorologists predict the weather

## Books

- [Measuring and Managing Information Risk: A FAIR Approach](https://www.amazon.com/Measuring-Managing-Information-Risk-Approach/dp/0124202314) - describes the [FAIR](https://en.wikipedia.org/wiki/Factor_analysis_of_information_risk) framework for measuring risk
- [How to Measure Anything in Cybersecurity Risk](https://www.amazon.com/How-Measure-Anything-Cybersecurity-Risk-ebook/dp/B01J4XYM16) - a spin-off of the author's [How to Measure Anything Book](https://www.amazon.com/How-Measure-Anything-Intangibles-Business-ebook/dp/B00INUYS2U), specifically for cybersecurity risk
- [Superforecasting](https://www.amazon.com/Superforecasting-Science-Prediction-Philip-Tetlock/dp/0804136718) - describes what skills make a person great at the art of prediction, even if the person lacks domain expertise
- [Expert Political Judgment](https://www.amazon.com/Expert-Political-Judgment-Good-Know-ebook/dp/B072F4X6QY) - points out the "perversely inverse relationship between the best scientific indicators of good judgement and the qualities that the media most prizes in pundits"
- [Loss Models](https://www.amazon.com/Loss-Models-Decisions-Probability-Statistics/dp/1119523788/) - discusses techniques including "random variables, basic distributional quantities, parametric, non-parametric, Bayesian estimation methods". originally for actuaries

## Talks

- [Quantifying Risk](https://www.infoq.com/presentations/risk-quantification-netflix/) by Markus De Shon (2020) - walks through the process of measuring risk, from identifying threats and assets to guessing frequency and magnitude (in terms of money)
- [Forecasting, Browsers, and “In The Wild” Exploitation](https://www.youtube.com/watch?v=vzcmzj-JuWk) by Ryan McGeehan (2019) - Ryan forecasts the probability of a Chrome zero day being exploited in the wild in a certain month

## Related Subjects

- [Failure mode and effects analysis (FMEA)](https://en.wikipedia.org/wiki/Failure_mode_and_effects_analysis) - methodology for identifying the failure modes in a system
