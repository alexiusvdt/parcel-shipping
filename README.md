# Parcel Shipping

#### Shipping Simulation for MVC practice

#### By Alex Johnson

## Technologies Used

* C#
* .NET 6
* MSTest

## Description
 Following the guidelines below, create a website for a fictional shipping company that helps users calculate shipping estimates:

*Create a Parcel class and test it thoroughly. It should contain a constructor, and getters and setters for each property. You should be able to create a new parcel and specify the dimensions and weight in the arguments.

*Create a website where the user can submit a form with the dimensions and weight of a Parcel, and you can use the data in the form to instantiate a Parcel object and display its dimensions and weight.

*When you call a method called Volume() on a Parcel instance, it should return the product of the sides.

*When you call a CostToShip() method on your parcel, return a cost based on a formula you make up.

*Display the cost to ship and the volume of a Parcel with its dimensions in your site.

*Add validation and make sure the Parcel object is not created if any of the form fields are blank. Display an error message instead. Also make sure your user can only enter numbers into the form.



## Setup/Installation Requirements

* Clone this repo & navigate to the root directory
* open a command line prompt
* build the project using $dotnet build
* execute code with $dotnet run

dev note:
* to run tests, cd to the ProjectTests folder
* enter $dotnet test to run tests
* keep all dots in names, dont forget to update .gitignore

## Known Bugs

* If you find additional bugs not listed here, please email me at alex.johnson293@gmail.com with the subject **[_Repo Name_] Bug** and include:
  * BUG: _A brief description of the bug_
  * FIX: _Suggestion for solution (if you have one!)_
  * If you'd like to be credited, please also include your **_github user profile link_**

## Additional Thanks

*Elesh Norn - may her vision be compleat

## Future implementations


## License
MIT License

Copyright (c) 2022 Alex Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR 
PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS 
BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.