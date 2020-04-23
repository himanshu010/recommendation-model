# recommendation-model

A model which recommends products matching the available products in the cart, according to the items placed previously in it.

While building this model I am facing problems to find a appropriate dataset. And then I came up to a conclusion to create own dataset to solve this problem.

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
        a.  vegetable
        b.  fruit
        c.  liquid
        d.  packed
        e.  chinese
        f.  dairy
        
        For '2' (medicine)
        a.  fever
        b.  family-planning
        c.  for acute
        d.  for chronic
        e.  daily nutrients
        f.  syrup
        
        For '3' (self-care)
        a.  teeth
        b.  hair
        c.  face
        d.  body
        e.  grooming
        f.  sanitizing
        
        For '4' (electric)
        a.  hair
        b.  computer
        c.  laptop
        d.  mobile
        e.  other
        
        For '5' (study)
        a.  writing
        b.  paper
        c.  measuring
        d.  tools
        
        For '6' (cleaning)
        a.  body
        b.  surrounding
        c.  electric
        
        For '7' (Decoration)
        a.  self
        b.  surrounding
        
  ```
  
  
  
