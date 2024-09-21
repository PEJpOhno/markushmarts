# markushmarts

## 1. Overviews  
A python module to generate SMARTS description from Markush structure.  

## 2. Current version and requirements
current version = 1.0
pyhon 3.10, 3.11

## 3. Copyright and license
Copyright (c) 2024 Mitsuru Ohno  
Released under the BSD-3 license, license that can be found in the LICENSE file.  

## 4. Usage    
Also show sample_script.  
1. Define a variable substituent(s) with Q<1-digit index>.
2. Only Q or Q<addition of 2 or more digits> is not allowed and will result in an error.
3. If the candidate functional groups are the same for all variable substituents, they are given as a list. If different, they are given as a list; the variable substituent as a key and a list of its candidate functional groups as a value. 
4. If the displacement substituent contains hydrogen (atmon), specify with [H]. 
  
## About SMARTS  
https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html (cited 09/21/2024)  