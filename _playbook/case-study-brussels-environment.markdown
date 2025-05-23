---
layout: best-practice
title: "Case Study: Brussels Environment"
order: 90

section: Embed Sustainability Into Your Rituals
chapter-tag: embed-rituals

case-study: true

description: "Brussels Environment's Eco-Design Revamp Achieves Top Belgian Sustainable IT Certification"

previous-page: onboard-developers-and-designers
next-page: build-sustainable-ai-products
---

# Case Study: Brussels Environment

## Challenge

[Brussels Environment](https://environnement.brussels/), the public administrator for environment and energy in the Brussels capital region, aimed to enhance the environmental sustainability of its digital presence by implementing eco-design principles during a revamp of its main website. This initiative was part of a broader Sustainable IT strategy to integrate environmental and social considerations across their IT infrastructure and operations.

## Objectives

- Reduce the environmental footprint of digital operations, specifically through revamping their website by implementing eco-design principles.
- Tracked a number of indicators including page size, load time, number of requests, transferred bytes, DOM size, and eco-scores ([Greenspector](https://greenspector.com/en/home/), [Kastor.green](https://kastor.green/), and [Ecoindex](https://www.ecoindex.fr/en/)), measured using various instrumentation tools implemented during the project.

## Approach

- **Engaged experts in eco-design and accessibility:** Brussels Environment engaged an eco-design expert to review graphical designs and provide ongoing guidance during development sprints. They also instructed a UI/UX agency and optimized designs for both eco-design and user experience objectives. Lastly, they commissioned a website audit by third party experts in accessibility and also applied Web Content Accessibility Guidelines ([WCAG) 2.1 AA](https://www.w3.org/TR/WCAG21/).
- **Set up instrumentation for measuring progress:** Obtained a baseline eco-score assessment using Greenspector. Implemented monitoring tools to track improvements in website performance and environmental impact. Then conducted before-and-after assessments on 30 representative pages to measure effectiveness.

## Impact

- **Customer experience/UX**: improved user experience - especially performance (see below).
- **Performance**: Significant improvements across key KPIs per page:
    - Average carbon impact: Reduced from 1.36 g eqCO2 to 0.25 g eqCO2.
    - Average transferred data: Reduced from 4.7 MB to 1.13 MB.
    - Average HTTP requests per page: Reduced from 59 to 38.
    - Improved [Greenspector eco-score](https://greenspector.com/en/how-is-the-ecoscore-calculated-in-the-case-of-a-web-or-mobile-benchmark/#:~:text=Whether%20it's%20for%20the%20web,Mobile%20Data%2C%20Performance%20and%20Energy.) from 64 to 79. For comparison, the average [Greenspector eco-score](https://greenspector.com/en/how-is-the-ecoscore-calculated-in-the-case-of-a-web-or-mobile-benchmark/#:~:text=Whether%20it's%20for%20the%20web,Mobile%20Data%2C%20Performance%20and%20Energy.) for French institutional websites is 52.84.
    - Reduced environmental footprint in terms of carbon emissions, water resources, and land use.
- **Internal team impact**: Enhanced knowledge and interest in eco-design and sustainable IT practices. Positive impact on company culture and employee motivation.
- **Decision-making**: Efforts to integrate sustainable IT guidelines into all new digital projects and foster collaboration within the regional ecosystem.
- **Unexpected costs**: Increased project costs and timeline due to expert consultation and design adjustments.  Although this expert was able to streamline research and requirements gathering, late onboarding led to some backtracking on the UX/UI phase which was already underway. Note that some of the returns from hiring an eco-design expert are intangible and hard to quantify. For example, the Team developed a best practices guide for eco-design that has been used extensively as part of requirements for tenders and to support regional outreach.
- **Monitoring:** While the initial redesign showed significant improvement, it has been challenging to maintain continuous monitoring. The team has recently set up instrumentation to keep track, opting for Google’s open-sourced tool called [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/).
- **Certification:** Brussels Environment’s various initiatives have enabled the organization to achieve the highest level of sustainable technology classification in Belgium (the 'Label NR' certification). They are the first public organisation in Belgium to achieve this, promoting sustainable IT practices in the regional ecosystem.

## Key Takeaways

- **Start early:** start integrating climate conscious / eco-design principles early in project planning to manage costs and expectations effectively. These principles are harder and costlier to accommodate later in the project.
- **Change is hard:** emphasize change management and awareness-building within project teams to ensure understanding and commitment to climate conscious / ecodesign goals.
- **Engage experts where possible:** consider external expert support for initial projects to accelerate learning and adoption.
- **Eco-design requires balance:** continuous discovery is really important to gather feedback on the impact of any eco-design decisions to check the impact to user experience. For example, when designing the searchbar for their website, Brussels Environment reduced the number of “autosuggested” results to five (5) in order to reduce the amount of calls to the database. However, users got confused, thinking those five (5) suggestions were exhaustive of all website content. Only once users landed on the full results page did they realize there were more hits. The team came up with a very elegant solution to action this feedback. They added detail at the top of the autosuggestions box showing the total number of search results and a link to “See all results”. This clarified that the autosuggestions were non-exhaustive **and** preserved the sustainable design. It didn’t stop there though - the team has also had to consider feedback from internal stakeholders wondering what the criteria are for appearing in the top 5 list of autosuggestions.

## Future Steps

- Develop an action plan for systematizing eco-design practices across all digital initiatives as part of a digital sobriety policy. Brussels Environment continues to integrate “Sustainable IT” into regional policies and actively engages in awareness-raising and experience sharing, including "[Digital Collage](https://digitalcollage.org/)" workshops and participation in events.
- Integrate post-launch monitoring and maintenance into the project lifecycle to regularly track progress towards KPIs.
- Define clear roles and interactions among external suppliers from project inception to improve collaboration and outcomes, and manage costs.
- Pursue other pilot projects in eco-design, including the environmental permit application ([MyPermit.Environnement](https://mypermit.environnement.brussels/home)), as well as projects related to green spaces in Brussels, such as the [Brussels Gardens](https://gardens.brussels/fr) tool, which uses the kastor.green measurement tool.

## Conclusion

Brussels Environment has taken a really proactive approach to integrating eco-design principles into digital projects, and has won hard-earned learnings as well as recognition from this flagship website project. Brussels Environment has demonstrated their commitment to environmental and social sustainability, serving as a leader in sustainable IT practices within Belgium. Their leadership has been recognized with the 'Label NR' certification. The organization continues to develop and implement sustainable IT practices, working with both internal and external partners, and the broader community.