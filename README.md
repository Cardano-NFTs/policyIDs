# policyIDs
CNFTs Verified Policy Database

__**To add your project to the list of verified policies for the marketplace:**__

Make a pull request to add a file to the repository in this format.
Sufficient proof must be provided that you are the creator, providing a link to your twitter / discord will be great

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
