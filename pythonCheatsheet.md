V = Variable you want to change
O = Optional variable

Cheat sheet
Convert/ create
variableName = tuple(want to tuple)
variableName = list(want to list)
variableName = dict(two-value sequence to dict)

Reorder
variableName.sort()
sorted(variableName)

Addition
variableName.append(“newVariable”)
variableName.extend(“listName”)
(dictionaryName[key] = “newVariable”)

Combine
{**variableName1, **variableName2}
dictionaryName.update(newDictionary)

Modify
variableName[offset] = “newVariable”
“, ”.join(variableName)
variableName.split(“splitArgument”)
dictionaryName[key] = “newVariable” 
	
Copy
 
copy.deepcopy(variableName)

Remove
variableName.remove(“unwantedVariable”)
del variable[unwantedOffset]
variableName.pop(unwantedOffset/ key)
variableName.clear()

Get
dictionaryName[“key”] -> value
dictionaryName.keys() -> keys
dictionaryName.values() -> values
dictionaryName.items() -> keys and values
dictionaryName.get(“key”, “optional value”) -> value if no value -> optional value


Comprehensions
dict_variableName = {key:value for (key,value) in dictonary.items()}
list_variableName = [expression #number for item #number in iterable #range(1,6) if condition]
set_variableName = {expression #number for expression #number in iterable #range(1,6) if condition}

Sets
Intersection
S1.intersection(S2) or S1&S2 -> common values

Union
S1.union(S2) or S1|S2 -> values in either set

Difference
S1.difference(S2) or S1 - S2 -> In S1 but not S2

Symmetric difference
S1.symmetric_difference(S2) or S1 ^ S2 -> items in one set or the other, not both

Subset
S1.issubset(S2) or S1 <= S2 -> S1 also in S2

S2 needs to have all things in S1 and more, calculate with <
S1 < S2

Superset
S1.issuperset(S2) or S1 >= S2 -> S2 also in S1

S1 needs to have all things in S2 and more, calculate with >
S1 > S2


