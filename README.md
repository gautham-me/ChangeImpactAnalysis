# Change - Impact analyser

Experiment to see what are the functional blocks needed to generate an impact document for change requests
As per ITIL, the Impact analysis (IA) must include the following 
- Cost analysis
- Time and Resource analysis
- Quality analysis
- Risk analysis

Based on some json about the request, 
1. I generated questions focussed on each analysis and run them against an open websearch ([tavily](https://tavily.com/))
2. Get the search results and summarize them for each analysis
3. Pass business context on what apps, mdm, budget and resrouces to evaluate whether to go ahead with the change
4. Generate a pdf as the "evaluation document"

### Obvious things I feel like we could improve on
- For each analysis, we can focus on improving the type of questions asked. 
- Based on the change, we can focus the search to forums of subject matter expertise. Eg: macbook sw upgrades, we should lookup support.apple.com or r/sysadmins
- Use similar previous changes to have a better Time estimation. 
- Risk analysis must include organizational asset data
