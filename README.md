# CRA
Course Rating Assistant, Automation of the World Wide Golf Course Rating Process.

A user must still have all the knowledge currently used in Rating. But this App records all inputs, provides position info,
calculates obstacle values using the rating tables and produces the results in a .csv file.

This App is made up of 3 parts all use Visual Studio:

  W10CRA:            Visual Basic UI + Visual Basic Backing Logic  
  CRAClassLibrary:   W10CRA Visual Basic Backing Logic (.Net Standard)  
  MobileCRA:         Xamarin UI in Xaml and C# + CRAClassLibrary  

Any change to the W10CRA "Backing Logic" is added to the CRAClassLibrary the result is included in MobileCRA resources.

As of 5/9/2021 MobileCRA is only available on Android. Don't have access to an Apple machine at this time. 

An older version of Windows CRA is in the Microsoft Store accessed only with a direct link (at request of USGA).
W10CRA has a UI change, fixes and other improvements.

Both W10CRA and MobileCRA are built and available on Visual Studio App Center. (GitHub Login)

Note: As of 9/20/2021 the name W10CRA in the Apps was changed to WinCRA.
