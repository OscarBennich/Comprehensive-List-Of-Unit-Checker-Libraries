# A Comprehensive List of Unit Checker Libraries
## Table of Contents
- [Short description of the project](#short-description)
- [Data gathering information](#data-gathering-information)
- [Top tier libraries](#top-tier-libraries)
- [Second tier libraries](#second-tier-libraries)
- [Tools and applications](#tools)
- [All projects](#all-projects)

## Short description 
In the spring of 2018 I (Oscar Bennich-Björkman) wrote my master thesis as part of my degree in Information Systems at Uppsala University. The main part of this thesis involved a comprehensive and systematic analysis of libraries related to the handling of physical quantities or units of measurement. The end result of this study was a group of what I chose to call 'top tier' libraries, which are the best and most well-developed libraries for a range of different programming languages. 

Me and my supervisor (Steve McKeever) also remade the core of this thesis into a paper which is to be published in the ACM Journals in conjunction with being presented at the 2018 ACM SIGPLAN International Conference on Software Language Engineering (https://conf.researchr.org/track/sle-2018/papers#About). 

This GitHub repository is primarily provided as a way of giving easy access to this data for anyone looking for a library of this kind, as this type of database did not exist prior to this study. Secondarily, this database is a way of making the data more transparent for any reader of either the paper or the thesis. 

The most relevant results of the study (the top tier group) is presented first in this repository as this is what is of interest to most readers, but the later sections present the rest of the data in its entirety. 

If you have any questions or thoughts you can contact me at: oscar.bennich@gmail.com

If you would like to read more, the master thesis can be found here: http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-353817 
and the paper can be found here: [...]

## Data gathering information
The data presented here was gathered from seven sites, using eight different keywords. More detailed information about this process can be found in either the thesis or the paper. The sites and keywords are found below. 

| Site Name  | Site Link |
| ------------- | ------------- |
| GitHub.com | https://github.com/ |
| Bit-Bucket.org | https://bitbucket.org/ |
| GitLab.com  | https://about.gitlab.com/  |
| SourceForge.net  | https://sourceforge.net/ |
| CodeProject.com  | https://www.codeproject.com/ |
| LaunchPad.net  | https://launchpad.net/  |
| Savannah.gnu.org  | http://savannah.gnu.org/ |

| Keyword  |
| ------------- |
| “Units of Measure”   |
| “Units Measure Converter” |
| “Units”  |
| “Unit Converter”  |
| “Quantities”  |
|  “Conversion”  |
|  “Unit Conversion”  |
|  “Physical Units”  |

## Library Data
The data presented here is categorised as follows; The top tier libraries (the best examples) are presented first. For this group, the amount of units that the library natively supports is also shown. After that the second tier libraries are presented, these libraries are of varying quality but are lacking compared to the top tier group. Then the projects that I have categorised as 'Tools' are presented. These projects fit into the general area of unit of measurement checking but are not libraries. This can for example be a dimension checking console application. The top tier libraries, second tier libraries, and tools together make up the 'Valid Project' group, referenced in the thesis and the paper. 

Lastly, for the sake of transparency, the full dataset is presented. This gives anyone the chance to double check my analysis or make their own analysis without having to gather the data again. 

## Top tier libraries 
| Name | Language | Amount of units/constants/prefixes supported | Source / URL |
|---------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| UnitsNet | C# | 600+ units (including prefixes) | https://github.com/angularsen/UnitsNet |
| Quantity System | C# | 300+ units | https://github.com/ibluesun/QuantitySystem |
| Quantity Types | C# | 300+ units | https://github.com/objorke/QuantityTypes |
| Working with Units and Amounts | C# | 70+ units, 16 constants | https://www.codeproject.com/Articles/611731/Working-with-Units-and-Amounts |
| RedStar.Amounts | C# | ~80 units, 16 constants | https://github.com/petermorlion/RedStar.Amounts/ |
| Cubico | C# | ~140 units | https://github.com/irperez/Cubico |
| Using physical quantities and units of measure in C# programs | C# | ~100 units | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |
| UnitParser | C# | ~300 units | https://www.codeproject.com/Articles/1211504/UnitParser |
| Fhir.Metrics | C# | ~150 units, 24 prefixes | https://github.com/FirelyTeam/Fhir.Metrics |
| Gu.Units | C# | ~50 units | https://github.com/JohanLarsson/Gu.Units |
| CSUnits | C# | 500+ units (including prefixes) | https://github.com/cureos/csunits |
| Convertinator | C# | ~20 units | https://github.com/hartez/Convertinator |
| CaliperSharp | C# | 132 units, 16 constants, 23 prefixes | https://github.com/point85/CaliperSharp |
| Pint | Python | 300+ units, 20 constants, 27 prefixes | https://github.com/hgrecco/pint |
| Scimath | Python | 300+ units | https://github.com/enthought/scimath |
| Quantities | Python | 300+ units, 28 prefixes | https://github.com/python-quantities/python-quantities |
| Astropy | Python | ~150 units, 35 constants | https://github.com/astropy/astropy |
| Efficient Scalars in Python | Python | ~150 units | http://russp.us/scalar-python.htm |
| ParamPy | Python | 50+ units, 16 prefixes | https://github.com/matthewwardrop/python-parampy |
| Pyvalem | Python | 70+ units | https://github.com/xnx/pyqn |
| Quantiphy | Python | ~40 units, 19 prefixes, 19 constants | https://github.com/KenKundert/quantiphy |
| Misu | Python | ~450 units, 20 prefixes | https://github.com/cjrh/misu |
| Aegon | Python | 150+ units | https://github.com/lukaskollmer/aegon |
| BoostUnits | C++ | ~200 units, 20 prefixes, ~150 constants | https://github.com/boostorg/units/ |
| Units | C++ | ~150 units, 22 prefixes | https://github.com/nholthaus/units |
| PhysUnits | C++ | 100+ units, 7 constants, 28 prefixes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| Units | C++ | ~30 units, 330+ constants, 14 prefixes | https://github.com/tonypilz/units |
| Units and measures for C++ 11 | C++ | ~50 units | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |
| Ruby Units | Ruby | ~150 units, 30 prefixes | https://github.com/olbrich/ruby-units |
| Unitwise | Ruby | 300+ units | https://github.com/joshwlewis/unitwise |
| SY | Ruby | 30+ units, ~10 constants | https://github.com/boris-s/sy |
| Units-Ruby | Ruby | 74 units, 5 prefixes | https://github.com/bfoz/units-ruby |
| Uom | Ruby | 63 units | https://github.com/caruby/uom |
| Quantity | Ruby | ~40 units, 25 prefixes, | https://github.com/bhuga/quantity |
| Alchemist | Ruby | 500+ units, 88 prefixes | https://github.com/halogenandtoast/alchemist |
| Unit_Soup | Ruby | 0 units preloaded? | https://github.com/rutvij47/unit_soup |
| Phys-Units | Ruby | 2300+ units, 85 prefixes | https://github.com/masa16/phys-units |
| Flowsnake | JavaScript | 650+ units | https://github.com/Eldelshell/flowsnake |
| JS-quantities | JavaScript | ~150 units, 30 prefixes | https://github.com/gentooboontoo/js-quantities |
| Mezur | JavaScript | ~100 units | https://github.com/guyisra/mezur |
| Unitz | JavaScript | ~70 units | https://github.com/ClickerMonkey/unitz |
| Units by Stak Digital | JavaScript | ~50 units | https://github.com/stak-digital/units |
| Unit API - JSR 385 | Java | 30+ units, 28 prefixes | https://github.com/unitsofmeasurement/unit-api |
| Caliper | Java | ~130 units,  23 prefixes, 16 constants | https://github.com/point85/caliper |
| SI-Units | Java | 120+ units, 4 constants | https://github.com/unitsofmeasurement/si-units |
| JSR 363 | Java | 35 units | https://jcp.org/en/jsr/detail?id=363 |
| Efficient Scalars in Scala | Scala | ~150 units | http://russp.us/scalar-scala.htm |
| Squants | Scala | ~300 units, 28 prefixes | https://github.com/typelevel/squants |
| Coulomb | Scala | ~70 units, 28 prefixes | https://github.com/erikerlandson/coulomb |
| SI -- A Scala Library of Units of Measurement | Scala | ~50 units, 20 prefixes | https://gitlab.com/h2b/SI |
| Scala-units | Scala | ~120 units | https://github.com/bwkimmel/scala-units |
| PHP Units of Measure | PHP | ~100 units | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |
| UnitConverter | PHP | 130+ units | https://github.com/nfraz007/UnitConverter |
| Convertor | PHP | 70+ units | https://github.com/olifolkerd/convertor |
| UOM-Plugin | Haskell | 0 units preloaded | https://github.com/adamgundry/uom-plugin |
| Dimensional | Haskell | ~200 units, 21 prefixes | https://github.com/bjornbm/dimensional|
| Quantities | Haskell | 200+ units, 28 prefixes, 3 constants | https://github.com/jdreaver/quantities |
| Physical Units for Matlab | MatLab | 800+ units | https://github.com/sky-s/physical-units-for-matlab |
| Quantities | MatLab | 200+ units, 28 prefixes, 18 constants | https://github.com/mikofski/Quantities |
| UnitKit | Swift | 100+ units | https://github.com/otaviocc/UnitKit |
| MKUnits | Swift | 80 units | https://github.com/michalkonturek/MKUnits |
| Units | Multiple | 65 units, 70 constants | https://github.com/saroad2/units |
| PHYSICS | Multiple | ~190 units, 25 prefixes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |
| Units 2 | Clojure | ~45 units, 28 prefixes | https://github.com/mfey/units2 |
| EiffelUnits | Eiffel | ~100 units, 21 prefixes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Unitful.jl | Julia | ~170 units, 50 prefixes, 21 constants | https://github.com/ajkeller34/Unitful.jl |
| Quantities | Idris | ~200 units, 24 prefixes | https://github.com/timjb/quantities |
| Elixir Unit Converter | Elixir | 60+ units | https://github.com/carturoch/ex_uc |
| Units of Measure (#2) | Kotlin | 350+ units | https://github.com/kunalsheth/units-of-measure |
| Quantities | D | ~50 units, 20 prefixes | https://github.com/biozic/quantities |
| Measures with Dimensions | Racket | ~150 units, 20 prefixes | https://github.com/AlexKnauth/measures-with-dimensions |
| Uncodium.Units | F# | ~350 units, 28 prefixes, ~50 constants | https://github.com/stefanmaierhofer/Uncodium.Units |
| Dimensioned | Rust | ~450 units & constants (hard to differentiate) | https://github.com/paholg/dimensioned |
| FURY | Fortran | ? | https://github.com/szaghi/FURY |
| PhysicalQuantities | Common Lisp | ~40 units, 28 prefixes | https://github.com/mrossini-ethz/physical-quantities |
| Units of measurement for Ada | Ada | 100+ units, 20 prefixes | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |
| Red-units | Red | 960 units, 1100+ constants, 100+ prefixes | https://gitlab.com/maxvel/red-units |
| PPX_Measure | OCalm | 0 units preloaded. Generates a lot of code from simple commands instead (see documentation) | https://github.com/xvw/ppx_measure |
| Purescript-Quantities | PureScript | ~100 units, 23 prefixes, 14 constants | https://github.com/sharkdp/purescript-quantities |
| Lua-Physical | Lua | ~150 units, 10 prefixes, 21 constants | https://github.com/tjenni/lua-physical |
| Units | Tcl | 60 units, 21 prefixes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Measurement Units for R | R | Has 0 preloaded units itself, uses other Library "UDUNITS-2" for this | https://github.com/r-quantities/units/ |

## Second tier libraries 
| Name | Language | Source / URL |
|------------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| Convert Units | Java | https://github.com/ben-ng/convert-units |
| Unit  | Go | https://github.com/martinlindhe/unit |
| UnitConversionLib | C# | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| Natu | Python | https://github.com/kdavies4/natu |
| Buckingham | Python | https://github.com/mdipierro/buckingham |
| Magnitude  | Python | https://github.com/juanre/magnitude |
| Units | Python | https://bitbucket.org/adonohue/units |
| Unum | Python | https://bitbucket.org/kiv/unum |
| CF_Units | Python | https://github.com/SciTools/cf_units |
| DimPy | Python | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| Units of Measure | C# | https://archive.codeplex.com/?p=unitsofmeasure |
| Physical Measure | C# | https://github.com/KiloBravoLima/PhysicalMeasure |
| NGenericDimensions | C# | https://github.com/MafuJosh/NGenericDimensions |
| Quantities.net | C# | https://sourceforge.net/projects/quantitiesnet/ |
| .NET Unit Conversion Library | C# | https://sourceforge.net/projects/unitcon/ |
| Measurement Unit Conversion Library  | C# | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Unit of Measure Library for .NET | C# | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Unit of Measure Validator for C# | C# | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Units of Measurement Systems | Java | https://github.com/unitsofmeasurement/uom-systems |
| Units | Java | https://github.com/SamCarlberg/units |
| Units | C# | https://github.com/engineers-tools/Units |
| PHP Unit Conversion | PHP | https://github.com/pimlie/php-unit-conversion |
| The Units of Measure Library | C++ | https://sourceforge.net/projects/tuoml/ |
| Metric | Rust | https://github.com/coder543/metric |
| ScalaU | Scala | https://github.com/adrianfr/scalau |
| Units | Go | https://github.com/smyrman/units |
| Superquants | Scala | https://github.com/rudogma/scala-superquants |
| Metric | Nim | https://github.com/mjendrusch/metric |
| Units D | D | https://github.com/nordlow/units-d |
| Units and Measurements | Racket | https://github.com/Metaxal/measures |
| SIUnits | Haskell | https://github.com/joewkr/SIUnits |
| Physikal | Kotlin | https://github.com/Tenkiv/Physikal |
| Engineering | C# | https://github.com/zhofre/engineering |
| ProgParam | C++ | https://github.com/qPCR4vir/ProgParam |
| InkUnits | Swift | https://github.com/angelsolaorbaiceta/InkUnits |
| Ruby Units | Ruby | https://github.com/olbrich/ruby-units |
| SwiftMeasurement | Swift | https://github.com/ken0nek/SwiftMeasurement |
| JNum | Java | https://github.com/attipaci/jnum |
| MagickScience | C++ | https://github.com/Iarfen/MagickScience |
| Unit.py | Python | https://github.com/fabian0010/Unit.py |
| Libquantify | C++ | https://github.com/damianorenfer/libquantify |
| Constants and Units | MatLab | https://github.com/mariomerinomartinez/constants_and_units |
| UOM-Domain | Java | https://github.com/unitsofmeasurement/uom-domain |
| Units | C# | https://github.com/LabyrinthApps/Units |
| Scale | Swift | https://github.com/onmyway133/Scale |
| SIConv | Haskell | https://github.com/owainlewis/conventional-si-unit-converter |
| Convert | Swift | https://github.com/danielbyon/Convert |
| Converter (#1) | PHP | https://github.com/cartalyst/converter |
| Quantify | Ruby | https://github.com/spatchcock/quantify |
| UOM | Ruby | https://github.com/madriska/uom |
| VUnits | Java | https://github.com/vaslabs/vunits |
| PhysicalQuantities (#2) | C# | https://github.com/timdetering/PhysicalQuantities |
| PhysicalQuantities (#5) | Haskell | https://github.com/fehu/PhysicalQuantities |
| Python-Physical | Python | https://github.com/EdwinChan/python-physical |
| PhysicalValue | Swift | https://github.com/antonvmironov/PhysicalValue |
| Lathexa Units | JavaScript | https://github.com/lethexa/lethexa-units |
| Units.jl | Julia | https://github.com/autocorr/Units.jl |
| Units | Go | https://github.com/zn8nz/units |
| AutoUnits | C++ | https://github.com/Fifty-Nine/AutoUnits |
| Physical Math | Python | https://github.com/matthagy/physmath |
| Dimanalyser | Java | https://github.com/cymi/dimanalyser |
| Dftu | C++ | https://github.com/triblatron/dftu |
| Physcon | Python | https://github.com/georglind/physcon |
| Units-v2 | C++ | https://github.com/Corristo/units-v2 |
| UDUnits | Julia | https://github.com/Alexander-Barth/UDUnits.jl |
| Quantity.Net | C# | https://github.com/bcachet/Quantity.Net |
| UnitManipulationLibrary | C++ | https://github.com/OuaisBla/UnitManipulationLibrary |
| Dimension-TF | Haskell | https://github.com/nushio3/dimensional-tf |
| Phys-Types | C++ | https://github.com/akubera/phys_types |
| Unit | C++/CMake/Python | https://github.com/njoy/unit |
| ValueWithUnit | C# | https://github.com/vbfox/ValueWithUnit |
| o2scl | C | https://github.com/awsteiner/o2scl |
| Decibel Units of Measurement with C# Framework | C# | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |
| Quantities, Units, and Values: An Object Oriented Implementation | C | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |
| Automatic Conversion of Physical Units | C# | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |
| TCX Unit Conversion Library | C++ | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |
| Measurement Unit Conversion Library (#2) | C# | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |
| International System of Units Notation | C# | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |
| Converting a value to an SI Unit String | C# | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |
| Unit Management Framework | Java | https://sourceforge.net/projects/quantitymanager/?source=directory |
| UOM Conversion Library | Java | https://sourceforge.net/projects/uomcl/?source=directory |
| NumericalChameleon | Java | https://sourceforge.net/projects/numchameleon/?source=directory |
| Libunits | C | https://sourceforge.net/projects/libunits/?source=directory |
| Quantities | C++ | https://sourceforge.net/projects/quantity/?source=directory |
| Magnitude | Java | https://sourceforge.net/projects/magnitude/?source=directory |
| PyPhys Class Library | Python | https://sourceforge.net/projects/pyphys/?source=directory |
| Physical | C++ | https://sourceforge.net/projects/physical/?source=directory |
| mcs::units | C++ | https://sourceforge.net/projects/mcs-units/?source=directory |
| Quan | C++ | https://sourceforge.net/projects/quan/?source=directory |
| Unum | Python | https://sourceforge.net/projects/unum/?source=directory |
| puny | Python | https://sourceforge.net/projects/puny/?source=directory |
| JQuantity: Precision Math Java Framework | Java | https://sourceforge.net/projects/jquantity/?source=directory |
| Java library and framework: quantity | Java | https://sourceforge.net/projects/javaquantity/?source=directory |
| PhysicalUnits | C++ | https://sourceforge.net/projects/physicalunits/?source=directory |
| QUDAL | C++ | https://sourceforge.net/projects/qudal/?source=directory |
| C++ Unit Library | C++ | https://sourceforge.net/projects/cppunitlibrary/?source=directory |
| UnitsC++ | C++ | https://sourceforge.net/projects/unitscpp/?source=directory |
| C++ Units | C++ | https://sourceforge.net/projects/cppunits/?source=directory |
| Unit Var | Python | https://sourceforge.net/projects/unitvar/?source=directory |
| Java Measure | Java | https://sourceforge.net/projects/javameasure/?source=directory |
| Python Unit Conversion Library | Python | https://sourceforge.net/projects/pythonconvert/?source=directory |
| .NET Unit Conversion Library | C# | https://sourceforge.net/projects/unitcon/?source=directory |
| .NET Units of Measure | C# | https://bitbucket.org/Thecentury/.net-units-of-measure |
| Measurement.js | JavaScript | https://github.com/Philzen/measurement.js |
| UnitsKit | Objective-C | https://github.com/stevemoser/UnitsKit |
| Units-of-Measure (#1) | Scala | https://github.com/Mononofu/Units-of-Measure |
| Units | Rust | https://github.com/Boddlnagg/units |
| FSharp.Units | F# | https://github.com/putridparrot/FSharp.Units |
| Units | Scala | https://github.com/nestorpersist/units |
| Python-Units-Of-Measure | Python | https://github.com/katerina7479/python-units-of-measure |
| IMT.Units | Java | https://github.com/imt-ag/imt.units-java |
| PHPMeasures | PHP | https://github.com/dcabanaw/phpMeasures |
| PHP-Units | PHP | https://github.com/hiqdev/php-units |
| Cuis-Smalltalk-Aconcagua | Smalltalk | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| Measurements | PHP | https://github.com/marfurt/measurements |
| UnitsOfMeasureBundle | PHP | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| UnitsOfMeasure | C# | https://github.com/capnmidnight/UnitsOfMeasure |
| Units | PHP | https://github.com/ARCANEDEV/Units |
| Units_of_measure | C++ | https://github.com/Skeen/units_of_measure |
| Units | Go | https://github.com/antha-lang/units |
| Units of Measure Prototype | Haskell | https://github.com/adamgundry/uom-prototype |
| Uom.Dart | Dart | https://github.com/damondouglas/uom.dart |
| RockUnits | C# | https://github.com/gareth-reid/RockUnits |
| TundraMeasure.java | Java | https://github.com/Permafrost/TundraMeasure.java |
| Units | PHP | https://github.com/marando/Units |
| UnitOfMeasure (#1) | C# | https://github.com/Chef-Code/UnitOfMeasure |
| Units-api | PHP | https://github.com/shrimpza/units-api |
| cppDegRad | C++ | https://github.com/grahamboree/cppDegRad |
| Unit| VB .NET | https://github.com/AdamSpeight2008/Unit |
| Simple.Units | C# | https://github.com/oriches/Simple.Units |
| Class-Measure | Perl | https://github.com/bluefeet/Class-Measure |
| Measurements | Ruby | https://github.com/Krustal/Measurements |
| Purescript-Units | PureScript | https://github.com/fluffynukeit/purescript-units |
| GenUnits | F# | https://github.com/halcwb/GenUnits |
| Ruby-Units | Ruby | https://github.com/davearonson/Ruby-Units |
| JavaMeasure | Java | https://github.com/tkuebler/JavaMeasure |
| AS3Units | ActionScript | https://github.com/erussell/AS3Units |
| PHPConverter | PHP | https://github.com/chapmang/PHPConverter |
| NGX-UOM | JavaScript | https://github.com/catellanir/ngx-uom |
| Physical Quantities | Smalltalk/C# | https://github.com/timdetering/PhysicalQuantities |
| GIM.Quantities | C# | https://github.com/togakangaroo/GIM.Quantities |
| JUNitConv | Java | https://github.com/duckler/JUnitConv |
| Dimensional | Ruby | https://github.com/cch1/Dimensional |
| UnitOfMeasure (#2) | Scala | https://github.com/ricemery/unitofmeasure |
| Umpy | Python | https://github.com/perdixsw/umpy |
| SBUnits | Swift | https://github.com/EBGToo/SBUnits |
| Units | Haskell | https://github.com/goldfirere/units |
| DDUnitConverter | Objective-C | https://github.com/davedelong/DDUnitConverter |
| PHP-Conversion | PHP | https://github.com/crisu83/php-conversion |
| SIUnitX | TeX | https://github.com/josephwright/siunitx |
| Units | Scala | https://github.com/KarolS/units |
| SI-Units | Java | https://github.com/unitsofmeasurement/si-units |
| Conversion| PHP | https://github.com/abhimanyu003/conversion |
| UnitConverter| Python | https://github.com/mattgd/UnitConverter |
| Unit-converter | PHP | https://github.com/jordanbrauer/unit-converter |
| HHUnitConverter | Objective-C | https://github.com/HiveHicks/HHUnitConverter |
| Angular-Unit-Converter | JavaScript | https://github.com/alexandernst/angular-unit-converter |
| UnitConverterWin | C | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| UnitConversion | Objective-C | https://github.com/unixpickle/UnitConversion |
| Cropio_Units_Converter | C++ | https://github.com/cropio/cropio_units_converter |
| Quantity | Ruby | https://github.com/bhuga/quantity |
| UDUNITS-2 | C | https://github.com/Unidata/UDUNITS-2 |
| Quantities | Swift | https://github.com/BradLarson/Quantities |
| PhysicalQuantities | Python | https://github.com/juhasch/PhysicalQuantities |
| Quantities | R | https://github.com/r-quantities/quantities |
| ScientificQuantities | C++ | https://github.com/nourani/ScientificQuantities |
| Physical-Quantities | Python | https://github.com/hplgit/physical-quantities |
| ScalaQuantity | Scala | https://github.com/zzorn/ScalaQuantity |
| Quantities | C++ | https://github.com/djbarker/quantities |
| Quantity | Ruby | https://github.com/aportnov/quantity |
| Quantities | Batchfile | https://github.com/greatfriends/Quantities |
| Quantities | C# | https://github.com/atmoos/Quantities |
| Physics-Measurement | JavaScript | https://github.com/victorpotasso/physics-measurement |
| PyQuantity | Python | https://github.com/gabbpuy/PyQuantity |
| Sundew.Quantities | C# | https://github.com/hugener/Sundew.Quantities |
| Meteor-Quantities | JavaScript | https://github.com/luzlab/meteor-quantities |
| Quantity | Clojure | https://github.com/spellman/quantity |
| Convert-Quantities | JavaScript | https://github.com/kendru/convert-quantities |
| UnitConversion | C# | https://github.com/gkampolis/UnitConversion |
| Convert.js | JavaScript | https://github.com/YazilimMuhendisiyizBiz/convert.js |
| MeasureBundle | PHP | https://github.com/akeneo/MeasureBundle |
| Convertr | R | https://github.com/ropenscilabs/convertr |
| Metric | Java | https://github.com/gnapse/metric |
| Jsunitconverter | JavaScript | https://github.com/jerodvenemafm/jsunitconverter |
| Sius | Java | https://github.com/mbe24/sius |
| Unit | JavaScript | https://github.com/smartcar/unit |
| Unit-formula | Common Lisp | https://github.com/Ramarren/unit-formula |
| Node-units | JavaScript | https://github.com/brettlangdon/node-units |
| Units.js | JavaScript | https://github.com/jairtrejo/units.js |
| Units | C++ | https://github.com/lonkamikaze/units |
| Unit.styl | JavaScript | https://github.com/diessica/unit.styl |
| Conversionr | R | https://github.com/alexnakagawa/conversionr |
| Math-units | Perl | https://github.com/kenfox/Math-Units |
| UnitConvert | JavaScript | https://github.com/agnoster/unitology |
| NGunits | Java | https://github.com/erussell/ngunits |
| Units | Swift | https://github.com/chrisjeane/Units |
| UnitConversion (#3) | Python | https://github.com/UnitConversion/unitConversion |
| Metiri | JavaScript | https://github.com/GCheung55/metiri |
| Convert-units | Ruby | https://github.com/tanvir002700/convert_unit |
| Django-Unit-Field | Python | https://github.com/kohout/django-unit-field |
| Units | PHP | https://github.com/rmasters/units |
| Unit_Conversion | Ruby | https://github.com/eternal44/unit_conversion |
| Maegor | JavaScript | https://github.com/lukaskollmer/maegor |
| Units-System | Ruby | https://github.com/jgoizueta/units-system |
| Physical | C++ | https://github.com/olsonse/physical |
| Conversion (#6) | C++ | https://github.com/simonmeaden/conversion |
| Gorilla | Ruby | https://github.com/stephencelis/gorilla |
| QtUnits | C++ | https://github.com/hrobeers/QtUnits |
| Units | Ruby | https://github.com/woahdae/units |
| convertR | R | https://github.com/colin-fraser/convertR |
| UnitConversion (#4) | C# | https://github.com/Mecteral/UnitConversion |
| JSR 275 | Java | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| Quantified | Ruby | https://github.com/Shopify/quantified |
| Units | Haskell | https://hackage.haskell.org/package/units |

## Tools
| Name | Language | Source / URL |
|-------------------------------------------------------------------------|-------------------|--------------------------------------------------------------------------------------------|
| Phriky-Units | Python | https://github.com/unl-nimbus-lab/phriky-units |
| ParamPool | Python | https://github.com/hplgit/parampool |
| NumericalUnits | Python | https://github.com/sbyrnes321/numericalunits |
| Rink | Rust | https://github.com/tiffany352/rink-rs |
| Insect | PureScript | https://github.com/sharkdp/insect |
| Units | JavaScript | https://github.com/dohliam/units |
| Smart Units | Sidef | https://github.com/trizen/smart-units |
| Chimp | Python | https://github.com/mhetrerajat/chimp |
| XamConverter | C# | https://github.com/brminnick/XamConverter |
| UnitConverter | Java | https://github.com/nevack/UnitConverter |
| Convertee | JavaScript | https://github.com/isquaredcreative/Convertee |
| Conversion Calculator | C++ | https://github.com/dtuivs/Converter |
| M2py | Python/Matlab | https://github.com/caiorss/m2py |
| Scaler | Shell | https://github.com/emugel/scaler |
| Praktool | Python | https://github.com/zombofant/praktool |
| qMetrics | C++ | https://launchpad.net/qmetrics |
| SimpleUnitConverter | C | https://launchpad.net/simpleunitconverter |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | C# | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |
| Libre Unit Conveter | C# | https://sourceforge.net/projects/libreunitconverter/?source=directory |
| ConvertAll | Python | https://sourceforge.net/projects/convertall/?source=directory |
| JFX Konwerter | Java | https://sourceforge.net/projects/jfx-konwerter/?source=directory |
| Unit Converter | Scratch | https://sourceforge.net/projects/unitconverter12/?source=directory |
| MAIA Unit Converter | C++ | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Unit Conveter | C# | https://sourceforge.net/projects/unitconversion/?source=directory |
| Converter | Java | https://sourceforge.net/projects/con-vert/?source=directory |
| LibreEngineering | Python | https://sourceforge.net/projects/libreeng/ |
| UNeedIT Converter | C# | https://sourceforge.net/projects/uneedconverter/?source=directory |
| Unit Converter | Python | https://sourceforge.net/projects/unit-converter/?source=directory |
| Portable Unit Converter | JavaScript | https://sourceforge.net/projects/puc/?source=directory |
| Web Unit Converter | C# | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| ChemicalA | C++ | https://sourceforge.net/projects/chemicala/?source=directory |
| Computing with Units | Java | https://sourceforge.net/projects/units-in-java/?source=directory |
| EngineeringCalculator | C++ | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| Quick Unit Converter | Java | https://sourceforge.net/projects/qunitconverter/?source=directory |
| Unit Converter | REBOL | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| ConverTo | C++ | https://sourceforge.net/projects/converto/?source=directory |
| UConverter | Java | https://sourceforge.net/projects/uconverter/?source=directory |
| GodSend | PHP | https://sourceforge.net/projects/godsend/?source=directory |
| JConvert | Java | https://sourceforge.net/projects/jconvert/?source=directory |
| SIMConverter | C# | https://sourceforge.net/projects/simconverter/?source=directory |
| Esos | C++ | https://sourceforge.net/projects/esos/?source=directory |
| Punits - Pluggable units | C | https://sourceforge.net/projects/punits/?source=directory |
| BeConverter | C++ | https://bitbucket.org/Teknomancer/beconverter |
| Unit | Java | https://bitbucket.org/hansolo/unit |
| Unit-converter (#1) | Python | https://bitbucket.org/brayvasq/unit-converter |
| Physics | Python | https://bitbucket.org/hppavilion1/physics |
| Frinj | Clojure | https://github.com/martintrojer/frinj |
| Converter | Java | https://github.com/samWson/converter |
| SimpleMeasurementConverter | Java | https://github.com/michaelstoops/SimpleMeasurementConverter |
| Converter | C++ | https://github.com/dtalaba/convertor |
| Frins | Scala | https://github.com/martintrojer/frins |
| MeasurementConverter | Java | https://github.com/SBrooks75/MeasurementConverter |
| UnitConverter | Java | https://github.com/MarioDudjak/UnitConverter |
| Maser | JavaScript/Python | https://github.com/justinbangerter/maser |
| JC-Units | Python | https://github.com/jason0x43/jc-units |
| UnitConverterUltimate | Java | https://github.com/physphil/UnitConverterUltimate |
| Units | Java | https://github.com/xxv/Units |
| Unit-Converter | JavaScript | https://github.com/TheMarco/Unit-Converter |
| Alfred-Converter | Python | https://github.com/WoLpH/alfred-converter |
| UnitConverter.htm | JavaScript | https://github.com/iterami/UnitConverter.htm |
| UnitConverter | Java | https://github.com/impateljay/UnitConverter |
| Unit-Converter | Java | https://github.com/AmitKumarSah/Unit-Converter |
| PythonUnitConverter | Python | https://github.com/Aaron1011/PythonUnitConverter |
| Converter| Java | https://github.com/HanSolo/converter |
| Mather | Java | https://github.com/icasdri/Mather |
| Vandelay | C++ | https://github.com/HaikuArchives/Vandelay |
| Unit-Converter | PHP | https://github.com/b-sebastian/unit-converter |
| Unit-Converter | C++ | https://github.com/mikeleppane/Unit-Converter |
| Unit-Converter | JavaScript | https://github.com/MaicolBen/unit-converter |
| Unit | PHP | https://github.com/pounard/Unit |
| Converter | C++ | https://github.com/KerryL/Converter |
| Angular-Converter | JavaScript | https://github.com/cyrilf/angular-converter |
| PreciseUnitConverter | JavaScript | https://github.com/bumxu/PreciseUnitConverter |
| Converter | TypeScript | https://github.com/ialex90/Converter |
| DakaUnitConverter | Java | https://github.com/darrylfonseka/DakaUnitConverter |
| Convertor | C++ | https://github.com/mihaelateo/Convertor |
| Converter | C++ | https://github.com/scruff3y/Converter |
| Unit-Converter | JavaScript | https://github.com/GTLook/Unit-Converter |
| UnitMan | C# | https://github.com/mbeloshapkin/UnitMan |
| PyUnitConverter | Python | https://github.com/jyri78/PyUnitConverter |
| All_In_One_Converter | Python | https://github.com/pradeepjairamani/All_in_one_converter |
| ConverterApp | C# | https://github.com/halezmo/ConverterApp |
| Alfred-Convert | Python | https://github.com/deanishe/alfred-convert |
| Xiny | Go | https://github.com/bcicen/xiny |
| GenUnitApp | JavaScript | https://github.com/halcwb/GenUnitApp |
| Unitconverter-Android | Java | https://github.com/dbrant/unitconverter-android |
| Unit_Conversion | Python | https://github.com/bastihaase/unit_conversion |
| UnitConversion | Java | https://github.com/yfl007/UnitConversion |
| Unit-Conversion | JavaScript | https://github.com/srimanthk/unit-conversion |
| GNU Units | C# | https://www.gnu.org/software/units/ |

## All projects
| Name | Language | Valid project? | Source / URL |
|-----------------------------------------------------------------------------------------------------------------------------|-------------------|----------------|-------------------------------------------------------------------------------------------------|
| .NET Unit Conversion Library | Python | Yes | https://github.com/unl-nimbus-lab/phriky-units |
| .NET Unit Conversion Library | C# | Yes | https://github.com/angularsen/UnitsNet |
| .NET Units of Measure | Python | Yes | https://github.com/hplgit/parampool |
| A look at the Boost Units Library | C++ | Yes | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |
| Aegon | Java | Yes | https://github.com/ben-ng/convert-units |
| Alchemist | C++ | Yes | https://github.com/nholthaus/units |
| Alfred-Convert | Go | Yes | https://github.com/martinlindhe/unit |
| Alfred-Converter | Python | Yes | https://github.com/hgrecco/pint |
| All Unit Converter | C# | Yes | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| All_In_One_Converter | Eiffel | Yes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Angular-Converter | Python | Yes | https://github.com/kdavies4/natu |
| Angular-Unit-Converter | Python | Yes | https://github.com/mdipierro/buckingham |
| Application of C++11 User-Defined Literals to Handling Scientific Quantities, Number Representation and String Manipulation | Python | Yes | https://github.com/juanre/magnitude |
| AS3Units | Python | Yes | https://bitbucket.org/adonohue/units |
| Astropy | Python | Yes | https://bitbucket.org/kiv/unum |
| Automatic Conversion of Physical Units | Python | Yes | https://github.com/enthought/scimath |
| AutoUnits | Python | Yes | https://github.com/python-quantities/python-quantities |
| Aviation Tool | Python | No | https://github.com/blazetopher/udunitspy |
| BeConverter | Python | Yes | https://github.com/astropy/astropy |
| BGConverter | Python | Yes | https://github.com/SciTools/cf_units |
| BoostUnits | Python | Yes | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| Buckingham | Python | Yes | https://github.com/sbyrnes321/numericalunits |
| C++ Unit Library | Scala | Yes | http://russp.us/scalar-scala.htm |
| C++ Units | Python | Yes | http://russp.us/scalar-python.htm |
| C0nv3rt3r | C# | Yes | https://archive.codeplex.com/?p=unitsofmeasure |
| Caliper | C# | Yes | https://github.com/mangh/unitsofmeasurement |
| CaliperSharp | C# | Yes | https://github.com/KiloBravoLima/PhysicalMeasure |
| Cerebro Converter | C# | Yes | https://github.com/ibluesun/QuantitySystem |
| CF_Units | C# | Yes | https://github.com/objorke/QuantityTypes |
| ChemicalA | C# | Yes | https://github.com/MafuJosh/NGenericDimensions |
| Chimp | C# | Yes | https://sourceforge.net/projects/quantitiesnet/ |
| Class-Measure | C# | Yes | https://sourceforge.net/projects/unitcon/ |
| Comment-Units | C# | Yes | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Complete Unit Conversion Sample in C# .NET | C# | Yes | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Computing with Units | C# | Yes | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Constants and Units | C# | Yes | https://www.codeproject.com/script/Articles/ListVersions.aspx?aid=611731 |
| Converge | C# | Yes | https://www.gnu.org/software/units/ |
| Conversion | C# | Yes | https://github.com/petermorlion/RedStar.Amounts/ |
| Conversion  | Java | Yes | https://github.com/unitsofmeasurement/uom-systems |
| Conversion  | C# | Yes | https://github.com/point85/CaliperSharp |
| Conversion | Java | Yes | https://github.com/SamCarlberg/units |
| Conversion  | C# | Yes | https://github.com/engineers-tools/Units |
| Conversion | C# | Yes | https://github.com/irperez/Cubico |
| Conversion | Julia | Yes | https://github.com/ajkeller34/Unitful.jl |
| Conversion Calculator | PHP | Yes | https://github.com/pimlie/php-unit-conversion |
| ConversionApp2 | C++ | Yes | https://sourceforge.net/projects/tuoml/ |
| Conversionr | Scala | Yes | https://github.com/typelevel/squants |
| ConversionsApp | Idris | Yes | https://github.com/timjb/quantities |
| Convert | Rust | Yes | https://github.com/tiffany352/rink-rs |
| Convert | Java | Yes | https://github.com/unitsofmeasurement/unit-api |
| Convert Units (#1) | C++ | Yes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| Convert-Quantities | Scala | Yes | https://github.com/erikerlandson/coulomb |
| Convert-units | Rust | Yes | https://github.com/coder543/metric |
| Convert.js | Scala | Yes | https://github.com/adrianfr/scalau |
| ConvertAll | Go | Yes | https://github.com/smyrman/units |
| Convertee | Scala | Yes | https://github.com/rudogma/scala-superquants |
| Converter | Elixir | Yes | https://github.com/carturoch/ex_uc |
| Converter | Nim | Yes | https://github.com/mjendrusch/metric |
| Converter | Kotlin | Yes | https://github.com/kunalsheth/units-of-measure |
| Converter | C++ | Yes | https://github.com/tonypilz/units |
| Converter | D | Yes | https://github.com/nordlow/units-d |
| Converter  | D | Yes | https://github.com/biozic/quantities |
| Converter  | Racket | Yes | https://github.com/AlexKnauth/measures-with-dimensions |
| Converter | Racket | Yes | https://github.com/Metaxal/measures |
| Converter  | Java | No | https://www.openhub.net/p/jucl |
| Converter | Multiple | Yes | https://github.com/saroad2/units |
| Converter  | Java | Yes | https://github.com/point85/caliper |
| Converter | F# | Yes | https://github.com/stefanmaierhofer/Uncodium.Units |
| Converter  | C# | No | http://jamesnewkirk.typepad.com/posts/nunit_converter_v11.html |
| Converter  | PHP | Yes | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |
| Converter  | Haskell | Yes | https://github.com/joewkr/SIUnits |
| Converter  | Kotlin | Yes | https://github.com/unitsofmeasurement/Physikal |
| Converter  | C# | Yes | https://github.com/zhofre/engineering |
| Converter | C++ | Yes | https://github.com/qPCR4vir/ProgParam |
| Converter  | Swift | Yes | https://github.com/angelsolaorbaiceta/InkUnits |
| Converter  | C | No | https://github.com/nithjino/UnitConverter |
| Converter | JavaScript | Yes | https://github.com/Eldelshell/flowsnake |
| Converter  | Ruby | No | https://github.com/christinach/unit |
| Converter | PureScript | Yes | https://github.com/sharkdp/insect |
| Converter  | Ruby | Yes | https://github.com/olbrich/ruby-units |
| Converter | JavaScript | Yes | https://github.com/gentooboontoo/js-quantities |
| Converter | Rust | Yes | https://github.com/paholg/dimensioned |
| Converter | Swift | Yes | https://github.com/ken0nek/SwiftMeasurement |
| Converter  | JavaScript | No | https://github.com/anthonydugois/fp-units |
| Converter | Clojure | Yes | https://github.com/mfey/units2 |
| Converter | JavaScript | Yes | https://github.com/dohliam/units |
| Converter | Sidef | Yes | https://github.com/trizen/smart-units |
| Converter Application | JavaScript | No | https://github.com/gkjohnson/scientific-javascript |
| Converter_Classes | Java | Yes | https://github.com/attipaci/jnum |
| ConverterApp | JavaScript | No | https://github.com/KELiON/cerebro-converter |
| Convertinator | C++ | Yes | https://github.com/Iarfen/MagickScience |
| Converting a value to an SI Unit String | Ruby | Yes | https://github.com/joshwlewis/unitwise |
| ConverTo | Haskell | No | https://github.com/irreverent-pixel-feats/quantity |
| Convertor | Python | Yes | https://github.com/fabian0010/Unit.py |
| Convertor | Python | Yes | https://github.com/mhetrerajat/chimp |
| Convertoroid | C++ | No | https://github.com/OMGtechy/Cue |
| Convertr | C++ | Yes | https://github.com/damianorenfer/libquantify |
| convertR | MatLab | Yes | https://github.com/mariomerinomartinez/constants_and_units |
| Coulomb | Java | No | https://github.com/echocat/units4j |
| cppDegRad | Java | Yes | https://github.com/unitsofmeasurement/uom-domain |
| Cropio_Units_Converter | JavaScript | No | https://github.com/cdbusby/run-convert |
| CSharp-UnitsOfMeasure | C# | Yes | https://github.com/LabyrinthApps/Units |
| CSUnits | Swift | Yes | https://github.com/onmyway133/Scale |
| Cubico | C# | Yes | https://github.com/brminnick/XamConverter |
| Cue | Java | Yes | https://github.com/nevack/UnitConverter |
| Cuis-Smalltalk-Aconcagua | JavaScript | No | https://github.com/ozgrozer/trevor |
| Currency | Haskell | Yes | https://github.com/owainlewis/conventional-si-unit-converter |
| DakaUnitConverter | Swift | Yes | https://github.com/danielbyon/Convert |
| DDUnitConverter | Python | No | https://github.com/rootinchase/tempconvert |
| Decibel Units of Measurement with C# Framework | JavaScript | Yes | https://github.com/isquaredcreative/Convertee |
| Dftu | PHP | Yes | https://github.com/cartalyst/converter |
| Dimanalyser | C++ | Yes | https://github.com/dtuivs/Converter |
| Dimension-TF | Go | No | https://github.com/yanndr/temperature |
| Dimensional | Ruby | Yes | https://github.com/spatchcock/quantify |
| Dimensional | Ruby | Yes | https://github.com/boris-s/sy |
| DimensionalAnalysis | Fortran | Yes | https://github.com/szaghi/FURY |
| Dimensioned | Common Lisp | Yes | https://github.com/mrossini-ethz/physical-quantities |
| DimPy | Ruby | Yes | https://github.com/madriska/uom |
| Django-Unit-Field | C++ | No | https://github.com/Jajauma/SIUnits |
| Easyunits-rs | MatLab | Yes | https://github.com/sky-s/physical-units-for-matlab |
| Efficient Scalars in Python | Java | Yes | https://github.com/vaslabs/vunits |
| Efficient Scalars in Scala | F# | No | https://github.com/kainous/PhysicalUnits |
| EiffelUnits | Python | No | https://github.com/DanielSank/units |
| Elixir Unit Converter | C# | Yes | https://github.com/timdetering/PhysicalQuantities |
| Elm-tunits | Scala | No | https://github.com/ppiotrow/physical-units |
| Elm-Units | Python | No | https://github.com/ppfaff/PhysicalQuantities |
| Engineering | C++ | No | https://github.com/grafwolg/UnitsOfMeasurement |
| EngineeringCalculator | C# | No | https://github.com/Traquina/PhysicalQuantities |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | Haskell | Yes | https://github.com/fehu/PhysicalQuantities |
| Esos | Python | Yes | https://github.com/EdwinChan/python-physical |
| Ethereumjs-units | Swift | Yes | https://github.com/antonvmironov/PhysicalValue |
| EveryConverter | Julia | No | https://github.com/sclereid/Units.jl |
| Fan measure | JavaScript | Yes | https://github.com/lethexa/lethexa-units |
| Fhir.Metrics | Julia | Yes | https://github.com/autocorr/Units.jl |
| Flowsnake | Python/Matlab | Yes | https://github.com/caiorss/m2py |
| FP Units | Go | Yes | https://github.com/zn8nz/units |
| Frinj | C++ | Yes | https://github.com/Fifty-Nine/AutoUnits |
| Frins | C++ | No | https://github.com/rdlabspl/PhysUnits |
| FSharp.Units | Python | No | https://github.com/d0cod3r/physicalQuantitis |
| FURY | Python | No | https://github.com/ypsilus/mensura |
| Gas Flow Unit Conversion | Python | Yes | https://github.com/matthagy/physmath |
| GenUnitApp | Java | Yes | https://github.com/cymi/dimanalyser |
| GenUnits | C++ | Yes | https://github.com/triblatron/dftu |
| GIM.Quantities | Shell | Yes | https://github.com/emugel/scaler |
| GNU Units | Rust | No | https://github.com/willi-kappler/comment_units |
| GodSend | Python | Yes | https://github.com/georglind/physcon |
| Gorilla | Python | Yes | https://github.com/zombofant/praktool |
| Grobid-Quantities | C++ | Yes | https://github.com/Corristo/units-v2 |
| Groovy-Unitconverter | Julia | Yes | https://github.com/Alexander-Barth/UDUnits.jl |
| Gu.Units | C# | Yes | https://github.com/bcachet/Quantity.Net |
| Hazpy.Unit-conversion | Elm | No | https://github.com/gyulalaszlo/elm-tunits |
| HHUnitConverter | Python/PowerShell | No | https://github.com/rpalo/wox-unit-converter |
| Imp Converter | Python | Yes | https://github.com/matthewwardrop/python-parampy |
| Imperial & Metric Converter | C++ | Yes | https://github.com/OuaisBla/UnitManipulationLibrary |
| IMT.Units | Haskell | Yes | https://github.com/nushio3/dimensional-tf |
| InkUnits | C++ | Yes | https://github.com/akubera/phys_types |
| Insect | C++/CMake/Python | Yes | https://github.com/njoy/unit |
| International System of Units Notation | Python | Yes | https://github.com/xnx/pyqn |
| Java library and framework: quantity | C# | Yes | https://github.com/vbfox/ValueWithUnit |
| Java Measure | Swift | Yes | https://github.com/otaviocc/UnitKit |
| Java Numbers with Unit | C++ | No | https://github.com/erdavila/SI |
| Java Unit Conversion Library | C++ | Yes | https://launchpad.net/qmetrics |
| JavaMeasure | C | Yes | https://launchpad.net/simpleunitconverter |
| JC-Units | C | Yes | https://github.com/awsteiner/o2scl |
| JConvert | C++ | Yes | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |
| JFX Konwerter | C# | Yes | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |
| JNum | C# | Yes | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |
| JQuantity: Precision Math Java Framework | C++ | No | https://www.codeproject.com/Articles/791511/Units-of-measurement-types-in-Cplusplus-Using-comp |
| JS-quantities | C# | Yes | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |
| JS-Quantities | C | Yes | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |
| JSR 275 | C# | Yes | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |
| JSR 363 | C# | Yes | https://www.codeproject.com/Articles/30569/Unit-Conversions-in-C-WPF |
| Jsunitconverter | C++ | No | https://www.codeproject.com/Articles/988932/Boost-Units-Library |
| JUNitConv | C++ | Yes | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |
| KingConverter | C# | Yes | https://www.codeproject.com/Articles/22470/Complete-Unit-Conversion-Sample-in-C-NET |
| Ktunits | C# | Yes | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |
| Kuants | C# | Yes | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |
| Lathexa Units | C# | Yes | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |
| Libquantify | C# | Yes | https://www.codeproject.com/Tips/1005796/Validation-Dimensions-of-Physical-Quantities-NET |
| Libre Unit Conveter | C++ | Yes | https://www.codeproject.com/Articles/447922/Application-of-Cplusplus-User-Defined-Literals-t |
| LibreEngineering | Ada | Yes | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |
| Libunits | Java | Yes | https://sourceforge.net/projects/quantitymanager/?source=directory |
| Lua-Physical | C# | No | https://sourceforge.net/projects/measure/?source=directory |
| M2py | Java | Yes | https://sourceforge.net/projects/uomcl/?source=directory |
| Maegor | C# | Yes | https://www.codeproject.com/Articles/1211504/UnitParser |
| MagickScience | Python | No | https://sourceforge.net/projects/converter-application/?source=directory |
| Magnitude (#1) | C# | Yes | https://sourceforge.net/projects/libreunitconverter/?source=directory |
| Magnitude (#2) | Python | Yes | https://sourceforge.net/projects/convertall/?source=directory |
| MAIA Unit Converter | Java | Yes | https://sourceforge.net/projects/numchameleon/?source=directory |
| Maser | Java | Yes | https://sourceforge.net/projects/jfx-konwerter/?source=directory |
| Math-units | C | No | https://sourceforge.net/projects/temp-unit-converter/?source=directory |
| Mather | Scratch | Yes | https://sourceforge.net/projects/unitconverter12/?source=directory |
| mcs::units | C++ | Yes | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Measure | C# | Yes | https://sourceforge.net/projects/unitconversion/?source=directory |
| Measure | JavaScript | No | https://sourceforge.net/projects/xvertr/?source=directory |
| Measure.js | Java | No | https://sourceforge.net/projects/unitsconverter/?source=directory |
| MeasureBundle | VB .NET | No | https://sourceforge.net/projects/exconverter/?source=directory |
| Measured | Java | Yes | https://sourceforge.net/projects/con-vert/?source=directory |
| Measurement Unit Conversion Library | Python | Yes | https://sourceforge.net/projects/libreeng/ |
| Measurement Unit Conversion Library | C# | Yes | https://sourceforge.net/projects/uneedconverter/?source=directory |
| Measurement with units | VB .NET | No | https://sourceforge.net/projects/aviationtool/?source=directory |
| Measurement_Converter | PHP | No | https://sourceforge.net/projects/phpunitconvert/?source=directory |
| Measurement.js | C | No | https://sourceforge.net/projects/specon/?source=directory |
| MeasurementConverter | Python | Yes | https://sourceforge.net/projects/unit-converter/?source=directory |
| Measurements | JavaScript | Yes | https://sourceforge.net/projects/puc/?source=directory |
| Measurements | C++ | No | https://sourceforge.net/projects/windunitsconver/?source=directory |
| Measures and Units | C | Yes | https://sourceforge.net/projects/libunits/?source=directory |
| Measures with Dimensions | C# | Yes | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| Memory_Units | Python | No | https://sourceforge.net/projects/gas-flow-unit-conversion/?source=directory |
| Mensura | C++ | Yes | https://sourceforge.net/projects/chemicala/?source=directory |
| Meshy-quantities | Pascal | No | https://sourceforge.net/projects/puma-repository/?source=directory |
| Meteor-Quantities | Java | No | https://sourceforge.net/projects/jnumwu/?source=directory |
| Metiri | C++ | No | https://sourceforge.net/projects/qsas/?source=directory |
| Metric | Java | No | https://sourceforge.net/projects/rssfiz/?source=directory |
| Metric | Java | Yes | https://sourceforge.net/projects/units-in-java/?source=directory |
| Metric | Java | No | https://sourceforge.net/projects/everyconverter/?source=directory |
| Mezur | C++ | Yes | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| MilesMeter | Java | No | https://sourceforge.net/projects/ultimatecalculator/?source=directory |
| Misu | Java | Yes | https://sourceforge.net/projects/qunitconverter/?source=directory |
| MKUnits | PHP | No | https://sourceforge.net/projects/stgmunitconvert/?source=directory |
| Natu | REBOL | Yes | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| NGenericDimensions | C++ | No | https://sourceforge.net/projects/impconvert/?source=directory |
| NGunits | C++ | Yes | https://sourceforge.net/projects/converto/?source=directory |
| NGX-UOM | Java | Yes | https://sourceforge.net/projects/uconverter/?source=directory |
| Nim-Units | C++ | Yes | https://sourceforge.net/projects/quantity/?source=directory |
| Node-units | Java | Yes | https://sourceforge.net/projects/magnitude/?source=directory |
| NUCOS | Python | Yes | https://sourceforge.net/projects/pyphys/?source=directory |
| NumericalChameleon | C++ | Yes | https://sourceforge.net/projects/physical/?source=directory |
| NumericalUnits | C++ | Yes | https://sourceforge.net/projects/mcs-units/?source=directory |
| NUnitConverter | C++ | Yes | https://sourceforge.net/projects/quan/?source=directory |
| o2scl | C | No | https://sourceforge.net/projects/units/?source=directory |
| Ocalm-units | Python | Yes | https://sourceforge.net/projects/unum/?source=directory |
| Open.Measuring | Python | Yes | https://sourceforge.net/projects/puny/?source=directory |
| ParamPool | Java | Yes | https://sourceforge.net/projects/jquantity/?source=directory |
| ParamPy | PHP | Yes | https://sourceforge.net/projects/godsend/?source=directory |
| PHP Unit Conversion | Java | Yes | https://sourceforge.net/projects/javaquantity/?source=directory |
| PHP Unit Converter | C++ | Yes | https://sourceforge.net/projects/physicalunits/?source=directory |
| PHP Units of Measure | C++ | Yes | https://sourceforge.net/projects/qudal/?source=directory |
| PHP-Conversion | Python | No | https://sourceforge.net/projects/dimensionalanalysis/?source=directory |
| PHP-Units | C++ | No | https://sourceforge.net/projects/scientificlib/?source=directory |
| PHPConverter | C++ | Yes | https://sourceforge.net/projects/cppunitlibrary/?source=directory |
| PHPMeasures | C++ | Yes | https://sourceforge.net/projects/unitscpp/?source=directory |
| Phriky-Units | C++ | Yes | https://sourceforge.net/projects/cppunits/?source=directory |
| Phys-Types | Java | Yes | https://sourceforge.net/projects/jconvert/?source=directory |
| Physcon | Python | Yes | https://sourceforge.net/projects/unitvar/?source=directory |
| Physical | C# | Yes | https://sourceforge.net/projects/simconverter/?source=directory |
| Physical | Java | Yes | https://sourceforge.net/projects/javameasure/?source=directory |
| Physical Math | C++ | Yes | https://sourceforge.net/projects/esos/?source=directory |
| Physical Measure | C | Yes | https://sourceforge.net/projects/punits/?source=directory |
| Physical Quantities | Python | Yes | https://sourceforge.net/projects/pythonconvert/?source=directory |
| Physical Units for Matlab | C# | Yes | https://sourceforge.net/projects/unitcon/?source=directory |
| Physical-Quantities | Scala | Yes | https://gitlab.com/h2b/SI |
| Physical-Quantities | Red | Yes | https://gitlab.com/maxvel/red-units |
| Physical-Units | C++ | No | https://gitlab.com/eclufsc/eda/units |
| PhysicalQuantities | Rust | No | https://gitlab.com/imp/easyunits-rs |
| PhysicalQuantities | C# | Yes | https://bitbucket.org/Thecentury/.net-units-of-measure |
| PhysicalQuantities | Fan | No | https://bitbucket.org/qualidafial/fan-measure |
| PhysicalQuantities | C++ | Yes | https://bitbucket.org/Teknomancer/beconverter |
| PhysicalQuantities | Java | Yes | https://bitbucket.org/hansolo/unit |
| PhysicalQuantities | Go | No | https://bitbucket.org/ede/units |
| PhysicalQuantities | Python | Yes | https://bitbucket.org/brayvasq/unit-converter |
| PhysicalQuantities | Python | No | https://bitbucket.org/johanhake/units |
| PhysicalUnits | JavaScript | No | https://bitbucket.org/sergespaolonzi/unit-converter |
| PhysicalUnits | Java | No | https://bitbucket.org/Chawakorn_A/all-unit-converter |
| PhysicalValue | Java | No | https://bitbucket.org/cpresley/unit-converter-application |
| Physics | Python | No | https://bitbucket.org/meshy/meshy-quantities/src |
| PHYSICS | Python | Yes | https://bitbucket.org/kiv/unum |
| Physics-Measurement | C# | No | https://bitbucket.org/MADc0d3r/unitconverterpublic |
| Physikal  | Python | Yes | https://bitbucket.org/hppavilion1/physics |
| Physikal | JavaScript | Yes | https://github.com/Philzen/measurement.js |
| PhysUnits  | Clojure | Yes | https://github.com/martintrojer/frinj |
| PhysUnits | Objective-C | Yes | https://github.com/stevemoser/UnitsKit |
| Pint | Haskell | Yes | https://github.com/adamgundry/uom-plugin |
| Portable Unit Converter | Scala | Yes | https://github.com/Mononofu/Units-of-Measure |
| PPX_Measure | Rust | Yes | https://github.com/Boddlnagg/units |
| Praktool | C# | Yes | https://github.com/FirelyTeam/Fhir.Metrics |
| PreciseUnitConverter | F# | Yes | https://github.com/putridparrot/FSharp.Units |
| ProgParam | Scala | Yes | https://github.com/nestorpersist/units |
| PUMA Repository | Ruby | Yes | https://github.com/bfoz/units-ruby |
| Punits - Pluggable units | Python | Yes | https://github.com/katerina7479/python-units-of-measure |
| puny | OCalm | Yes | https://github.com/xvw/ppx_measure |
| Purescript-Quantities | Java | Yes | https://github.com/imt-ag/imt.units-java |
| Purescript-Units | Java | No | https://github.com/KinYee/Measurement_Converter |
| PyPhys Class Library | Java | Yes | https://github.com/samWson/converter |
| PyQuantity | Java | Yes | https://github.com/michaelstoops/SimpleMeasurementConverter |
| Python Quantities | C++ | Yes | https://github.com/dtalaba/convertor |
| Python Unit Conversion Library | C++ | No | https://github.com/Shaddox/UnitConverter |
| Python-Physical | Java | No | https://github.com/ThanasiG/unit-converter |
| Python-Units-Of-Measure | Scala | Yes | https://github.com/martintrojer/frins |
| PythonUnitConverter | PHP | Yes | https://github.com/dcabanaw/phpMeasures |
| PyUnitConverter | PHP | Yes | https://github.com/hiqdev/php-units |
| Pyvalem | Smalltalk | Yes | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| qMetrics | PHP | Yes | https://github.com/marfurt/measurements |
| QSAS | C# | No | https://github.com/hediet/csharp-UnitsOfMeasure |
| QtUnits | C++ | No | https://github.com/ing200086/UnitsOfMeasure |
| Quan | PHP | Yes | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| Quant | C# | Yes | https://github.com/capnmidnight/UnitsOfMeasure |
| Quantified | C++ | No | https://github.com/printfn/UnitsOfMeasure |
| Quantify | PHP | Yes | https://github.com/ARCANEDEV/Units |
| Quantiphy | C++ | Yes | https://github.com/Skeen/units_of_measure |
| Quantities | Go | Yes | https://github.com/antha-lang/units |
| Quantities | Haskell | Yes | https://github.com/adamgundry/uom-prototype |
| Quantities | Perl | No | https://github.com/bluefeet/Measure |
| Quantities | Dart | Yes | https://github.com/damondouglas/uom.dart |
| Quantities | Java | No | https://github.com/timroejr/2.05-Units-of-Measurement |
| Quantities | F# | No | https://github.com/benhamner/UnitsDotNet |
| Quantities | C# | Yes | https://github.com/gareth-reid/RockUnits |
| Quantities | Java | Yes | https://github.com/Permafrost/TundraMeasure.java |
| Quantities | PHP | Yes | https://github.com/marando/Units |
| Quantities | C# | Yes | https://github.com/Chef-Code/UnitOfMeasure |
| Quantities  | PHP | Yes | https://github.com/shrimpza/units-api |
| Quantities  | C++ | Yes | https://github.com/grahamboree/cppDegRad |
| Quantities-Comparison | C++ | No | https://github.com/AndrewWasHere/measurements_with_units |
| Quantities, Units, and Values: An Object Oriented Implementation | VB .NET | Yes | https://github.com/AdamSpeight2008/Unit |
| Quantities.jl | Haskell | No | https://github.com/adamgundry/units-parser |
| Quantities.net | C# | Yes | https://github.com/oriches/Simple.Units |
| QuantitiesLib | Perl | Yes | https://github.com/bluefeet/Class-Measure |
| Quantity | Ruby | Yes | https://github.com/Krustal/Measurements |
| Quantity | PureScript | Yes | https://github.com/fluffynukeit/purescript-units |
| Quantity | Swift | No | https://github.com/sdrpa/measure |
| Quantity | JavaScript | Yes | https://github.com/guyisra/mezur |
| Quantity | JavaScript | No | https://github.com/alnesjo/measure.js |
| Quantity System | Elm | No | https://github.com/irpagnossin/units |
| Quantity Types | PHP | No | https://github.com/komparu/unit |
| Quantity.Net | Java | Yes | https://github.com/SBrooks75/MeasurementConverter |
| QUDAL | Ruby | Yes | https://github.com/caruby/uom |
| Quick Unit Converter | F# | Yes | https://github.com/halcwb/GenUnits |
| Rails-Units | Ruby | Yes | https://github.com/davearonson/Ruby-Units |
| RealizedQuantities | Java | Yes | https://github.com/tkuebler/JavaMeasure |
| Red-units | ActionScript | Yes | https://github.com/erussell/AS3Units |
| RedStar.Amounts | Java | Yes | https://github.com/MarioDudjak/UnitConverter |
| Rink | TypeScript | No | https://github.com/electricessence/Open.Measuring |
| RockUnits | Ruby | No | https://github.com/gschool-g5/converter_classes |
| Rssfiz | PHP | Yes | https://github.com/chapmang/PHPConverter |
| Ruby Units | JavaScript | Yes | https://github.com/catellanir/ngx-uom |
| Ruby-Units | Smalltalk/C# | Yes | https://github.com/timdetering/PhysicalQuantities |
| Run-Convert | C# | Yes | https://github.com/togakangaroo/GIM.Quantities |
| SBUnits | Java | Yes | https://github.com/duckler/JUnitConv |
| Scala-Quantities | Kotlin | No | https://github.com/evacchi/kuants |
| Scala-units | Ruby | Yes | https://github.com/cch1/Dimensional |
| ScalaQuantity | JavaScript/Python | Yes | https://github.com/justinbangerter/maser |
| ScalaU | Scala | Yes | https://github.com/ricemery/unitofmeasure |
| Scale | Python | Yes | https://github.com/perdixsw/umpy |
| Scaler | Swift | Yes | https://github.com/EBGToo/SBUnits |
| Scientific Javascript | Haskell | Yes | https://github.com/goldfirere/units |
| Scientific Library | JavaScript | No | https://github.com/heygrady/Units |
| ScientificQuantities | Swift | Yes | https://github.com/michalkonturek/MKUnits |
| Scimath | Python | Yes | https://github.com/jason0x43/jc-units |
| SI | Julia | No | https://github.com/Keno/SIUnits.jl |
| SI -- A Scala Library of Units of Measurement | Go | No | https://github.com/alecthomas/units |
| SI-Units | C# | Yes | https://github.com/JohanLarsson/Gu.Units |
| SIConv | Objective-C | Yes | https://github.com/davedelong/DDUnitConverter |
| Silphid.Unity | C# | Yes | https://github.com/cureos/csunits |
| SIMConverter | PHP | Yes | https://github.com/crisu83/php-conversion |
| Simple-Unit-Converter | TeX | Yes | https://github.com/josephwright/siunitx |
| Simple.Units | Scala | Yes | https://github.com/KarolS/units |
| SimpleMeasurementConverter | Java | Yes | https://github.com/physphil/UnitConverterUltimate |
| SimpleUnitConverter | Java | Yes | https://github.com/unitsofmeasurement/si-units |
| SIUnits (#1) | Ruby | Yes | https://github.com/Shopify/measured |
| SIUnits (#2) | Java | Yes | https://github.com/xxv/Units |
| SIUnits.jl | PHP | Yes | https://github.com/abhimanyu003/conversion |
| SIUnitX | Python | Yes | https://github.com/mattgd/UnitConverter |
| Sius | Java | No | https://github.com/sommukhopadhyay/UnitConverter |
| Smart Units | PHP | Yes | https://github.com/jordanbrauer/unit-converter |
| Spectroscopist's Energy Converter | Objective-C | Yes | https://github.com/HiveHicks/HHUnitConverter |
| Squants | JavaScript | Yes | https://github.com/TheMarco/Unit-Converter |
| Sundew.Quantities | Python | Yes | https://github.com/WoLpH/alfred-converter |
| Superquants | JavaScript | Yes | https://github.com/ClickerMonkey/unitz |
| SwiftMeasurement | JavaScript | No | https://github.com/war1025/Unit-Converter |
| SY | JavaScript | Yes | https://github.com/iterami/UnitConverter.htm |
| tConverter | Java | Yes | https://github.com/impateljay/UnitConverter |
| TCX Unit Conversion Library | JavaScript | Yes | https://github.com/alexandernst/angular-unit-converter |
| TempConvert | C | Yes | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| Temperature | Java | No | https://github.com/MarcKuniansky/UnitConverter |
| Temperature Unit Converter | Java | Yes | https://github.com/AmitKumarSah/Unit-Converter |
| TemperatureConverter | Python | Yes | https://github.com/Aaron1011/PythonUnitConverter |
| The Quantity Library | Java | Yes | https://github.com/HanSolo/converter |
| The Units of Measure Library | Java | Yes | https://github.com/icasdri/Mather |
| Trevor | C++ | Yes | https://github.com/HaikuArchives/Vandelay |
| TundraMeasure.java | PHP | Yes | https://github.com/b-sebastian/unit-converter |
| UConverter | C++ | No | https://github.com/stevenharradine/Converter |
| UDUnits | C++ | Yes | https://github.com/mikeleppane/Unit-Converter |
| UDUNITS-2 | Java | No | https://github.com/Ideally/UnitConverter |
| Udunitspy | C++ | No | https://github.com/BoboTiG/unit-converter |
| UltimateCalculator | PHP | No | https://github.com/tankotun/tConverter |
| Umpy | C# | No | https://github.com/kolesnikova745/units-converter |
| Uncodium.Units | Java | No | https://github.com/fnk0/UnitConverter |
| UNeedIT Converter | Java | No | https://github.com/khaldi-yass/Converter |
| UniCon | HTML | No | https://github.com/Bingde/unit |
| Unisum | JavaScript | Yes | https://github.com/MaicolBen/unit-converter |
| Unit | Python | No | https://github.com/Demoleas715/UnitConverter |
| Unit | JavaScript | No | https://github.com/smtaydemir/simple-unit-converter |
| Unit | Objective-C | Yes | https://github.com/unixpickle/UnitConversion |
| Unit | PHP | Yes | https://github.com/nfraz007/UnitConverter |
| Unit | Java | No | https://github.com/sunilthalore/UnitConverter |
| Unit  | PHP | Yes | https://github.com/pounard/Unit |
| Unit | Objective-C | No | https://github.com/milkyNik/Converter |
| Unit  | Java | No | https://github.com/hirenj0009/converter |
| Unit  | Swift | No | https://github.com/dhunten/Converter |
| Unit  | C++ | Yes | https://github.com/KerryL/Converter |
| Unit API | JavaScript | Yes | https://github.com/cyrilf/angular-converter |
| Unit Conversion Wox Plugin | HTML | No | https://github.com/annaavanesyan/converter |
| Unit Conversions in C#/WPF | JavaScript | No | https://github.com/Urrby/Converter |
| Unit Converter | PureScript | No | https://github.com/moniyax/converter |
| Unit Converter  | Java | No | https://github.com/NaOHman/Converter |
| Unit Converter  | Java | No | https://github.com/sunil512/Converter |
| Unit Converter  | JavaScript | No | https://github.com/angeshpokharel/unit-converter.js |
| Unit Converter | Java | No | https://github.com/jessepasos/Converter |
| Unit Converter Application | JavaScript | Yes | https://github.com/bumxu/PreciseUnitConverter |
| Unit Conveter | C++ | Yes | https://github.com/cropio/cropio_units_converter |
| Unit Conveter using PHP and HTML | JavaScript | No | https://github.com/zlargon/converter |
| Unit Management Framework | C# | No | https://github.com/sun-haha/Converter |
| Unit of Measure Library for .NET | JavaScript | No | https://github.com/ziggy42/Converter |
| Unit of Measure Validator for C# | Java | No | https://github.com/SurajPrasadd/Converter |
| Unit Var | Python | No | https://github.com/hpjardon/converter |
| Unit_Conversion | C# | No | https://github.com/torifat/C0nv3rt3r |
| Unit_Conversion | Java | No | https://github.com/napnie/converter |
| Unit_Converter | Clojure | No | https://github.com/andreasfrom/converter |
| Unit_Soup | TypeScript | Yes | https://github.com/ialex90/Converter |
| Unit-Conversion | Java | Yes | https://github.com/darrylfonseka/DakaUnitConverter |
| Unit-Conversion | Python | No | https://github.com/XTremeRox/converter |
| Unit-converter | Java | No | https://github.com/davoraleksic/UniCon |
| Unit-Converter | Swift | No | https://github.com/mirokolodii/milesmeter |
| Unit-Converter | JavaScript | No | https://github.com/jgalla/unit-converter |
| Unit-converter | Vue | No | https://github.com/askhat/unisum |
| Unit-Converter | Ruby | No | https://github.com/samuels410/unit_converter |
| Unit-converter  | PHP | No | https://github.com/anstag/units |
| Unit-Converter | Java | No | https://github.com/abhii2028/Convertoroid |
| Unit-converter  | C++ | Yes | https://github.com/mihaelateo/Convertor |
| Unit-Converter  | C++ | Yes | https://github.com/scruff3y/Converter |
| Unit-Converter | Java | No | https://github.com/urielvan/converter |
| Unit-Converter | HTML | No | https://github.com/AmitBuchnik/Converter |
| Unit-Converter | Objective-C | No | https://github.com/basicsbeauty/UnitConverter |
| Unit-Converter | Groovy | No | https://github.com/rhyolight/groovy-unitconverter |
| Unit-Converter.js | JavaScript | Yes | https://github.com/GTLook/Unit-Converter |
| Unit-formula | JavaScript | No | https://github.com/ryanr1230/KingConverter |
| Unit.py | C# | Yes | https://github.com/mbeloshapkin/UnitMan |
| Unit.styl | C# | No | https://github.com/github-ganesh/UnitConverter |
| UnitComboLib | Python | Yes | https://github.com/jyri78/PyUnitConverter |
| UnitConversion  | Java | No | https://github.com/atsang36/Unit_Converter |
| UnitConversion  | C# | No | https://github.com/pfthroaway/Converter |
| UnitConversion  | Python | No | https://github.com/bobo333/TemperatureConverter |
| UnitConversion  | C++ | No | https://github.com/bugeaggeorge/BGConverter |
| UnitConversion | Ruby | Yes | https://github.com/bhuga/quantity |
| UnitConversion | JavaScript | No | https://github.com/kermitt2/grobid-quantities |
| UnitConversion | C | Yes | https://github.com/Unidata/UDUNITS-2 |
| UnitConversionLib | Python | No | https://github.com/tbekolay/quantities-comparison |
| UnitConvert | PureScript | Yes | https://github.com/sharkdp/purescript-quantities |
| UnitConverter | Haskell | Yes | https://github.com/jdreaver/quantities |
| UnitConverter  | Swift | Yes | https://github.com/BradLarson/Quantities |
| UnitConverter  | Python | Yes | https://github.com/juhasch/PhysicalQuantities |
| UnitConverter | Nim | No | https://github.com/def-/nim-units |
| UnitConverter  | PHP | Yes | https://github.com/phospr/quantity |
| UnitConverter | R | Yes | https://github.com/r-quantities/quantities |
| UnitConverter | Python | Yes | https://github.com/KenKundert/quantiphy |
| UnitConverter | C++ | Yes | https://github.com/nourani/ScientificQuantities |
| UnitConverter | MatLab | Yes | https://github.com/mikofski/Quantities |
| UnitConverter  | Python | Yes | https://github.com/hplgit/physical-quantities |
| UnitConverter  | Scala | Yes | https://github.com/zzorn/ScalaQuantity |
| UnitConverter | Python | Yes | https://github.com/cjrh/misu |
| UnitConverter | Haskell | No | https://github.com/mtesseract/physical-quantities |
| UnitConverter | Lua | Yes | https://github.com/tjenni/lua-physical |
| UnitConverter | Python | Yes | https://github.com/pradeepjairamani/All_in_one_converter |
| Unitconverter-Android | C# | No | https://github.com/isabellaalstrom/QuantitiesLib |
| UnitConverter.htm | C++ | Yes | https://github.com/djbarker/quantities |
| UnitConverterLibrary | Haskell | No | https://github.com/mtesseract/quantities |
| UnitConverterUltimate | Ruby | Yes | https://github.com/aportnov/quantity |
| UnitConverterWin | Batchfile | Yes | https://github.com/greatfriends/Quantities |
| Unitful.jl | JavaScript | No | https://github.com/jdrew1303/quantities |
| UnitKit | C# | Yes | https://github.com/atmoos/Quantities |
| UnitMan | JavaScript | Yes | https://github.com/victorpotasso/physics-measurement |
| UnitManipulationLibrary | Python | No | https://github.com/BayerSe/RealizedQuantities |
| Unitmaster | Python | Yes | https://github.com/gabbpuy/PyQuantity |
| UnitOfMeasure | JavaScript | No | https://github.com/mugendi/js-quantities |
| UnitOfMeasure | Scala | No | https://github.com/Lastik/scala-quantities |
| UnitParser | C# | Yes | https://github.com/halezmo/ConverterApp |
| Units | C# | Yes | https://github.com/hugener/Sundew.Quantities |
| Units | C# | No | https://github.com/cardassianscot/Units |
| Units  | JavaScript | Yes | https://github.com/luzlab/meteor-quantities |
| Units  | Python | No | https://github.com/colecocomo/quant |
| Units | Clojure | Yes | https://github.com/spellman/quantity |
| Units  | JavaScript | Yes | https://github.com/kendru/convert-quantities |
| Units  | C# | No | https://github.com/KorzunK/PhysicalQuantities |
| Units  | Julia | No | https://github.com/ElOceanografo/Quantities.jl |
| Units  | Ruby | Yes | https://github.com/halogenandtoast/alchemist |
| Units  | C# | Yes | https://github.com/gkampolis/UnitConversion |
| Units | Java | No | https://github.com/billthefarmer/currency |
| Units | JavaScript | Yes | https://github.com/YazilimMuhendisiyizBiz/convert.js |
| Units | PHP | Yes | https://github.com/olifolkerd/convertor |
| Units | Swift | No | https://github.com/SwiftEducation/UnitConverter |
| Units | Python | Yes | https://github.com/deanishe/alfred-convert |
| Units | PHP | Yes | https://github.com/akeneo/MeasureBundle |
| Units | R | Yes | https://github.com/ropenscilabs/convertr |
| Units | JavaScript | No | https://github.com/ethereumjs/ethereumjs-units |
| Units | Java | Yes | https://github.com/gnapse/metric |
| Units  | JavaScript | Yes | https://github.com/jerodvenemafm/jsunitconverter |
| Units | Java | Yes | https://github.com/mbe24/sius |
| Units | JavaScript | Yes | https://github.com/smartcar/unit |
| Units | Ruby | No | https://github.com/scpike/rails-units |
| Units | Python | No | https://github.com/NOAA-ORR-ERD/hazpy.unit_conversion |
| Units | Python | No | https://github.com/sugarlabs/convert |
| Units | Kotlin | No | https://github.com/sargunv/ktunits |
| Units | Common Lisp | Yes | https://github.com/Ramarren/unit-formula |
| Units | C# | No | https://github.com/silphid/silphid.unity |
| Units  | Kotlin | No | https://github.com/Tenkiv/Physikal |
| Units | JavaScript | No | https://github.com/NOAA-ORR-ERD/NUCOS |
| Units | JavaScript | Yes | https://github.com/brettlangdon/node-units |
| Units | Go | Yes | https://github.com/bcicen/xiny |
| Units | JavaScript | Yes | https://github.com/jairtrejo/units.js |
| Units | JavaScript | Yes | https://github.com/halcwb/GenUnitApp |
| Units 2 | C++ | Yes | https://github.com/lonkamikaze/units |
| Units and Measurements | Java | Yes | https://github.com/dbrant/unitconverter-android |
| Units and measures for C++ 11 | JavaScript | Yes | https://github.com/diessica/unit.styl |
| Units by Stak Digital | R | Yes | https://github.com/alexnakagawa/conversionr |
| Units Conversion Library | Perl | Yes | https://github.com/kenfox/Math-Units |
| Units D | Swift | No | https://github.com/daneden/Converge |
| Units of Measure | JavaScript | Yes | https://github.com/agnoster/unitology |
| Units of Measure | PHP | No | https://github.com/h4kuna/unit-conversion |
| Units of Measure Prototype | OCalm | No | https://github.com/pelzlpj/ocaml-units |
| Units of Measurement | C# | Yes | https://github.com/hartez/Convertinator |
| Units of measurement for Ada | Java | Yes | https://github.com/erussell/ngunits |
| Units of Measurement Systems | Swift | Yes | https://github.com/chrisjeane/Units |
| Units of measurement types in C++ | Python | Yes | https://github.com/UnitConversion/unitConversion |
| Units_of_measure | JavaScript | Yes | https://github.com/GCheung55/metiri |
| Units-api | Scala | Yes | https://github.com/bwkimmel/scala-units |
| Units-Converter | Ruby | Yes | https://github.com/tanvir002700/convert_unit |
| Units-of-Measure | Go | No | https://github.com/kormoc/unit |
| Units-of-Measure | Python | Yes | https://github.com/kohout/django-unit-field |
| Units-parser | Elm | No | https://github.com/anfelor/elm-units |
| Units-Ruby | Python | Yes | https://github.com/lukaskollmer/aegon |
| Units-System | PHP | Yes | https://github.com/rmasters/units |
| Units-v2 | Ruby | Yes | https://github.com/eternal44/unit_conversion |
| Units.jl | JavaScript | Yes | https://github.com/lukaskollmer/maegor |
| Units.jl | Rust | No | https://github.com/pepyakin/memory_units |
| Units.js | Ruby | Yes | https://github.com/jgoizueta/units-system |
| Units4j | C++ | Yes | https://github.com/olsonse/physical |
| UnitsC++ | Java | No | https://github.com/VaishnavRajesh/conversion |
| UnitsDotNet | Java | No | https://github.com/SoftronixGlobal/Conversion |
| UnitsKit | Java | No | https://github.com/2aredford/Conversion |
| UnitsNet | C++ | Yes | https://github.com/simonmeaden/conversion |
| UnitsOfMeasure | Ruby | Yes | https://github.com/stephencelis/gorilla |
| UnitsOfMeasure | JavaScript | Yes | https://github.com/stak-digital/units |
| UnitsOfMeasure | Java | No | https://github.com/ali-hamad/Conversion |
| UnitsOfMeasureBundle | Java | No | https://github.com/ironwire/Conversion |
| UnitsOfMeasurement | C++ | No | https://github.com/oswjk/unitmaster |
| Unitwise | Objective-C | No | https://github.com/JoeCortopassi/ConversionsApp |
| Unitz | C++ | Yes | https://github.com/hrobeers/QtUnits |
| Unum | Ruby | Yes | https://github.com/rutvij47/unit_soup |
| Unum | Ruby | Yes | https://github.com/woahdae/units |
| Unum | Python | Yes | https://github.com/bastihaase/unit_conversion |
| Uom | R | Yes | https://github.com/colin-fraser/convertR |
| UOM | C# | Yes | https://github.com/Mecteral/UnitConversion |
| UOM Conversion Library | Java | No | https://github.com/yadavparmatma/UnitConversion |
| UOM-Domain | Java | Yes | https://github.com/yfl007/UnitConversion |
| UOM-Plugin | C# | No | https://github.com/vsooraj/UnitsConversion |
| Uom.Dart | JavaScript | Yes | https://github.com/srimanthk/unit-conversion |
| Using physical quantities and units of measure in C# programs | C# | No | https://github.com/Dirkster99/UnitComboLib |
| Validation Dimensions of Physical Quantities .NET | Java | No | https://github.com/dpinero/ConversionApp2 |
| ValueWithUnit | Java | Yes | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| Vandelay | Java | Yes | https://jcp.org/en/jsr/detail?id=363 |
| VUnits | Tcl | Yes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Web Unit Converter | R | Yes | https://cran.r-project.org/web/packages/units/index.html |
| Winds Units Converter | Ruby | Yes | https://github.com/Shopify/quantified |
| Working with Units and Amounts | Haskell | Yes | https://github.com/bjornbm/dimensional |
| XamConverter | Haskell | Yes | https://hackage.haskell.org/package/units |
| Xiny | Multiple | Yes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |
| XVertR - eXtensible units conVERTeR | C++ | No | http://home.xnet.com/~msk/quantity/quantity.html |
