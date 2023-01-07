# Collections
Array Sets and Dictionary 


**Array:**

```
let ahmet = "ahmet"
let alex = "alex"
let ali = "ali"
let marcus = "marcus"
let veli = "veli"

let array : [Any] = [ahmet, alex, ali, marcus, veli, 12, veli]
array[4]  // "veli"
print(array) // ["ahmet", "alex", "ali", "marcus", "veli", 12, "veli"]
```
 

**Set: Set([index0, index1, index2])**
```
let setColorsObject = Set(["red", "green", "blue", "red", "blue"])
print(setColorsObject)` //  {"green", "blue", "red"}
```

**Dictionaries = dictionary[Key: Value]**
```
let dictionary = ["Ahmet": 1.70, "Alex": 1.80] // dictionary[String: Int]
dictionary["Alex"] // Alex = Key , and  dictionary["Alex"] = 1.80 -> 1.80 is a value
```

**Empty collections**
```
var emptyDictionary = [String : String] () //Creating an empty Dictionary
emptyDictionary["ahmet"] = "Ahmet" //appending a new value to dictionary
var emptyArray = [Int]() //Creating an empty Array
emptyArray.append(1)  //appending a new value to Array
var emptySet = Set<String>() //Creating an empty Set
```
