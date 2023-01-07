# Collections
Array Sets and Dictionary 


**Array**

```
`let ahmet = "ahmet"`
`let alex = "alex"`
`let ali = "ali"`
`let marcus = "marcus"`
`let veli = "veli"`

let array : [Any] = [ahmet, alex, ali, marcus, veli, 12, veli]
array[4]  // "veli"
print(array) // ["ahmet", "alex", "ali", "marcus", "veli", 12, "veli"]
```
 

**Sets**
<br />
`let setColorsObject = Set(["red", "green", "blue", "red", "blue"])`
<br />
`print(setColorsObject)` //  {"green", "blue", "red"}
<br />
<br />
**Dictionaries = [Key: Value]**
<br />
`let dictionary = ["Ahmet": 1.70, "Alex": 1.80]` // **dictionary[String: Int]**
<br />
`dictionary["Alex"]` // Alex = Key and value dictionary["Alex"] = 1.80




**Empty collections**
<br />
`var emptyDictionary = [String : String] ()` //Creating an empty **Dictionary**
<br />
`emptyDictionary["ahmet"] = "Ahmet"` //appending a new value to dictionary
<br />
<br />
<br />
`var emptyArray = [Int]()` //Creating an empty **Array**
<br />
`emptyArray.append(1)`  //appending a new value to Array
<br />
<br />
<br />
`var emptySet = Set<String>()` //Creating an empty **Set**




