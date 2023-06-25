# CRA
Course Rating Assistant, Automation of the World Wide Golf Course Rating Process.

A user must still have all the knowledge currently used in Rating. But this App records all inputs, provides position info,
calculates obstacle values using the rating tables and produces the results in a .csv file.

This App is made up of 3 parts all use Visual Studio:

  WinCRA:            Visual Basic UI + Visual Basic Backing Logic  
  CRAClassLibrary:   WinCRA Visual Basic Backing Logic (.Net Standard)  
  MobileCRA:         Xamarin UI in Xaml and C# + CRAClassLibrary  

Any change to the WinCRA "Backing Logic" is added to the CRAClassLibrary the result is included in MobileCRA resources.

As of 6/24/2023 MobileCRA is only available on Android. Have no access to an Apple machine at this time. 

An older version of Windows CRA is in the Microsoft Store accessed only with a direct link (at request of USGA).
WinCRA has a UI change, two Rating modes: Orginal and Map Assisted, fixes and other improvements.


