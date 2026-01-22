# Excersises Parts 1-6 Markdown Github Work-Repo: 

[[_TOC_]]

---

## Part One: Github Markdown Syntax for headers: 


```
# This is Header 1 

## This is Header 2 

### This is Header 3

#### This is Header 4

##### This is Header 5


###### This is Header 
```

FYI: 

- Header 6 is the lowest possible Header in Github Flavored Markdown Syntax! 

---

## Excersise Part 2: Adding Images via Markdown (Git) 

The basics syntax for performing the edit is: 
Add bang in the very begining: ex) !

["The Header or Image Desc"]("The URL or Path to the image in question")

Example: 

![SAMPLE IMAGE of Thai Demon](https://octodex.github.com/images/yaktocat.png)

So basically, I have to initiate a pull request for the currently-working-draft branch and compare it to the main branch for a pull request to be possbile. 

Then I should edit the index.md and add the edits and submit the addtions for merge and branch consolidation? 

---

## Excersises Part 3: Adding In-line code blocks for JS and others 

sample JSON 

```json
{
  "Title": "Graph response output",
  "Details": {
    "@odata.context": "https://graph.microsoft.com/beta/$metadata#deviceManagement/deviceEnrollmentConfigurations/$entity",
    "@odata.type": "#microsoft.graph.deviceEnrollmentPlatformRestrictionConfiguration",
    "id": "6f3fac11-99f5-4808-983c-43dee3fc6b31_SinglePlatformRestriction",
    "displayName": "Windows 기기 등록 허용",
    "description": "Windows 기기 등록 허용",
    "priority": 1,
    "createdDateTime": "2021-11-26T05:15:21.4365643Z",
    "lastModifiedDateTime": "2025-01-03T05:38:56.0093602Z",
    "version": 4,
    "roleScopeTagIds": [
      "0"
    ],
    "deviceEnrollmentConfigurationType": "singlePlatformRestriction",
    "platformType": "android",
    "platformRestriction": {
      "platformBlocked": false,
      "personalDeviceEnrollmentBlocked": false,
      "osMinimumVersion": null,
      "osMaximumVersion": null,
      "blockedManufacturers": [],
      "blockedSkus": []
    }
  }
}
```

Codeblock added above. 

---

## PART 4: Adding To-Do list via Markdown Syntax. 

GUIDE: 
```
- [] Have you checked the branch you are editing the code on?
- [] ARE YOU SURE??
- [] I dont think so?
```

Testing checklist Syntax. Perhaps filling in the check box is possbile with a ALL_CAPS "X"? Lets try that. 

- [X] Testing Checklist syntax number one!
- [ ] YES given that the checklist is automatically input IF the previous one has an X in the brackets, it does indeed appear to be correct.
- [ ] YEAH BABY, lets goo

---








