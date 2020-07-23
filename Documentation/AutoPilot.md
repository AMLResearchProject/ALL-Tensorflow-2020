# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project
## Acute Lymphoblastic Leukemia Tensorflow CNN 2020

![Acute Lymphoblastic Leukemia Tensorflow 2020](../Media/Images/Peter-Moss-Acute-Myeloid-Lymphoblastic-Leukemia-Research-Project.png)

&nbsp;

# Using AutoPilot functionality

To run in autopilot we'd be utilizing 3 scripts:

1. AutoPilot.sh
2. Randomizer.sh
3. TimeDiff.sh

All of these are located inside the Scripts folder of the CNN Directory. So, first step is to go inside the Scripts directory.

```
cd Scripts
```

From here we run

```
sh AutoPilot.sh
```
**AutoPilot.sh** acts as a wrapper for **Script.sh** and runs all the remaining scripts. Now sit back and enjoy the ride as dependencies start installing on their own, but before you can completely relax you have to provide a couple of more inputs

```
Do you want to randomize the image transfer in Test folder? (Y/N) -
```
If you put N here, then **Randomizer.sh** will replicate the exact scenario in terms of sorting Train and Test images based on which we measured performance.

```
Enter path to im folder of ALL_IDB1 (in Windows path should be in format C:/Users/ instead of C:\Users\
```
This one is pretty self explanatory, so path to be provided by User should be in the format C:/Users/XYZ/PML-AI-Research/ALL_IDB_Data/ALL_IDB1/im

Once all this is done, Training and Testing would begin with **TimeDiff.sh** running each of them and recording the total time taken by each.

&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](../CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

&nbsp;

## Contributors

- [Rishabh Banga](https://www.leukemiaresearchassociation.ai/team/rishabh-banga "Rishabh Banga") - [Asociacion De Investigation En Inteligencia Artificial Para La Leucemia Peter Moss](https://www.leukemiaresearchassociation.ai "Asociacion De Investigation En Inteligencia Artificial Para La Leucemia Peter Moss") Research & Development, Delhi, India

# Versioning

We use SemVer for versioning. For the versions available, see [Releases](../releases "Releases").

&nbsp;

# License

This project is licensed under the **MIT License** - see the [LICENSE](../LICENSE "LICENSE") file for details.

&nbsp;

# Bugs/Issues

We use the [repo issues](../issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](../CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.