\# 🧠 Adoption Triage Decision Logic



Before coding the system, the algorithm workflow for pet adoption approval was mapped out using basic conditional logic (IF/ELSE):



1\. The adopter submits the interest form for a specific pet.

2\. \*\*IF\*\* `adopter.age < 18` ➡️ \*\*Action:\*\* Block adoption. \*\*Message:\*\* "Adoption only allowed for adults."

3\. \*\*ELSE IF\*\* `adopter.residenceType == "Apartment"` \*\*AND\*\* `pet.size == "Large"` ➡️ \*\*Action:\*\* Set status to "Pending NGO Review".

4\. \*\*ELSE\*\* ➡️ \*\*Action:\*\* Set status to "Approved for Interview".



