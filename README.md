# recommendation-model

A model which recommends products matching the available products in the cart, according to the items placed previously in it.

While building this model I was facing problems to find a appropriate dataset. And then I came up to a conclusion to create own dataset to solve this problem.

```
How the Dataset is arranged:
1. For every entry in x_train there is a corresponding entry in y_train
2. Codes are gives for the entry of the comodities
     Every comodity has a code of three integers which are calculated as follows
      i. First Integer represents its type. You have to choose a integer from the options given below
        a.  food-item : 1
        b.  medicine : 2
        c.  self care : 3
        d.  electric : 4
        e   Study : 5
        f.  cleaning : 6
        g.  decoration : 7
        
      ii. Now the next two integers represents the subcategory (as it can be in two subcategories).
        For '1' (food-item)
        a.  vegetable :1
        b.  fruit : 2
        c.  liquid : 3
        d.  packed: 4
        e.  chinese: 5
        f.  dairy : 6
        
        For '2' (medicine)
        a.  fever : 1
        b.  family-planning : 2
        c.  for acute : 3
        d.  for chronic : 4
        e.  daily nutrients : 5
        f.  syrup : 6
        
        For '3' (self-care)
        a.  teeth : 1
        b.  hair : 2
        c.  face : 3
        d.  body : 4
        e.  grooming : 5
        f.  sanitizing : 6
        
        For '4' (electric)
        a.  hair : 1
        b.  computer : 2
        c.  laptop : 3
        d.  mobile : 4
        e.  other : 5
     
        For '5' (study)
        a.  writing : 1
        b.  paper : 2
        c.  measuring : 3
        d.  tools : 4
        
        For '6' (cleaning)
        a.  body : 1
        b.  surrounding : 2
        c.  electric : 3
        
        For '7' (Decoration)
        a.  self : 1
        b.  surrounding : 2
        
  ```
