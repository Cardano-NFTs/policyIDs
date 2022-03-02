# policyIDs
CNFTs Verified Policy Database 

__**To add your project to the list of verified policies for the marketplace:**__

**__Important:__ You must show proof of your project by tweeting your pull request to your projects twitter and linking in your pull request
Alternatively, provide adequate proof such as a direct link to project website with policies**

Make a pull request to add a file in the "projects" directory of this repository in the following format.
Please note that the name of the file **must not** contain any special character (:,./\@"'-_).

__**Information:**__

**project:** Name of your project

**policies** one or many policy ids of your project

https://youtu.be/8hoYS1xCyWM

Validate your code before requesting: https://jsonformatter.curiousconcept.com/#

Single Project:
```json
[
  {
    "project": "GoldCreditCard",
    "policies": [
      "19bbeb2252b0020d579ad2f1f3edb853157478d345d7433c65a24a28",
      "14466a705f27aba0690611056190090d83555fa782bfc42bb872027b",
      "15c1657c0fe8b29742847393d359b26e4f0363a5286e4e200eaae2fd",
      "29be1fff4f8286eb3a941d53537686ccc41cc8abea89311d0a1eef29",
      "311a56b40eca41eee2743864c34b5aaa53737d158becac14e547aee3",
      "858bdbb2ba41eb991131ae45619d910e94644ebfc980a28b415eed9f",
      "8e10928cf8376f2cb155cb3c963cc74e3c0ba47b77e2ce411e8bb639",
      "96e05f78a10d161be44328d6d240ffd5577de3b7df10f836a6fade73",
      "9b56df070a431ae465b324f1452128e77392c36ebf3097da96752ec9",
      "d95682e33324fc28913f53d3ecbbd7ec051e625c74a36a8cdea2de38"
    ]
  }
]

```

Multiple Projects under one name:
```json
[
  {
    "project": "YourFirstProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  },
  {
    "project": "YourSecondProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  }
]
```
