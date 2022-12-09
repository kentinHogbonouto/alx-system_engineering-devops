Title: Showcare sales form down on production

Incident date: 5/12/2022

Owner: Kentin Hogbonouto

Peer-review committee:
- Joel Gnanssounou
- Aymar Sossou
- Anatole Palnteur

Tags:
`Deployement` `Production` `Build`

Summary:
After fixing some some bugs about email sapn on showcare sales, we was unable to deploy it because the production mode fail, indeed after building the application the .next folder was not found in production, the . marque was replace by _ for some reason nobody can explain.

Supporting data:
Metric graphs, tables, or other data, that best illustrate the impact of this event.

Customer Impact:
one million of costumer was impact by this incident in about 2hours accross the world


- Was the event detected within the expected time?
No, the event was not detect within the expect time

- How was it detected?
after deployment

- How could time to detection be improved?
continous integration will defintely increase the detection time

- Did the escalation work appropriately?
No, it didn't

- Would earlier escalation have reduced or prevented the event?
Yes

- How did you know how to mitigate the event?

- How could time to mitigation be improved?

- How did you confirm the event was entirely mitigated?

Post-Incident Analysis:
- How were the contributing factors diagnosed?

- How could time to diagnosis be improved?

- Did you have an actual backlog item that could’ve prevented or reduced the impact of this event? If yes, why was this item not done?

- Could a programmatic verification rule (e.g., AWS Config) be used to prevent this event?

- Did a change trigger this event?

- How was that change deployed — automatically or manually?

- Could safeguards in the deployment have prevented or reduced the impact of this event?

- Could this have been caught and rolled back during the deployment?

- Was this tested in a staging environment? If yes, why did this pass through? Could more tests have prevented or reduced the impact of this event?

- If this change was manual, was there a playbook? Was that playbook practiced, tested, and reviewed recently?

- Did a specific tool/command trigger the event? Could safeguards have prevented or reduced the impact of this event? Was there any safeguard triggered? If not, why none were in place?

- Was a production operation readiness or well-architected review performed on the system(s)? If not, why? 

- When was the last evaluation done?

- Could a review have prevented or reduced the impact of the event?

Timeline:
- Detail all major event points with their time (included the timezone) with a short description.
09:19 EEST — database run out of connections. Link graph & log
