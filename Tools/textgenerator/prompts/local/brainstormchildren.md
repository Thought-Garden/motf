---
PromptInfo:
 promptId: continueChilidren
 name: 🗞 Continue
 description:
 tags: 
 version: 0.0.1
---
content:  
Background Information:
{{#each children}} {{content}} {{/each}}

Content:
{{context}}

prompt:
Continue writing

