# policyIDs
CNFTs Verified Policy Database

__**To add your project to the list of verified policies for the marketplace:**__

Make a pull request to add a file to the repository in this format.

```json
{
    "project": "PlanetPalz",
    "tags": [
        "PlanetPalz"
    ],
    "policies": [
        "89fa6dc66a24799ccaee43a3a16930bb045a8152fdf2a2642034774f"
    ]
}
```

**Project** should be the name of your project.
**Tags** should include specific keywords that would identify the name of your NFTS, used to spot fakes.
**Policies** is an array of policy ids that can be seperated by commas
