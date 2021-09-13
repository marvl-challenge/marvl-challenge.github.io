---
layout: default
title: The Task
nav_order: 1
---

# The MaRVL Task

Given *a pair of images* and *a caption*, the model needs to assign **TRUE**/**FALSE** to the example (i.e., juedge whether the caption is correctly describing the pair of images).

Two examples from MaRVL. The Tamil images (a) are from the concept [ஏறுதழுவல்](https://ta.wikipedia.org/wiki/ஏறுதழுவல்) ([Jallikattu](https://en.wikipedia.org/wiki/Jallikattu), part of an Indian festivity), while the Swahili images (b) are from the concept [leso](https://sw.wikipedia.org/wiki/Leso) ([Handkerchief](https://en.wikipedia.org/wiki/Handkerchief)).


## Example (a)
<img src="/media/images/front-page-tamil.pdf" height="3" width="600"> <br>
இரு படங்களில் ஒன்றில் இரண்டிற்கும் மேற்பட்ட மஞ்சள் சட்டை அணிந்த வீரர்கள் காளையை அடக்கும் பணியில் ஈடுப்பட்டிருப்பதை காணமுடிகிறது.<br>
(Translation: *In one of the two photos, more than two yellow-shirted players are seen engaged in bull taming.*)<br>
Label: **TRUE**<br>

## Example (b) 
<img src="/media/images/front-page-swahili-v3.pdf" height="3" width="600"> <br>
Picha moja ina watu kadhaa waliovaa leso na picha nyingine ina leso bila watu. <br>
(Translation: *One picture contains several people wearing handkerchiefs and another picture has a handkerchief without people.*)<br>
Label: **FALSE**<br>

