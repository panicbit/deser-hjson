<a name="v1.0.0"></a>
### v1.0.0 - 2021-06-15
- it's stable. Calling it a 1.0

<a name="v0.1.13"></a>
### v0.1.13 - 2021-05-26
- make \r\n behave like \n
- allow more liberty for enum variants

<a name="v0.1.12"></a>
### v0.1.12 - 2021-02-13
- more precise number type guessing

<a name="v0.1.11"></a>
### v0.1.11 - 2021-02-11
- fix primitive types (ie not Hjson texts but primitives like integers and floats) needing a space at the end - Fix #1

<a name="v0.1.10"></a>
### v0.1.10 - 2021-02-11
- make from_str parse a `DeserializeOwned` instead of a borrowed `Deserialize<'a>`
