# Logical Operators

## Logical Operator ব্যবহার করি কেন?
দুই বা ততধিক Propossition কে যখন যুক্ত করে নতুন propossition তৈরি করি তখন Logical operator ব্যবহার করি।

## Logical Operator
- ¬ -> NOT
- ∧ -> AND
- ∨ -> OR
- → -> IF....THEN
- ↔ -> Biconditional

## NOT (¬) সম্পর্কে
### Example
- Today is friday.
- এটির NOT(Nigation) হবে।
- It is not friday.

এখন Today is not friday কে যদি P variable চিন্তা করি তাহলে আসে
- p = Today is not friday
NOT(Nigation) হবে
- ¬p
## Logical Expression বোঝানোর জন্য সব থেকে সহজ উপায় হলো।
Truth table ব্যবহার করা।
- Truth table এ সারি সংখ্যা বের করার সূত্র 2<sup>n</sup>
- n = Total Variable
- এখানে, Total variable, n = 1 তাই সারি সংখ্যা, 2<sup>1</sup> = 2

### Truth table

| p | ¬p |
|---|---|
| T | F |
| F | T |

এখানে p এর মান True হতে পারে। কিন্তু Nigation করলে False হবে। আবার p এর মান False হতে পারে। যাকে Nigation করলে True হবে।

### Nigation example
1. 6 is negative = 6 is non negative
2. 2 + 1 = 3 = 2 + 1 != 3
3. There is no pollution in jusrse = There is pollution in jurse
4. The summer in marine is hot and summy. = The summer in marine is hot and summy.
5. Today is Friday. = Today is not Friday.

## AND (∧) Operator
- Today is Friday and raining.
এখানে, Today is Friday একটি Propossition এবং Raining একটা propossition. এটা হচ্ছে Complex propossition.
ধরি, p = Today is Friday
q = raining
তাহলে, p ∧ q

Truth table ব্যবহার করলে, = 2<sup>2</sup> = 4

| p | q | p∧q |
|---|---|---|
| F | F | F |
| F | T | F |
| T | F | F |
| T | T | T |

## OR(∨) Operator
- Today is Friday or raining.
এখানে, Today is Friday একটি Propossition অথবা Raining একটা propossition. এটা হচ্ছে Complex propossition.
ধরি, p = Today is Friday
q = raining
তাহলে, p ∨ q

Truth table ব্যবহার করলে, = 2<sup>2</sup> = 4

| p | q | p∨q |
|---|---|---|
| F | F | F |
| F | T | T |
| T | F | T |
| T | T | T |
