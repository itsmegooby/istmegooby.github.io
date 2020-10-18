---
layout: template
title: Example Page

---
# HackClub WebDevs

## Nested structures in C++
- A nested structure is a structure in another structures. To nest a structure inside of another structure we have to declare the nested structure before the structure its being nested in .

Syntax

```c++
struct nested_structure_name
{
  //datatypes
};

struct name_for_nesting_structure
{
  //datatypes
struct nested_structure_name variable_name_for_nested_structure;

}structure’s_variable;
```

For example

```cpp
#include <iostream>
using namespace std;

struct address
{
   string city="lusaka";
   string houseno= "124/96";	
};

struct student
{
  string name="DOREEN";
  int mark=60;
  struct address address1;
}student1;

int main ()
{
  cout<<student1.address1.city<<endl;
  cout<<student1.address1.houseno<<endl;
  cout<<student1.mark<<endl;
  cout<<student1.name;
  return 0;
}


```

