# policyIDs
CNFTs Verified Policy Database

__**To add your project to the list of verified policies for the marketplace:**__

**__Important:__ You must show proof of your project by tweeting your pull request to your projects twitter and linking in your pull request
Alternatively, provide adequate proof such as a direct link to project website with policies**

Make a pull request to add a file to the repository in this format.

__**Information:**__
**project:** Name of your project

**tags:** Uniquely identifiable tags for the name of your assets (mustn't be vague, is used for finding fakes)

**policies** one or many policy ids of your project

https://www.youtube.com/watch?v=z6yPjed4sMI

Single Project:
```json
{
    "project": "PlanetPalz",
    "tags": [
        "PlanetPalz"
    ],
    "policies": [
        "89fa6dc66a24799ccaee43a3a16930bb045a8152fdf2a2642034774f",
        "example66a24799ccaee43a3a16930bb045a8152fdf2a2642034774f"
    ]
}
```

Multiple Projects under one name:
```json
[
    {
        "project": "Example 1",
        "tags": [
            "Example"
        ],
        "policies": [
            "Example1",
            "Example2"
        ]
    },
    {
        "project": "Example 2",
        "tags": [
            "Example 2"
        ],
        "policies": [
            "Example 2"
        ]
    }
]



```


**Project** should be the name of your project.
**Tags** should include specific keywords that would identify the name of your NFTS, used to spot fakes.
**Policies** is an array of policy ids that can be seperated by commas
