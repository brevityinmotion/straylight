# Project Straylight

Project straylight has been constructed as a foundation of accelerators, walkthroughs, designs, and tools that can help security researchers and companies improve their information security capabilities. 

The goals of project straylight are three-fold:
* __Accelerators__ — To introduce a series of accelerators that can help security researchers and companies improve their information security capabilities.
* __Mentoring__ — To help you advance your career in information security; whether you are just getting started, trying to advance into a principal technical role, or even if you are working in a leadership capacity.
* __Collaboration__ — To learn from you, to establish more connections, to bounce ideas for feedback, and to help solve this challenge of security together.

## Introduction
A deeper perspective on the overall project can be referenced in the Brevity In Motion blog at:
* __Introduction - Project Straylight - Security Accelerators, Mentoring, and Collaboration__ - https://medium.com/@brevityinmotion/introduction-project-straylight-security-accelerators-mentoring-and-collaboration-7426a32bd940?sk=7913ec6788585ac17c22065a64b1f267

"Stray light is light in an optical system, which was not intended in the design. The light may be from the intended source, but follow paths other than intended, or it may be from a source other than the intended source."

Success in security, hacking, and puzzles all require creativity, ambition, curiosity, and logic. Building a resilient defense is hard. Building an effective security program is exponentially harder.

Let's solve this together!


## Learning Resources
* [Information Security - Learning Resources](resources.md) - This is an inventory of my favorite security resources that I have leveraged across the past decade.

## Walkthroughs
### External IP domain reconnaissance and attack surface visualization in under 2 minutes.
* The blog post can be accessed at https://medium.com/@brevityinmotion/external-ip-domain-reconnaissance-and-attack-surface-visualization-in-under-2-minutes-b2ab06105def?sk=45a029919647bd3214e6dd1e8526ca25. This walkthrough provides the steps to configure AWS cloud based resources to query the Forward DNS stored in the Rapid 7 Project Sonar public dataset. The output of this process can be used to supplement passive domain reconnaissance techniques. It can also be integrated as a fully automated and entirely passive process to track attack surface on a monthly basis. The corresponding source code and Jupyter notebooks are contained within this repository to replicate the capability.
* The corresponding source code and Jupyter notebook utilized is located at [tools-r7sonar.ipynb](notebooks/tools-r7sonar.ipynb).

### Search the html across 25 billion websites for passive reconnaissance using common crawl
* The blog post can be accessed at https://medium.com/@brevityinmotion/search-the-html-across-25-billion-websites-for-passive-reconnaissance-using-common-crawl-7fe109250b83?sk=5b8b4a7c506d5acba572c0b30137f7aa. This walkthrough provides the steps to configure AWS cloud based resources to query the Common Crawl public dataset of over 25 billion websites archived across the past 8 years. The walkthrough will search domains and download the relevant archived html. Since posting the blog, the retrieved data is now processed inline using beautifulsoup so analysis can happen prior to writing to disk. Current functionality will capture and output a listing of all urls and comments within the html.
* The corresponding source code and Jupyter notebook utilized is located at [tools-commoncrawl.ipynb](notebooks/tools-commoncrawl.ipynb).

## Presentations
### Combining notebooks, datasets, and cloud for the ultimate automation factory
* 8/6/2020 - Defcon Red Team Village - @VillageRedTeam and @defcon
* Watch: https://www.youtube.com/watch?v=V5oHuSnZDFg
* Slides:

### Elevating your career through scientific computing and the cloud
* 6/27/2020 - Cyber June'gle 2020 - @VillageRedTeam and @texas_cyber
* Watch: https://www.youtube.com/watch?v=5d2c8-e6klE 
* Slides: [2020-Junegle-RyanElkins.pdf](presentations/2020-Junegle-RyanElkins.pdf)
* Thank you for the opportunity @santosomar and @cedoxX! Make sure to check out and subscribe to the Red Team Village Youtube channel to watch more great presentations! 

