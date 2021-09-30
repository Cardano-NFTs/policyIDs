# policyIDs
CNFTs Verified Policy Database

__**To add your project to the list of verified policies for the marketplace:**__

**__Important:__ You must show proof of your project by tweeting your pull request to your projects twitter and linking in your pull request
Alternatively, provide adequate proof such as a direct link to project website with policies**

Make a pull request to add a file to the repository in this format.

__**Information:**__

**project:** Name of your project

**policies** one or many policy ids of your project

https://www.youtube.com/watch?v=z6yPjed4sMI

Validate your code before requesting: https://jsonformatter.curiousconcept.com/#

Single Project:
```json
{
    "project": "CardanianSnowGlobes",
    "tags": [
        "CardanianSnowGlobes"
    ],
    "policies": [
        "2d1e33d10789b2284788e7e67bd3fd2d07194720bc81f475adf45cbe",
              "eadf22778135584d96da25ebf4696de1e2bed4b9422ea24444442ade",
              "8aae5b74fb6f66755911200634427ea484bfd2bd313db30a37e96c7b"
          ]
}

```

Multiple Projects under one name:
```json
[
    {
        "project": "Example 1",
        "policies": [
            "Example1",
            "Example2"
        ]
    },
    {
        "project": "Example 2",
        "policies": [
            "Example 2"
        ]
    }
]
```
