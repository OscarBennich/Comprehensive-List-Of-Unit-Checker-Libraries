# A Comprehensive List of Unit Checker Libraries
## Table of Contents
- [Short description of the project](#short-description)
- [Data gathering information](#data-gathering-information)
- [Top tier libraries](#top-tier-libraries)
- [Second tier libraries](#second-tier-libraries)
- [Tools and applications](#tools)
- [All projects](#valid-projects)

## Short description 
In the spring of 2018 I (Oscar Bennich-Björkman) wrote my master thesis as part of my degree in Information Systems at Uppsala University. The main part of this thesis involved a comprehensive and systematic analysis of libraries related to the handling of physical quantities or units of measurement. The end result of this study was a group of what I chose to call 'top tier' libraries, which are the best and most well-developed libraries for a range of different programming languages. 

Me and my supervisor (Steve McKeever) also remade the core of this thesis into a paper which is to be published in the ACM Journals in conjunction with being presented at the 2018 ACM SIGPLAN International Conference on Software Language Engineering (https://conf.researchr.org/track/sle-2018/papers#About). 

This GitHub repository is primarily provided as a way of giving easy access to this data for anyone looking for a library of this kind, as this type of database did not exist prior to this study. Secondarily, this database is a way of making the data more transparent for any reader of either the paper or the thesis. 

The most relevant results of the study (the top tier group) is presented first in this repository as this is what is of interest to most readers, but the later sections present the rest of the data in its entirety. 

If you have any questions or thoughts you can contact me at: oscar.bennich@gmail.com

If you would like to read more, the master thesis can be found here: http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-353817 
and the paper can be found here: [...]

## Data gathering information
The data presented here was gathered from seven sites, using eight different keywords. More detailed information about this process can be found in either the thesis or the paper. Thee sites and keywords are found below. 

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
The data presented here is categorised as follows; The top tier libraries (the best examples) are presented first. After that the second tier libraries are presented, these libraries are of varying quality but are lacking compared to the top tier group. Then the projects that I have categorised as 'Tools' are presented. These projects fit into the general area of unit of measurement checking but are not libraries. This can for example be a dimension checking console application. The top tier libraries, second tier libraries, and tools together make up the 'Valid Project' group, referenced in the thesis and the paper. 

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
| Quantities (#1) | Python | 300+ units, 28 prefixes | https://github.com/python-quantities/python-quantities |
| Astropy | Python | ~150 units, 35 constants | https://github.com/astropy/astropy |
| Efficient Scalars in Python | Python | ~150 units | http://russp.us/scalar-python.htm |
| ParamPy | Python | 50+ units, 16 prefixes | https://github.com/matthewwardrop/python-parampy |
| Pyvalem | Python | 70+ units | https://github.com/xnx/pyqn |
| Quantiphy | Python | ~40 units, 19 prefixes, 19 constants | https://github.com/KenKundert/quantiphy |
| Misu | Python | ~450 units, 20 prefixes | https://github.com/cjrh/misu |
| Aegon | Python | 150+ units | https://github.com/lukaskollmer/aegon |
| BoostUnits | C++ | ~200 units, 20 prefixes, ~150 constants | https://github.com/boostorg/units/ |
| Units (#1) | C++ | ~150 units, 22 prefixes | https://github.com/nholthaus/units |
| PhysUnits | C++ | 100+ units, 7 constants, 28 prefixes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| Units (#2) | C++ | ~30 units, 330+ constants, 14 prefixes | https://github.com/tonypilz/units |
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
| Dimensional | Haskell | ~200 units, 21 prefixes | https://github.com/bjornbm/dimensional/blob/master/src/Numeric/Units/Dimensional/Quantities.hs |
| Quantities (#2) | Haskell | 200+ units, 28 prefixes, 3 constants | https://github.com/jdreaver/quantities |
| Physical Units for Matlab | MatLab | 800+ units | https://github.com/sky-s/physical-units-for-matlab |
| Quantities (#3) | MatLab | 200+ units, 28 prefixes, 18 constants | https://github.com/mikofski/Quantities |
| UnitKit | Swift | 100+ units | https://github.com/otaviocc/UnitKit |
| MKUnits | Swift | 80 units | https://github.com/michalkonturek/MKUnits |
| Units (#3) | Multiple | 65 units, 70 constants | https://github.com/saroad2/units |
| PHYSICS | Multiple | ~190 units, 25 prefixes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |
| Units 2 | Clojure | ~45 units, 28 prefixes | https://github.com/mfey/units2 |
| EiffelUnits | Eiffel | ~100 units, 21 prefixes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Unitful.jl | Julia | ~170 units, 50 prefixes, 21 constants | https://github.com/ajkeller34/Unitful.jl |
| Quantities (#4) | Idris | ~200 units, 24 prefixes | https://github.com/timjb/quantities |
| Elixir Unit Converter | Elixir | 60+ units | https://github.com/carturoch/ex_uc |
| Units of Measure (#2) | Kotlin | 350+ units | https://github.com/kunalsheth/units-of-measure |
| Quantities (#5) | D | ~50 units, 20 prefixes | https://github.com/biozic/quantities |
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
| Units (#4) | Tcl | 60 units, 21 prefixes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Measurement Units for R | R | Has 0 preloaded units itself, uses other Library "UDUNITS-2" for this | https://github.com/r-quantities/units/ |

## Second tier libraries 
| Name | Language | Source / URL |
|------------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| Convert Units (#1) | Java | https://github.com/ben-ng/convert-units |
| Unit (#1) | Go | https://github.com/martinlindhe/unit |
| UnitConversionLib | C# | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| Natu | Python | https://github.com/kdavies4/natu |
| Buckingham | Python | https://github.com/mdipierro/buckingham |
| Magnitude (#1) | Python | https://github.com/juanre/magnitude |
| Units (#2) | Python | https://bitbucket.org/adonohue/units |
| Unum (#1) | Python | https://bitbucket.org/kiv/unum |
| CF_Units | Python | https://github.com/SciTools/cf_units |
| DimPy | Python | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| Units of Measure (#1) | C# | https://archive.codeplex.com/?p=unitsofmeasure |
| Physical Measure | C# | https://github.com/KiloBravoLima/PhysicalMeasure |
| NGenericDimensions | C# | https://github.com/MafuJosh/NGenericDimensions |
| Quantities.net | C# | https://sourceforge.net/projects/quantitiesnet/ |
| .NET Unit Conversion Library | C# | https://sourceforge.net/projects/unitcon/ |
| Measurement Unit Conversion Library (#1) | C# | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Unit of Measure Library for .NET | C# | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Unit of Measure Validator for C# | C# | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Units of Measurement Systems | Java | https://github.com/unitsofmeasurement/uom-systems |
| Units (#3) | Java | https://github.com/SamCarlberg/units |
| Units (#4) | C# | https://github.com/engineers-tools/Units |
| PHP Unit Conversion | PHP | https://github.com/pimlie/php-unit-conversion |
| The Units of Measure Library | C++ | https://sourceforge.net/projects/tuoml/ |
| Metric (#1) | Rust | https://github.com/coder543/metric |
| ScalaU | Scala | https://github.com/adrianfr/scalau |
| Units (#5) | Go | https://github.com/smyrman/units |
| Superquants | Scala | https://github.com/rudogma/scala-superquants |
| Metric (#2) | Nim | https://github.com/mjendrusch/metric |
| Units D | D | https://github.com/nordlow/units-d |
| Units and Measurements | Racket | https://github.com/Metaxal/measures |
| SIUnits (#1) | Haskell | https://github.com/joewkr/SIUnits |
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
| Units (#9) | C# | https://github.com/LabyrinthApps/Units |
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
| Units.jl (#2) | Julia | https://github.com/autocorr/Units.jl |
| Units (#11) | Go | https://github.com/zn8nz/units |
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
| Quantities (#3) | C++ | https://sourceforge.net/projects/quantity/?source=directory |
| Magnitude (#2) | Java | https://sourceforge.net/projects/magnitude/?source=directory |
| PyPhys Class Library | Python | https://sourceforge.net/projects/pyphys/?source=directory |
| Physical | C++ | https://sourceforge.net/projects/physical/?source=directory |
| mcs::units | C++ | https://sourceforge.net/projects/mcs-units/?source=directory |
| Quan | C++ | https://sourceforge.net/projects/quan/?source=directory |
| Unum (#2) | Python | https://sourceforge.net/projects/unum/?source=directory |
| puny | Python | https://sourceforge.net/projects/puny/?source=directory |
| JQuantity: Precision Math Java Framework | Java | https://sourceforge.net/projects/jquantity/?source=directory |
| Java library and framework: quantity | Java | https://sourceforge.net/projects/javaquantity/?source=directory |
| PhysicalUnits (#2) | C++ | https://sourceforge.net/projects/physicalunits/?source=directory |
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
| Units (#15) | Rust | https://github.com/Boddlnagg/units |
| FSharp.Units | F# | https://github.com/putridparrot/FSharp.Units |
| Units (#16) | Scala | https://github.com/nestorpersist/units |
| Python-Units-Of-Measure | Python | https://github.com/katerina7479/python-units-of-measure |
| IMT.Units | Java | https://github.com/imt-ag/imt.units-java |
| PHPMeasures | PHP | https://github.com/dcabanaw/phpMeasures |
| PHP-Units | PHP | https://github.com/hiqdev/php-units |
| Cuis-Smalltalk-Aconcagua | Smalltalk | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| Measurements | PHP | https://github.com/marfurt/measurements |
| UnitsOfMeasureBundle | PHP | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| UnitsOfMeasure (#2) | C# | https://github.com/capnmidnight/UnitsOfMeasure |
| Units (#17) | PHP | https://github.com/ARCANEDEV/Units |
| Units_of_measure | C++ | https://github.com/Skeen/units_of_measure |
| Units (#18) | Go | https://github.com/antha-lang/units |
| Units of Measure Prototype | Haskell | https://github.com/adamgundry/uom-prototype |
| Uom.Dart | Dart | https://github.com/damondouglas/uom.dart |
| RockUnits | C# | https://github.com/gareth-reid/RockUnits |
| TundraMeasure.java | Java | https://github.com/Permafrost/TundraMeasure.java |
| Units (#19) | PHP | https://github.com/marando/Units |
| UnitOfMeasure (#1) | C# | https://github.com/Chef-Code/UnitOfMeasure |
| Units-api | PHP | https://github.com/shrimpza/units-api |
| cppDegRad | C++ | https://github.com/grahamboree/cppDegRad |
| Unit (#3) | VB .NET | https://github.com/AdamSpeight2008/Unit |
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
| Units (#21) | Haskell | https://github.com/goldfirere/units |
| DDUnitConverter | Objective-C | https://github.com/davedelong/DDUnitConverter |
| PHP-Conversion | PHP | https://github.com/crisu83/php-conversion |
| SIUnitX | TeX | https://github.com/josephwright/siunitx |
| Units (#24) | Scala | https://github.com/KarolS/units |
| SI-Units | Java | https://github.com/unitsofmeasurement/si-units |
| Conversion (#1) | PHP | https://github.com/abhimanyu003/conversion |
| UnitConverter (#5) | Python | https://github.com/mattgd/UnitConverter |
| Unit-converter | PHP | https://github.com/jordanbrauer/unit-converter |
| HHUnitConverter | Objective-C | https://github.com/HiveHicks/HHUnitConverter |
| Angular-Unit-Converter | JavaScript | https://github.com/alexandernst/angular-unit-converter |
| UnitConverterWin | C | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| UnitConversion (#1) | Objective-C | https://github.com/unixpickle/UnitConversion |
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
| UnitConversion (#2) | C# | https://github.com/gkampolis/UnitConversion |
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
| Units (#28) | C++ | https://github.com/lonkamikaze/units |
| Unit.styl | JavaScript | https://github.com/diessica/unit.styl |
| Conversionr | R | https://github.com/alexnakagawa/conversionr |
| Math-units | Perl | https://github.com/kenfox/Math-Units |
| UnitConvert | JavaScript | https://github.com/agnoster/unitology |
| NGunits | Java | https://github.com/erussell/ngunits |
| Units (#29) | Swift | https://github.com/chrisjeane/Units |
| UnitConversion (#3) | Python | https://github.com/UnitConversion/unitConversion |
| Metiri | JavaScript | https://github.com/GCheung55/metiri |
| Convert-units | Ruby | https://github.com/tanvir002700/convert_unit |
| Django-Unit-Field | Python | https://github.com/kohout/django-unit-field |
| Units (#30) | PHP | https://github.com/rmasters/units |
| Unit_Conversion | Ruby | https://github.com/eternal44/unit_conversion |
| Maegor | JavaScript | https://github.com/lukaskollmer/maegor |
| Units-System | Ruby | https://github.com/jgoizueta/units-system |
| Physical | C++ | https://github.com/olsonse/physical |
| Conversion (#6) | C++ | https://github.com/simonmeaden/conversion |
| Gorilla | Ruby | https://github.com/stephencelis/gorilla |
| QtUnits | C++ | https://github.com/hrobeers/QtUnits |
| Units (#32) | Ruby | https://github.com/woahdae/units |
| convertR | R | https://github.com/colin-fraser/convertR |
| UnitConversion (#4) | C# | https://github.com/Mecteral/UnitConversion |
| JSR 275 | Java | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| Quantified | Ruby | https://github.com/Shopify/quantified |
| Units (#33) | Haskell | https://hackage.haskell.org/package/units |

## Tools
| Name | Language | Source / URL |
|-------------------------------------------------------------------------|-------------------|--------------------------------------------------------------------------------------------|
| Phriky-Units | Python | https://github.com/unl-nimbus-lab/phriky-units |
| ParamPool | Python | https://github.com/hplgit/parampool |
| NumericalUnits | Python | https://github.com/sbyrnes321/numericalunits |
| Rink | Rust | https://github.com/tiffany352/rink-rs |
| Insect | PureScript | https://github.com/sharkdp/insect |
| Units (#8) | JavaScript | https://github.com/dohliam/units |
| Smart Units | Sidef | https://github.com/trizen/smart-units |
| Chimp | Python | https://github.com/mhetrerajat/chimp |
| XamConverter | C# | https://github.com/brminnick/XamConverter |
| UnitConverter (#1) | Java | https://github.com/nevack/UnitConverter |
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
| Unit Converter (#2) | Scratch | https://sourceforge.net/projects/unitconverter12/?source=directory |
| MAIA Unit Converter | C++ | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Unit Conveter (#3) | C# | https://sourceforge.net/projects/unitconversion/?source=directory |
| Converter (#2) | Java | https://sourceforge.net/projects/con-vert/?source=directory |
| LibreEngineering | Python | https://sourceforge.net/projects/libreeng/ |
| UNeedIT Converter | C# | https://sourceforge.net/projects/uneedconverter/?source=directory |
| Unit Converter (#4) | Python | https://sourceforge.net/projects/unit-converter/?source=directory |
| Portable Unit Converter | JavaScript | https://sourceforge.net/projects/puc/?source=directory |
| Web Unit Converter | C# | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| ChemicalA | C++ | https://sourceforge.net/projects/chemicala/?source=directory |
| Computing with Units | Java | https://sourceforge.net/projects/units-in-java/?source=directory |
| EngineeringCalculator | C++ | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| Quick Unit Converter | Java | https://sourceforge.net/projects/qunitconverter/?source=directory |
| Unit Converter (#5) | REBOL | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| ConverTo | C++ | https://sourceforge.net/projects/converto/?source=directory |
| UConverter | Java | https://sourceforge.net/projects/uconverter/?source=directory |
| GodSend | PHP | https://sourceforge.net/projects/godsend/?source=directory |
| JConvert | Java | https://sourceforge.net/projects/jconvert/?source=directory |
| SIMConverter | C# | https://sourceforge.net/projects/simconverter/?source=directory |
| Esos | C++ | https://sourceforge.net/projects/esos/?source=directory |
| Punits - Pluggable units | C | https://sourceforge.net/projects/punits/?source=directory |
| BeConverter | C++ | https://bitbucket.org/Teknomancer/beconverter |
| Unit (#2) | Java | https://bitbucket.org/hansolo/unit |
| Unit-converter (#1) | Python | https://bitbucket.org/brayvasq/unit-converter |
| Physics | Python | https://bitbucket.org/hppavilion1/physics |
| Frinj | Clojure | https://github.com/martintrojer/frinj |
| Converter (#3) | Java | https://github.com/samWson/converter |
| SimpleMeasurementConverter | Java | https://github.com/michaelstoops/SimpleMeasurementConverter |
| Converter (#4) | C++ | https://github.com/dtalaba/convertor |
| Frins | Scala | https://github.com/martintrojer/frins |
| MeasurementConverter | Java | https://github.com/SBrooks75/MeasurementConverter |
| UnitConverter (#4) | Java | https://github.com/MarioDudjak/UnitConverter |
| Maser | JavaScript/Python | https://github.com/justinbangerter/maser |
| JC-Units | Python | https://github.com/jason0x43/jc-units |
| UnitConverterUltimate | Java | https://github.com/physphil/UnitConverterUltimate |
| Units (#25) | Java | https://github.com/xxv/Units |
| Unit-Converter (#1) | JavaScript | https://github.com/TheMarco/Unit-Converter |
| Alfred-Converter | Python | https://github.com/WoLpH/alfred-converter |
| UnitConverter.htm | JavaScript | https://github.com/iterami/UnitConverter.htm |
| UnitConverter (#7) | Java | https://github.com/impateljay/UnitConverter |
| Unit-Converter (#3) | Java | https://github.com/AmitKumarSah/Unit-Converter |
| PythonUnitConverter | Python | https://github.com/Aaron1011/PythonUnitConverter |
| Converter (#5) | Java | https://github.com/HanSolo/converter |
| Mather | Java | https://github.com/icasdri/Mather |
| Vandelay | C++ | https://github.com/HaikuArchives/Vandelay |
| Unit-Converter (#3) | PHP | https://github.com/b-sebastian/unit-converter |
| Unit-Converter (#4) | C++ | https://github.com/mikeleppane/Unit-Converter |
| Unit-Converter (#6) | JavaScript | https://github.com/MaicolBen/unit-converter |
| Unit | PHP | https://github.com/pounard/Unit |
| Converter (#11) | C++ | https://github.com/KerryL/Converter |
| Angular-Converter | JavaScript | https://github.com/cyrilf/angular-converter |
| PreciseUnitConverter | JavaScript | https://github.com/bumxu/PreciseUnitConverter |
| Converter (#25) | TypeScript | https://github.com/ialex90/Converter |
| DakaUnitConverter | Java | https://github.com/darrylfonseka/DakaUnitConverter |
| Convertor | C++ | https://github.com/mihaelateo/Convertor |
| Converter (#27) | C++ | https://github.com/scruff3y/Converter |
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
| UnitConversion (#6) | Java | https://github.com/yfl007/UnitConversion |
| Unit-Conversion | JavaScript | https://github.com/srimanthk/unit-conversion |
| GNU Units | C# | https://www.gnu.org/software/units/ |

## All projects
| Name | Language | Valid project? | Source / URL | Total repositories | Python Repositories | C# Repositories | C++ Repositories | Java Repositories | Other Repositories |  |  |  |
|-----------------------------------------------------------------------------------------------------------------------------|-------------------|----------------|-------------------------------------------------------------------------------------------------|--------------------|---------------------|------------------------|-------------------------------------|---------------------------------------|--------------------------|------------------------|-----------------------|--------------------|
| Phriky-Units | Python | Yes | https://github.com/unl-nimbus-lab/phriky-units | 568 | 72 | 73 | 69 | 83 | 271 |  |  |  |
| UnitsNet | C# | Yes | https://github.com/angularsen/UnitsNet |  |  |  |  |  |  |  |  |  |
| ParamPool | Python | Yes | https://github.com/hplgit/parampool |  | GitHub Repositories | BitBucket Repositories | GitLab Repositories | SourceForge Repositories | CodeProject Repositories | LaunchPad Repositories | Savannah Repositories | Other Repositories |
| BoostUnits | C++ | Yes | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |  | 433 | 16 | 4 | 73 | 22 | 2 | 0 | 18 |
| Convert Units (#1) | Java | Yes | https://github.com/ben-ng/convert-units |  |  |  |  |  |  |  |  |  |
| Units (#1) | C++ | Yes | https://github.com/nholthaus/units |  | Number of languages |  |  |  |  |  |  |  |
| Unit (#1) | Go | Yes | https://github.com/martinlindhe/unit |  | 59 |  |  |  |  |  |  |  |
| Pint | Python | Yes | https://github.com/hgrecco/pint |  |  |  |  |  |  |  |  |  |
| UnitConversionLib | C# | Yes | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |  |  |  |  |  |  |  |  |  |
| EiffelUnits | Eiffel | Yes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |  |  |  |  |  |  |  |  |  |
| Natu | Python | Yes | https://github.com/kdavies4/natu |  |  |  |  |  |  |  |  |  |
| Buckingham | Python | Yes | https://github.com/mdipierro/buckingham |  |  |  |  |  |  |  |  |  |
| Magnitude (#1) | Python | Yes | https://github.com/juanre/magnitude |  |  |  |  |  |  |  |  |  |
| Units (#2) | Python | Yes | https://bitbucket.org/adonohue/units |  |  |  |  |  |  |  |  |  |
| Unum (#1) | Python | Yes | https://bitbucket.org/kiv/unum |  |  |  |  |  |  |  |  |  |
| Scimath | Python | Yes | https://github.com/enthought/scimath |  |  |  |  |  |  |  |  |  |
| Python Quantities | Python | Yes | https://github.com/python-quantities/python-quantities |  |  |  |  |  |  |  |  |  |
| Udunitspy | Python | No | https://github.com/blazetopher/udunitspy |  |  |  |  |  |  |  |  |  |
| Astropy | Python | Yes | https://github.com/astropy/astropy |  |  |  |  |  |  |  |  |  |
| CF_Units | Python | Yes | https://github.com/SciTools/cf_units |  |  |  |  |  |  |  |  |  |
| DimPy | Python | Yes | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |  |  |  |  |  |  |  |  |  |
| NumericalUnits | Python | Yes | https://github.com/sbyrnes321/numericalunits |  |  |  |  |  |  |  |  |  |
| Efficient Scalars in Scala | Scala | Yes | http://russp.us/scalar-scala.htm |  |  |  |  |  |  |  |  |  |
| Efficient Scalars in Python | Python | Yes | http://russp.us/scalar-python.htm |  |  |  |  |  |  |  |  |  |
| Units of Measure (#1) | C# | Yes | https://archive.codeplex.com/?p=unitsofmeasure |  |  |  |  |  |  |  |  |  |
| Units of Measurement | C# | Yes | https://github.com/mangh/unitsofmeasurement |  |  |  |  |  |  |  |  |  |
| Physical Measure | C# | Yes | https://github.com/KiloBravoLima/PhysicalMeasure |  |  |  |  |  |  |  |  |  |
| Quantity System | C# | Yes | https://github.com/ibluesun/QuantitySystem |  |  |  |  |  |  |  |  |  |
| Quantity Types | C# | Yes | https://github.com/objorke/QuantityTypes |  |  |  |  |  |  |  |  |  |
| NGenericDimensions | C# | Yes | https://github.com/MafuJosh/NGenericDimensions |  |  |  |  |  |  |  |  |  |
| Quantities.net | C# | Yes | https://sourceforge.net/projects/quantitiesnet/ |  |  |  |  |  |  |  |  |  |
| .NET Unit Conversion Library | C# | Yes | https://sourceforge.net/projects/unitcon/ |  |  |  |  |  |  |  |  |  |
| Measurement Unit Conversion Library (#1) | C# | Yes | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |  |  |  |  |  |  |  |  |  |
| Unit of Measure Library for .NET | C# | Yes | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |  |  |  |  |  |  |  |  |  |
| Unit of Measure Validator for C# | C# | Yes | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |  |  |  |  |  |  |  |  |  |
| Working with Units and Amounts | C# | Yes | https://www.codeproject.com/script/Articles/ListVersions.aspx?aid=611731 |  |  |  |  |  |  |  |  |  |
| GNU Units | C# | Yes | https://www.gnu.org/software/units/ |  |  |  |  |  |  |  |  |  |
| RedStar.Amounts | C# | Yes | https://github.com/petermorlion/RedStar.Amounts/ |  |  |  |  |  |  |  |  |  |
| Units of Measurement Systems | Java | Yes | https://github.com/unitsofmeasurement/uom-systems |  |  |  |  |  |  |  |  |  |
| CaliperSharp | C# | Yes | https://github.com/point85/CaliperSharp |  |  |  |  |  |  |  |  |  |
| Units (#3) | Java | Yes | https://github.com/SamCarlberg/units |  |  |  |  |  |  |  |  |  |
| Units (#4) | C# | Yes | https://github.com/engineers-tools/Units |  |  |  |  |  |  |  |  |  |
| Cubico | C# | Yes | https://github.com/irperez/Cubico |  |  |  |  |  |  |  |  |  |
| Unitful.jl | Julia | Yes | https://github.com/ajkeller34/Unitful.jl |  |  |  |  |  |  |  |  |  |
| PHP Unit Conversion | PHP | Yes | https://github.com/pimlie/php-unit-conversion |  |  |  |  |  |  |  |  |  |
| The Units of Measure Library | C++ | Yes | https://sourceforge.net/projects/tuoml/ |  |  |  |  |  |  |  |  |  |
| Squants | Scala | Yes | https://github.com/typelevel/squants |  |  |  |  |  |  |  |  |  |
| Quantities (#1) | Idris | Yes | https://github.com/timjb/quantities |  |  |  |  |  |  |  |  |  |
| Rink | Rust | Yes | https://github.com/tiffany352/rink-rs |  |  |  |  |  |  |  |  |  |
| Unit API | Java | Yes | https://github.com/unitsofmeasurement/unit-api |  |  |  |  |  |  |  |  |  |
| PhysUnits (#1) | C++ | Yes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |  |  |  |  |  |  |  |  |  |
| Coulomb | Scala | Yes | https://github.com/erikerlandson/coulomb |  |  |  |  |  |  |  |  |  |
| Metric (#1) | Rust | Yes | https://github.com/coder543/metric |  |  |  |  |  |  |  |  |  |
| ScalaU | Scala | Yes | https://github.com/adrianfr/scalau |  |  |  |  |  |  |  |  |  |
| Units (#5) | Go | Yes | https://github.com/smyrman/units |  |  |  |  |  |  |  |  |  |
| Superquants | Scala | Yes | https://github.com/rudogma/scala-superquants |  |  |  |  |  |  |  |  |  |
| Elixir Unit Converter | Elixir | Yes | https://github.com/carturoch/ex_uc |  |  |  |  |  |  |  |  |  |
| Metric (#2) | Nim | Yes | https://github.com/mjendrusch/metric |  |  |  |  |  |  |  |  |  |
| Units of Measure (#2) | Kotlin | Yes | https://github.com/kunalsheth/units-of-measure |  |  |  |  |  |  |  |  |  |
| Units (#6) | C++ | Yes | https://github.com/tonypilz/units |  |  |  |  |  |  |  |  |  |
| Units D | D | Yes | https://github.com/nordlow/units-d |  |  |  |  |  |  |  |  |  |
| Quantities (#2) | D | Yes | https://github.com/biozic/quantities |  |  |  |  |  |  |  |  |  |
| Measures with Dimensions | Racket | Yes | https://github.com/AlexKnauth/measures-with-dimensions |  |  |  |  |  |  |  |  |  |
| Units and Measurements | Racket | Yes | https://github.com/Metaxal/measures |  |  |  |  |  |  |  |  |  |
| Java Unit Conversion Library | Java | No | https://www.openhub.net/p/jucl |  |  |  |  |  |  |  |  |  |
| Units (#7) | Multiple | Yes | https://github.com/saroad2/units |  |  |  |  |  |  |  |  |  |
| Caliper | Java | Yes | https://github.com/point85/caliper |  |  |  |  |  |  |  |  |  |
| Uncodium.Units | F# | Yes | https://github.com/stefanmaierhofer/Uncodium.Units |  |  |  |  |  |  |  |  |  |
| NUnitConverter | C# | No | http://jamesnewkirk.typepad.com/posts/nunit_converter_v11.html |  |  |  |  |  |  |  |  |  |
| PHP Units of Measure | PHP | Yes | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |  |  |  |  |  |  |  |  |  |
| SIUnits (#1) | Haskell | Yes | https://github.com/joewkr/SIUnits |  |  |  |  |  |  |  |  |  |
| Physikal (#1) | Kotlin | Yes | https://github.com/unitsofmeasurement/Physikal |  |  |  |  |  |  |  |  |  |
| Engineering | C# | Yes | https://github.com/zhofre/engineering |  |  |  |  |  |  |  |  |  |
| ProgParam | C++ | Yes | https://github.com/qPCR4vir/ProgParam |  |  |  |  |  |  |  |  |  |
| InkUnits | Swift | Yes | https://github.com/angelsolaorbaiceta/InkUnits |  |  |  |  |  |  |  |  |  |
| Unit Converter (#1) | C | No | https://github.com/nithjino/UnitConverter |  |  |  |  |  |  |  |  |  |
| Flowsnake | JavaScript | Yes | https://github.com/Eldelshell/flowsnake |  |  |  |  |  |  |  |  |  |
| Unit | Ruby | No | https://github.com/christinach/unit |  |  |  |  |  |  |  |  |  |
| Insect | PureScript | Yes | https://github.com/sharkdp/insect |  |  |  |  |  |  |  |  |  |
| Ruby Units | Ruby | Yes | https://github.com/olbrich/ruby-units |  |  |  |  |  |  |  |  |  |
| JS-quantities | JavaScript | Yes | https://github.com/gentooboontoo/js-quantities |  |  |  |  |  |  |  |  |  |
| Dimensioned | Rust | Yes | https://github.com/paholg/dimensioned |  |  |  |  |  |  |  |  |  |
| SwiftMeasurement | Swift | Yes | https://github.com/ken0nek/SwiftMeasurement |  |  |  |  |  |  |  |  |  |
| FP Units | JavaScript | No | https://github.com/anthonydugois/fp-units |  |  |  |  |  |  |  |  |  |
| Units 2 | Clojure | Yes | https://github.com/mfey/units2 |  |  |  |  |  |  |  |  |  |
| Units (#8) | JavaScript | Yes | https://github.com/dohliam/units |  |  |  |  |  |  |  |  |  |
| Smart Units | Sidef | Yes | https://github.com/trizen/smart-units |  |  |  |  |  |  |  |  |  |
| Scientific Javascript | JavaScript | No | https://github.com/gkjohnson/scientific-javascript |  |  |  |  |  |  |  |  |  |
| JNum | Java | Yes | https://github.com/attipaci/jnum |  |  |  |  |  |  |  |  |  |
| Cerebro Converter | JavaScript | No | https://github.com/KELiON/cerebro-converter |  |  |  |  |  |  |  |  |  |
| MagickScience | C++ | Yes | https://github.com/Iarfen/MagickScience |  |  |  |  |  |  |  |  |  |
| Unitwise | Ruby | Yes | https://github.com/joshwlewis/unitwise |  |  |  |  |  |  |  |  |  |
| Quantity | Haskell | No | https://github.com/irreverent-pixel-feats/quantity |  |  |  |  |  |  |  |  |  |
| Unit.py | Python | Yes | https://github.com/fabian0010/Unit.py |  |  |  |  |  |  |  |  |  |
| Chimp | Python | Yes | https://github.com/mhetrerajat/chimp |  |  |  |  |  |  |  |  |  |
| Cue | C++ | No | https://github.com/OMGtechy/Cue |  |  |  |  |  |  |  |  |  |
| Libquantify | C++ | Yes | https://github.com/damianorenfer/libquantify |  |  |  |  |  |  |  |  |  |
| Constants and Units | MatLab | Yes | https://github.com/mariomerinomartinez/constants_and_units |  |  |  |  |  |  |  |  |  |
| Units4j | Java | No | https://github.com/echocat/units4j |  |  |  |  |  |  |  |  |  |
| UOM-Domain | Java | Yes | https://github.com/unitsofmeasurement/uom-domain |  |  |  |  |  |  |  |  |  |
| Run-Convert | JavaScript | No | https://github.com/cdbusby/run-convert |  |  |  |  |  |  |  |  |  |
| Units (#9) | C# | Yes | https://github.com/LabyrinthApps/Units |  |  |  |  |  |  |  |  |  |
| Scale | Swift | Yes | https://github.com/onmyway133/Scale |  |  |  |  |  |  |  |  |  |
| XamConverter | C# | Yes | https://github.com/brminnick/XamConverter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#1) | Java | Yes | https://github.com/nevack/UnitConverter |  |  |  |  |  |  |  |  |  |
| Trevor | JavaScript | No | https://github.com/ozgrozer/trevor |  |  |  |  |  |  |  |  |  |
| SIConv | Haskell | Yes | https://github.com/owainlewis/conventional-si-unit-converter |  |  |  |  |  |  |  |  |  |
| Convert | Swift | Yes | https://github.com/danielbyon/Convert |  |  |  |  |  |  |  |  |  |
| TempConvert | Python | No | https://github.com/rootinchase/tempconvert |  |  |  |  |  |  |  |  |  |
| Convertee | JavaScript | Yes | https://github.com/isquaredcreative/Convertee |  |  |  |  |  |  |  |  |  |
| Converter (#1) | PHP | Yes | https://github.com/cartalyst/converter |  |  |  |  |  |  |  |  |  |
| Conversion Calculator | C++ | Yes | https://github.com/dtuivs/Converter |  |  |  |  |  |  |  |  |  |
| Temperature | Go | No | https://github.com/yanndr/temperature |  |  |  |  |  |  |  |  |  |
| Quantify | Ruby | Yes | https://github.com/spatchcock/quantify |  |  |  |  |  |  |  |  |  |
| SY | Ruby | Yes | https://github.com/boris-s/sy |  |  |  |  |  |  |  |  |  |
| FURY | Fortran | Yes | https://github.com/szaghi/FURY |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#1) | Common Lisp | Yes | https://github.com/mrossini-ethz/physical-quantities |  |  |  |  |  |  |  |  |  |
| UOM | Ruby | Yes | https://github.com/madriska/uom |  |  |  |  |  |  |  |  |  |
| SIUnits (#2) | C++ | No | https://github.com/Jajauma/SIUnits |  |  |  |  |  |  |  |  |  |
| Physical Units for Matlab | MatLab | Yes | https://github.com/sky-s/physical-units-for-matlab |  |  |  |  |  |  |  |  |  |
| VUnits | Java | Yes | https://github.com/vaslabs/vunits |  |  |  |  |  |  |  |  |  |
| PhysicalUnits (#1) | F# | No | https://github.com/kainous/PhysicalUnits |  |  |  |  |  |  |  |  |  |
| Units (#10) | Python | No | https://github.com/DanielSank/units |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#2) | C# | Yes | https://github.com/timdetering/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| Physical-Units | Scala | No | https://github.com/ppiotrow/physical-units |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#3) | Python | No | https://github.com/ppfaff/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| UnitsOfMeasurement | C++ | No | https://github.com/grafwolg/UnitsOfMeasurement |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#4) | C# | No | https://github.com/Traquina/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#5) | Haskell | Yes | https://github.com/fehu/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| Python-Physical | Python | Yes | https://github.com/EdwinChan/python-physical |  |  |  |  |  |  |  |  |  |
| PhysicalValue | Swift | Yes | https://github.com/antonvmironov/PhysicalValue |  |  |  |  |  |  |  |  |  |
| Units.jl (#1) | Julia | No | https://github.com/sclereid/Units.jl |  |  |  |  |  |  |  |  |  |
| Lathexa Units | JavaScript | Yes | https://github.com/lethexa/lethexa-units |  |  |  |  |  |  |  |  |  |
| Units.jl (#2) | Julia | Yes | https://github.com/autocorr/Units.jl |  |  |  |  |  |  |  |  |  |
| M2py | Python/Matlab | Yes | https://github.com/caiorss/m2py |  |  |  |  |  |  |  |  |  |
| Units (#11) | Go | Yes | https://github.com/zn8nz/units |  |  |  |  |  |  |  |  |  |
| AutoUnits | C++ | Yes | https://github.com/Fifty-Nine/AutoUnits |  |  |  |  |  |  |  |  |  |
| PhysUnits (#2) | C++ | No | https://github.com/rdlabspl/PhysUnits |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities (#6) | Python | No | https://github.com/d0cod3r/physicalQuantitis |  |  |  |  |  |  |  |  |  |
| Mensura | Python | No | https://github.com/ypsilus/mensura |  |  |  |  |  |  |  |  |  |
| Physical Math | Python | Yes | https://github.com/matthagy/physmath |  |  |  |  |  |  |  |  |  |
| Dimanalyser | Java | Yes | https://github.com/cymi/dimanalyser |  |  |  |  |  |  |  |  |  |
| Dftu | C++ | Yes | https://github.com/triblatron/dftu |  |  |  |  |  |  |  |  |  |
| Scaler | Shell | Yes | https://github.com/emugel/scaler |  |  |  |  |  |  |  |  |  |
| Comment-Units | Rust | No | https://github.com/willi-kappler/comment_units |  |  |  |  |  |  |  |  |  |
| Physcon | Python | Yes | https://github.com/georglind/physcon |  |  |  |  |  |  |  |  |  |
| Praktool | Python | Yes | https://github.com/zombofant/praktool |  |  |  |  |  |  |  |  |  |
| Units-v2 | C++ | Yes | https://github.com/Corristo/units-v2 |  |  |  |  |  |  |  |  |  |
| UDUnits | Julia | Yes | https://github.com/Alexander-Barth/UDUnits.jl |  |  |  |  |  |  |  |  |  |
| Quantity.Net | C# | Yes | https://github.com/bcachet/Quantity.Net |  |  |  |  |  |  |  |  |  |
| Elm-tunits | Elm | No | https://github.com/gyulalaszlo/elm-tunits |  |  |  |  |  |  |  |  |  |
| Unit Conversion Wox Plugin | Python/PowerShell | No | https://github.com/rpalo/wox-unit-converter |  |  |  |  |  |  |  |  |  |
| ParamPy | Python | Yes | https://github.com/matthewwardrop/python-parampy |  |  |  |  |  |  |  |  |  |
| UnitManipulationLibrary | C++ | Yes | https://github.com/OuaisBla/UnitManipulationLibrary |  |  |  |  |  |  |  |  |  |
| Dimension-TF | Haskell | Yes | https://github.com/nushio3/dimensional-tf |  |  |  |  |  |  |  |  |  |
| Phys-Types | C++ | Yes | https://github.com/akubera/phys_types |  |  |  |  |  |  |  |  |  |
| Unit | C++/CMake/Python | Yes | https://github.com/njoy/unit |  |  |  |  |  |  |  |  |  |
| Pyvalem | Python | Yes | https://github.com/xnx/pyqn |  |  |  |  |  |  |  |  |  |
| ValueWithUnit | C# | Yes | https://github.com/vbfox/ValueWithUnit |  |  |  |  |  |  |  |  |  |
| UnitKit | Swift | Yes | https://github.com/otaviocc/UnitKit |  |  |  |  |  |  |  |  |  |
| SI | C++ | No | https://github.com/erdavila/SI |  |  |  |  |  |  |  |  |  |
| qMetrics | C++ | Yes | https://launchpad.net/qmetrics |  |  |  |  |  |  |  |  |  |
| SimpleUnitConverter | C | Yes | https://launchpad.net/simpleunitconverter |  |  |  |  |  |  |  |  |  |
| o2scl | C | Yes | https://github.com/awsteiner/o2scl |  |  |  |  |  |  |  |  |  |
| Units and measures for C++ 11 | C++ | Yes | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |  |  |  |  |  |  |  |  |  |
| Using physical quantities and units of measure in C# programs | C# | Yes | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |  |  |  |  |  |  |  |  |  |
| Decibel Units of Measurement with C# Framework | C# | Yes | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |  |  |  |  |  |  |  |  |  |
| Units of measurement types in C++ | C++ | No | https://www.codeproject.com/Articles/791511/Units-of-measurement-types-in-Cplusplus-Using-comp |  |  |  |  |  |  |  |  |  |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | C# | Yes | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |  |  |  |  |  |  |  |  |  |
| Quantities, Units, and Values: An Object Oriented Implementation | C | Yes | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |  |  |  |  |  |  |  |  |  |
| Automatic Conversion of Physical Units | C# | Yes | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |  |  |  |  |  |  |  |  |  |
| Unit Conversions in C#/WPF | C# | Yes | https://www.codeproject.com/Articles/30569/Unit-Conversions-in-C-WPF |  |  |  |  |  |  |  |  |  |
| A look at the Boost Units Library | C++ | No | https://www.codeproject.com/Articles/988932/Boost-Units-Library |  |  |  |  |  |  |  |  |  |
| TCX Unit Conversion Library | C++ | Yes | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |  |  |  |  |  |  |  |  |  |
| Complete Unit Conversion Sample in C# .NET | C# | Yes | https://www.codeproject.com/Articles/22470/Complete-Unit-Conversion-Sample-in-C-NET |  |  |  |  |  |  |  |  |  |
| Measurement Unit Conversion Library (#2) | C# | Yes | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |  |  |  |  |  |  |  |  |  |
| International System of Units Notation | C# | Yes | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |  |  |  |  |  |  |  |  |  |
| Converting a value to an SI Unit String | C# | Yes | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |  |  |  |  |  |  |  |  |  |
| Validation Dimensions of Physical Quantities .NET | C# | Yes | https://www.codeproject.com/Tips/1005796/Validation-Dimensions-of-Physical-Quantities-NET |  |  |  |  |  |  |  |  |  |
| Application of C++11 User-Defined Literals to Handling Scientific Quantities, Number Representation and String Manipulation | C++ | Yes | https://www.codeproject.com/Articles/447922/Application-of-Cplusplus-User-Defined-Literals-t |  |  |  |  |  |  |  |  |  |
| Units of measurement for Ada | Ada | Yes | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Management Framework | Java | Yes | https://sourceforge.net/projects/quantitymanager/?source=directory |  |  |  |  |  |  |  |  |  |
| Measures and Units | C# | No | https://sourceforge.net/projects/measure/?source=directory |  |  |  |  |  |  |  |  |  |
| UOM Conversion Library | Java | Yes | https://sourceforge.net/projects/uomcl/?source=directory |  |  |  |  |  |  |  |  |  |
| UnitParser | C# | Yes | https://www.codeproject.com/Articles/1211504/UnitParser |  |  |  |  |  |  |  |  |  |
| Converter Application | Python | No | https://sourceforge.net/projects/converter-application/?source=directory |  |  |  |  |  |  |  |  |  |
| Libre Unit Conveter | C# | Yes | https://sourceforge.net/projects/libreunitconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| ConvertAll | Python | Yes | https://sourceforge.net/projects/convertall/?source=directory |  |  |  |  |  |  |  |  |  |
| NumericalChameleon | Java | Yes | https://sourceforge.net/projects/numchameleon/?source=directory |  |  |  |  |  |  |  |  |  |
| JFX Konwerter | Java | Yes | https://sourceforge.net/projects/jfx-konwerter/?source=directory |  |  |  |  |  |  |  |  |  |
| Temperature Unit Converter | C | No | https://sourceforge.net/projects/temp-unit-converter/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Converter (#2) | Scratch | Yes | https://sourceforge.net/projects/unitconverter12/?source=directory |  |  |  |  |  |  |  |  |  |
| MAIA Unit Converter | C++ | Yes | https://sourceforge.net/projects/maia-unit-conv/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Conveter (#3) | C# | Yes | https://sourceforge.net/projects/unitconversion/?source=directory |  |  |  |  |  |  |  |  |  |
| XVertR - eXtensible units conVERTeR | JavaScript | No | https://sourceforge.net/projects/xvertr/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Converter (#3) | Java | No | https://sourceforge.net/projects/unitsconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Imperial & Metric Converter | VB .NET | No | https://sourceforge.net/projects/exconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Converter (#2) | Java | Yes | https://sourceforge.net/projects/con-vert/?source=directory |  |  |  |  |  |  |  |  |  |
| LibreEngineering | Python | Yes | https://sourceforge.net/projects/libreeng/ |  |  |  |  |  |  |  |  |  |
| UNeedIT Converter | C# | Yes | https://sourceforge.net/projects/uneedconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Aviation Tool | VB .NET | No | https://sourceforge.net/projects/aviationtool/?source=directory |  |  |  |  |  |  |  |  |  |
| PHP Unit Converter | PHP | No | https://sourceforge.net/projects/phpunitconvert/?source=directory |  |  |  |  |  |  |  |  |  |
| Spectroscopist's Energy Converter | C | No | https://sourceforge.net/projects/specon/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Converter (#4) | Python | Yes | https://sourceforge.net/projects/unit-converter/?source=directory |  |  |  |  |  |  |  |  |  |
| Portable Unit Converter | JavaScript | Yes | https://sourceforge.net/projects/puc/?source=directory |  |  |  |  |  |  |  |  |  |
| Winds Units Converter | C++ | No | https://sourceforge.net/projects/windunitsconver/?source=directory |  |  |  |  |  |  |  |  |  |
| Libunits | C | Yes | https://sourceforge.net/projects/libunits/?source=directory |  |  |  |  |  |  |  |  |  |
| Web Unit Converter | C# | Yes | https://sourceforge.net/projects/web-unit-converter/?source=directory |  |  |  |  |  |  |  |  |  |
| Gas Flow Unit Conversion | Python | No | https://sourceforge.net/projects/gas-flow-unit-conversion/?source=directory |  |  |  |  |  |  |  |  |  |
| ChemicalA | C++ | Yes | https://sourceforge.net/projects/chemicala/?source=directory |  |  |  |  |  |  |  |  |  |
| PUMA Repository | Pascal | No | https://sourceforge.net/projects/puma-repository/?source=directory |  |  |  |  |  |  |  |  |  |
| Java Numbers with Unit | Java | No | https://sourceforge.net/projects/jnumwu/?source=directory |  |  |  |  |  |  |  |  |  |
| QSAS | C++ | No | https://sourceforge.net/projects/qsas/?source=directory |  |  |  |  |  |  |  |  |  |
| Rssfiz | Java | No | https://sourceforge.net/projects/rssfiz/?source=directory |  |  |  |  |  |  |  |  |  |
| Computing with Units | Java | Yes | https://sourceforge.net/projects/units-in-java/?source=directory |  |  |  |  |  |  |  |  |  |
| EveryConverter | Java | No | https://sourceforge.net/projects/everyconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| EngineeringCalculator | C++ | Yes | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |  |  |  |  |  |  |  |  |  |
| UltimateCalculator | Java | No | https://sourceforge.net/projects/ultimatecalculator/?source=directory |  |  |  |  |  |  |  |  |  |
| Quick Unit Converter | Java | Yes | https://sourceforge.net/projects/qunitconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Conveter using PHP and HTML | PHP | No | https://sourceforge.net/projects/stgmunitconvert/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Converter (#5) | REBOL | Yes | https://sourceforge.net/projects/tbunitconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Imp Converter | C++ | No | https://sourceforge.net/projects/impconvert/?source=directory |  |  |  |  |  |  |  |  |  |
| ConverTo | C++ | Yes | https://sourceforge.net/projects/converto/?source=directory |  |  |  |  |  |  |  |  |  |
| UConverter | Java | Yes | https://sourceforge.net/projects/uconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Quantities (#3) | C++ | Yes | https://sourceforge.net/projects/quantity/?source=directory |  |  |  |  |  |  |  |  |  |
| Magnitude (#2) | Java | Yes | https://sourceforge.net/projects/magnitude/?source=directory |  |  |  |  |  |  |  |  |  |
| PyPhys Class Library | Python | Yes | https://sourceforge.net/projects/pyphys/?source=directory |  |  |  |  |  |  |  |  |  |
| Physical | C++ | Yes | https://sourceforge.net/projects/physical/?source=directory |  |  |  |  |  |  |  |  |  |
| mcs::units | C++ | Yes | https://sourceforge.net/projects/mcs-units/?source=directory |  |  |  |  |  |  |  |  |  |
| Quan | C++ | Yes | https://sourceforge.net/projects/quan/?source=directory |  |  |  |  |  |  |  |  |  |
| Units Conversion Library | C | No | https://sourceforge.net/projects/units/?source=directory |  |  |  |  |  |  |  |  |  |
| Unum (#2) | Python | Yes | https://sourceforge.net/projects/unum/?source=directory |  |  |  |  |  |  |  |  |  |
| puny | Python | Yes | https://sourceforge.net/projects/puny/?source=directory |  |  |  |  |  |  |  |  |  |
| JQuantity: Precision Math Java Framework | Java | Yes | https://sourceforge.net/projects/jquantity/?source=directory |  |  |  |  |  |  |  |  |  |
| GodSend | PHP | Yes | https://sourceforge.net/projects/godsend/?source=directory |  |  |  |  |  |  |  |  |  |
| Java library and framework: quantity | Java | Yes | https://sourceforge.net/projects/javaquantity/?source=directory |  |  |  |  |  |  |  |  |  |
| PhysicalUnits (#2) | C++ | Yes | https://sourceforge.net/projects/physicalunits/?source=directory |  |  |  |  |  |  |  |  |  |
| QUDAL | C++ | Yes | https://sourceforge.net/projects/qudal/?source=directory |  |  |  |  |  |  |  |  |  |
| DimensionalAnalysis | Python | No | https://sourceforge.net/projects/dimensionalanalysis/?source=directory |  |  |  |  |  |  |  |  |  |
| Scientific Library | C++ | No | https://sourceforge.net/projects/scientificlib/?source=directory |  |  |  |  |  |  |  |  |  |
| C++ Unit Library | C++ | Yes | https://sourceforge.net/projects/cppunitlibrary/?source=directory |  |  |  |  |  |  |  |  |  |
| UnitsC++ | C++ | Yes | https://sourceforge.net/projects/unitscpp/?source=directory |  |  |  |  |  |  |  |  |  |
| C++ Units | C++ | Yes | https://sourceforge.net/projects/cppunits/?source=directory |  |  |  |  |  |  |  |  |  |
| JConvert | Java | Yes | https://sourceforge.net/projects/jconvert/?source=directory |  |  |  |  |  |  |  |  |  |
| Unit Var | Python | Yes | https://sourceforge.net/projects/unitvar/?source=directory |  |  |  |  |  |  |  |  |  |
| SIMConverter | C# | Yes | https://sourceforge.net/projects/simconverter/?source=directory |  |  |  |  |  |  |  |  |  |
| Java Measure | Java | Yes | https://sourceforge.net/projects/javameasure/?source=directory |  |  |  |  |  |  |  |  |  |
| Esos | C++ | Yes | https://sourceforge.net/projects/esos/?source=directory |  |  |  |  |  |  |  |  |  |
| Punits - Pluggable units | C | Yes | https://sourceforge.net/projects/punits/?source=directory |  |  |  |  |  |  |  |  |  |
| Python Unit Conversion Library | Python | Yes | https://sourceforge.net/projects/pythonconvert/?source=directory |  |  |  |  |  |  |  |  |  |
| .NET Unit Conversion Library | C# | Yes | https://sourceforge.net/projects/unitcon/?source=directory |  |  |  |  |  |  |  |  |  |
| SI -- A Scala Library of Units of Measurement | Scala | Yes | https://gitlab.com/h2b/SI |  |  |  |  |  |  |  |  |  |
| Red-units | Red | Yes | https://gitlab.com/maxvel/red-units |  |  |  |  |  |  |  |  |  |
| Units (#12) | C++ | No | https://gitlab.com/eclufsc/eda/units |  |  |  |  |  |  |  |  |  |
| Easyunits-rs | Rust | No | https://gitlab.com/imp/easyunits-rs |  |  |  |  |  |  |  |  |  |
| .NET Units of Measure | C# | Yes | https://bitbucket.org/Thecentury/.net-units-of-measure |  |  |  |  |  |  |  |  |  |
| Fan measure | Fan | No | https://bitbucket.org/qualidafial/fan-measure |  |  |  |  |  |  |  |  |  |
| BeConverter | C++ | Yes | https://bitbucket.org/Teknomancer/beconverter |  |  |  |  |  |  |  |  |  |
| Unit (#2) | Java | Yes | https://bitbucket.org/hansolo/unit |  |  |  |  |  |  |  |  |  |
| Units (#13) | Go | No | https://bitbucket.org/ede/units |  |  |  |  |  |  |  |  |  |
| Unit-converter (#1) | Python | Yes | https://bitbucket.org/brayvasq/unit-converter |  |  |  |  |  |  |  |  |  |
| Units (#14) | Python | No | https://bitbucket.org/johanhake/units |  |  |  |  |  |  |  |  |  |
| Unit-converter (#2) | JavaScript | No | https://bitbucket.org/sergespaolonzi/unit-converter |  |  |  |  |  |  |  |  |  |
| All Unit Converter | Java | No | https://bitbucket.org/Chawakorn_A/all-unit-converter |  |  |  |  |  |  |  |  |  |
| Unit Converter Application | Java | No | https://bitbucket.org/cpresley/unit-converter-application |  |  |  |  |  |  |  |  |  |
| Meshy-quantities | Python | No | https://bitbucket.org/meshy/meshy-quantities/src |  |  |  |  |  |  |  |  |  |
| Unum (#3) | Python | Yes | https://bitbucket.org/kiv/unum |  |  |  |  |  |  |  |  |  |
| UnitConverterLibrary | C# | No | https://bitbucket.org/MADc0d3r/unitconverterpublic |  |  |  |  |  |  |  |  |  |
| Physics | Python | Yes | https://bitbucket.org/hppavilion1/physics |  |  |  |  |  |  |  |  |  |
| Measurement.js | JavaScript | Yes | https://github.com/Philzen/measurement.js |  |  |  |  |  |  |  |  |  |
| Frinj | Clojure | Yes | https://github.com/martintrojer/frinj |  |  |  |  |  |  |  |  |  |
| UnitsKit | Objective-C | Yes | https://github.com/stevemoser/UnitsKit |  |  |  |  |  |  |  |  |  |
| UOM-Plugin | Haskell | Yes | https://github.com/adamgundry/uom-plugin |  |  |  |  |  |  |  |  |  |
| Units-of-Measure (#1) | Scala | Yes | https://github.com/Mononofu/Units-of-Measure |  |  |  |  |  |  |  |  |  |
| Units (#15) | Rust | Yes | https://github.com/Boddlnagg/units |  |  |  |  |  |  |  |  |  |
| Fhir.Metrics | C# | Yes | https://github.com/FirelyTeam/Fhir.Metrics |  |  |  |  |  |  |  |  |  |
| FSharp.Units | F# | Yes | https://github.com/putridparrot/FSharp.Units |  |  |  |  |  |  |  |  |  |
| Units (#16) | Scala | Yes | https://github.com/nestorpersist/units |  |  |  |  |  |  |  |  |  |
| Units-Ruby | Ruby | Yes | https://github.com/bfoz/units-ruby |  |  |  |  |  |  |  |  |  |
| Python-Units-Of-Measure | Python | Yes | https://github.com/katerina7479/python-units-of-measure |  |  |  |  |  |  |  |  |  |
| PPX_Measure | OCalm | Yes | https://github.com/xvw/ppx_measure |  |  |  |  |  |  |  |  |  |
| IMT.Units | Java | Yes | https://github.com/imt-ag/imt.units-java |  |  |  |  |  |  |  |  |  |
| Measurement_Converter | Java | No | https://github.com/KinYee/Measurement_Converter |  |  |  |  |  |  |  |  |  |
| Converter (#3) | Java | Yes | https://github.com/samWson/converter |  |  |  |  |  |  |  |  |  |
| SimpleMeasurementConverter | Java | Yes | https://github.com/michaelstoops/SimpleMeasurementConverter |  |  |  |  |  |  |  |  |  |
| Converter (#4) | C++ | Yes | https://github.com/dtalaba/convertor |  |  |  |  |  |  |  |  |  |
| UnitConverter (#2) | C++ | No | https://github.com/Shaddox/UnitConverter |  |  |  |  |  |  |  |  |  |
| Unit-converter (#3) | Java | No | https://github.com/ThanasiG/unit-converter |  |  |  |  |  |  |  |  |  |
| Frins | Scala | Yes | https://github.com/martintrojer/frins |  |  |  |  |  |  |  |  |  |
| PHPMeasures | PHP | Yes | https://github.com/dcabanaw/phpMeasures |  |  |  |  |  |  |  |  |  |
| PHP-Units | PHP | Yes | https://github.com/hiqdev/php-units |  |  |  |  |  |  |  |  |  |
| Cuis-Smalltalk-Aconcagua | Smalltalk | Yes | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |  |  |  |  |  |  |  |  |  |
| Measurements | PHP | Yes | https://github.com/marfurt/measurements |  |  |  |  |  |  |  |  |  |
| CSharp-UnitsOfMeasure | C# | No | https://github.com/hediet/csharp-UnitsOfMeasure |  |  |  |  |  |  |  |  |  |
| UnitsOfMeasure (#1) | C++ | No | https://github.com/ing200086/UnitsOfMeasure |  |  |  |  |  |  |  |  |  |
| UnitsOfMeasureBundle | PHP | Yes | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |  |  |  |  |  |  |  |  |  |
| UnitsOfMeasure (#2) | C# | Yes | https://github.com/capnmidnight/UnitsOfMeasure |  |  |  |  |  |  |  |  |  |
| UnitsOfMeasure (#3) | C++ | No | https://github.com/printfn/UnitsOfMeasure |  |  |  |  |  |  |  |  |  |
| Units (#17) | PHP | Yes | https://github.com/ARCANEDEV/Units |  |  |  |  |  |  |  |  |  |
| Units_of_measure | C++ | Yes | https://github.com/Skeen/units_of_measure |  |  |  |  |  |  |  |  |  |
| Units (#18) | Go | Yes | https://github.com/antha-lang/units |  |  |  |  |  |  |  |  |  |
| Units of Measure Prototype | Haskell | Yes | https://github.com/adamgundry/uom-prototype |  |  |  |  |  |  |  |  |  |
| Measure | Perl | No | https://github.com/bluefeet/Measure |  |  |  |  |  |  |  |  |  |
| Uom.Dart | Dart | Yes | https://github.com/damondouglas/uom.dart |  |  |  |  |  |  |  |  |  |
| Units-of-Measure (#2) | Java | No | https://github.com/timroejr/2.05-Units-of-Measurement |  |  |  |  |  |  |  |  |  |
| UnitsDotNet | F# | No | https://github.com/benhamner/UnitsDotNet |  |  |  |  |  |  |  |  |  |
| RockUnits | C# | Yes | https://github.com/gareth-reid/RockUnits |  |  |  |  |  |  |  |  |  |
| TundraMeasure.java | Java | Yes | https://github.com/Permafrost/TundraMeasure.java |  |  |  |  |  |  |  |  |  |
| Units (#19) | PHP | Yes | https://github.com/marando/Units |  |  |  |  |  |  |  |  |  |
| UnitOfMeasure (#1) | C# | Yes | https://github.com/Chef-Code/UnitOfMeasure |  |  |  |  |  |  |  |  |  |
| Units-api | PHP | Yes | https://github.com/shrimpza/units-api |  |  |  |  |  |  |  |  |  |
| cppDegRad | C++ | Yes | https://github.com/grahamboree/cppDegRad |  |  |  |  |  |  |  |  |  |
| Measurement with units | C++ | No | https://github.com/AndrewWasHere/measurements_with_units |  |  |  |  |  |  |  |  |  |
| Unit (#3) | VB .NET | Yes | https://github.com/AdamSpeight2008/Unit |  |  |  |  |  |  |  |  |  |
| Units-parser | Haskell | No | https://github.com/adamgundry/units-parser |  |  |  |  |  |  |  |  |  |
| Simple.Units | C# | Yes | https://github.com/oriches/Simple.Units |  |  |  |  |  |  |  |  |  |
| Class-Measure | Perl | Yes | https://github.com/bluefeet/Class-Measure |  |  |  |  |  |  |  |  |  |
| Measurements | Ruby | Yes | https://github.com/Krustal/Measurements |  |  |  |  |  |  |  |  |  |
| Purescript-Units | PureScript | Yes | https://github.com/fluffynukeit/purescript-units |  |  |  |  |  |  |  |  |  |
| Measure | Swift | No | https://github.com/sdrpa/measure |  |  |  |  |  |  |  |  |  |
| Mezur | JavaScript | Yes | https://github.com/guyisra/mezur |  |  |  |  |  |  |  |  |  |
| Measure.js | JavaScript | No | https://github.com/alnesjo/measure.js |  |  |  |  |  |  |  |  |  |
| Units (#20) | Elm | No | https://github.com/irpagnossin/units |  |  |  |  |  |  |  |  |  |
| Unit (#4) | PHP | No | https://github.com/komparu/unit |  |  |  |  |  |  |  |  |  |
| MeasurementConverter | Java | Yes | https://github.com/SBrooks75/MeasurementConverter |  |  |  |  |  |  |  |  |  |
| Uom | Ruby | Yes | https://github.com/caruby/uom |  |  |  |  |  |  |  |  |  |
| GenUnits | F# | Yes | https://github.com/halcwb/GenUnits |  |  |  |  |  |  |  |  |  |
| Ruby-Units | Ruby | Yes | https://github.com/davearonson/Ruby-Units |  |  |  |  |  |  |  |  |  |
| JavaMeasure | Java | Yes | https://github.com/tkuebler/JavaMeasure |  |  |  |  |  |  |  |  |  |
| AS3Units | ActionScript | Yes | https://github.com/erussell/AS3Units |  |  |  |  |  |  |  |  |  |
| UnitConverter (#4) | Java | Yes | https://github.com/MarioDudjak/UnitConverter |  |  |  |  |  |  |  |  |  |
| Open.Measuring | TypeScript | No | https://github.com/electricessence/Open.Measuring |  |  |  |  |  |  |  |  |  |
| Converter_Classes | Ruby | No | https://github.com/gschool-g5/converter_classes |  |  |  |  |  |  |  |  |  |
| PHPConverter | PHP | Yes | https://github.com/chapmang/PHPConverter |  |  |  |  |  |  |  |  |  |
| NGX-UOM | JavaScript | Yes | https://github.com/catellanir/ngx-uom |  |  |  |  |  |  |  |  |  |
| Physical Quantities | Smalltalk/C# | Yes | https://github.com/timdetering/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| GIM.Quantities | C# | Yes | https://github.com/togakangaroo/GIM.Quantities |  |  |  |  |  |  |  |  |  |
| JUNitConv | Java | Yes | https://github.com/duckler/JUnitConv |  |  |  |  |  |  |  |  |  |
| Kuants | Kotlin | No | https://github.com/evacchi/kuants |  |  |  |  |  |  |  |  |  |
| Dimensional | Ruby | Yes | https://github.com/cch1/Dimensional |  |  |  |  |  |  |  |  |  |
| Maser | JavaScript/Python | Yes | https://github.com/justinbangerter/maser |  |  |  |  |  |  |  |  |  |
| UnitOfMeasure (#2) | Scala | Yes | https://github.com/ricemery/unitofmeasure |  |  |  |  |  |  |  |  |  |
| Umpy | Python | Yes | https://github.com/perdixsw/umpy |  |  |  |  |  |  |  |  |  |
| SBUnits | Swift | Yes | https://github.com/EBGToo/SBUnits |  |  |  |  |  |  |  |  |  |
| Units (#21) | Haskell | Yes | https://github.com/goldfirere/units |  |  |  |  |  |  |  |  |  |
| Units (#22) | JavaScript | No | https://github.com/heygrady/Units |  |  |  |  |  |  |  |  |  |
| MKUnits | Swift | Yes | https://github.com/michalkonturek/MKUnits |  |  |  |  |  |  |  |  |  |
| JC-Units | Python | Yes | https://github.com/jason0x43/jc-units |  |  |  |  |  |  |  |  |  |
| SIUnits.jl | Julia | No | https://github.com/Keno/SIUnits.jl |  |  |  |  |  |  |  |  |  |
| Units (#23) | Go | No | https://github.com/alecthomas/units |  |  |  |  |  |  |  |  |  |
| Gu.Units | C# | Yes | https://github.com/JohanLarsson/Gu.Units |  |  |  |  |  |  |  |  |  |
| DDUnitConverter | Objective-C | Yes | https://github.com/davedelong/DDUnitConverter |  |  |  |  |  |  |  |  |  |
| CSUnits | C# | Yes | https://github.com/cureos/csunits |  |  |  |  |  |  |  |  |  |
| PHP-Conversion | PHP | Yes | https://github.com/crisu83/php-conversion |  |  |  |  |  |  |  |  |  |
| SIUnitX | TeX | Yes | https://github.com/josephwright/siunitx |  |  |  |  |  |  |  |  |  |
| Units (#24) | Scala | Yes | https://github.com/KarolS/units |  |  |  |  |  |  |  |  |  |
| UnitConverterUltimate | Java | Yes | https://github.com/physphil/UnitConverterUltimate |  |  |  |  |  |  |  |  |  |
| SI-Units | Java | Yes | https://github.com/unitsofmeasurement/si-units |  |  |  |  |  |  |  |  |  |
| Measured | Ruby | Yes | https://github.com/Shopify/measured |  |  |  |  |  |  |  |  |  |
| Units (#25) | Java | Yes | https://github.com/xxv/Units |  |  |  |  |  |  |  |  |  |
| Conversion (#1) | PHP | Yes | https://github.com/abhimanyu003/conversion |  |  |  |  |  |  |  |  |  |
| UnitConverter (#5) | Python | Yes | https://github.com/mattgd/UnitConverter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#6) | Java | No | https://github.com/sommukhopadhyay/UnitConverter |  |  |  |  |  |  |  |  |  |
| Unit-converter | PHP | Yes | https://github.com/jordanbrauer/unit-converter |  |  |  |  |  |  |  |  |  |
| HHUnitConverter | Objective-C | Yes | https://github.com/HiveHicks/HHUnitConverter |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#1) | JavaScript | Yes | https://github.com/TheMarco/Unit-Converter |  |  |  |  |  |  |  |  |  |
| Alfred-Converter | Python | Yes | https://github.com/WoLpH/alfred-converter |  |  |  |  |  |  |  |  |  |
| Unitz | JavaScript | Yes | https://github.com/ClickerMonkey/unitz |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#2) | JavaScript | No | https://github.com/war1025/Unit-Converter |  |  |  |  |  |  |  |  |  |
| UnitConverter.htm | JavaScript | Yes | https://github.com/iterami/UnitConverter.htm |  |  |  |  |  |  |  |  |  |
| UnitConverter (#7) | Java | Yes | https://github.com/impateljay/UnitConverter |  |  |  |  |  |  |  |  |  |
| Angular-Unit-Converter | JavaScript | Yes | https://github.com/alexandernst/angular-unit-converter |  |  |  |  |  |  |  |  |  |
| UnitConverterWin | C | Yes | https://github.com/NikolaiTyrMDS/UnitConverterWin |  |  |  |  |  |  |  |  |  |
| UnitConverter (#7) | Java | No | https://github.com/MarcKuniansky/UnitConverter |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#3) | Java | Yes | https://github.com/AmitKumarSah/Unit-Converter |  |  |  |  |  |  |  |  |  |
| PythonUnitConverter | Python | Yes | https://github.com/Aaron1011/PythonUnitConverter |  |  |  |  |  |  |  |  |  |
| Converter (#5) | Java | Yes | https://github.com/HanSolo/converter |  |  |  |  |  |  |  |  |  |
| Mather | Java | Yes | https://github.com/icasdri/Mather |  |  |  |  |  |  |  |  |  |
| Vandelay | C++ | Yes | https://github.com/HaikuArchives/Vandelay |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#3) | PHP | Yes | https://github.com/b-sebastian/unit-converter |  |  |  |  |  |  |  |  |  |
| Converter (#6) | C++ | No | https://github.com/stevenharradine/Converter |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#4) | C++ | Yes | https://github.com/mikeleppane/Unit-Converter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#7) | Java | No | https://github.com/Ideally/UnitConverter |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#4) | C++ | No | https://github.com/BoboTiG/unit-converter |  |  |  |  |  |  |  |  |  |
| tConverter | PHP | No | https://github.com/tankotun/tConverter |  |  |  |  |  |  |  |  |  |
| Units-Converter(#5) | C# | No | https://github.com/kolesnikova745/units-converter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#8) | Java | No | https://github.com/fnk0/UnitConverter |  |  |  |  |  |  |  |  |  |
| Converter (#7) | Java | No | https://github.com/khaldi-yass/Converter |  |  |  |  |  |  |  |  |  |
| Unit (#5) | HTML | No | https://github.com/Bingde/unit |  |  |  |  |  |  |  |  |  |
| Unit-Converter (#6) | JavaScript | Yes | https://github.com/MaicolBen/unit-converter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#9) | Python | No | https://github.com/Demoleas715/UnitConverter |  |  |  |  |  |  |  |  |  |
| Simple-Unit-Converter | JavaScript | No | https://github.com/smtaydemir/simple-unit-converter |  |  |  |  |  |  |  |  |  |
| UnitConversion (#1) | Objective-C | Yes | https://github.com/unixpickle/UnitConversion |  |  |  |  |  |  |  |  |  |
| UnitConverter (#10) | PHP | Yes | https://github.com/nfraz007/UnitConverter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#11) | Java | No | https://github.com/sunilthalore/UnitConverter |  |  |  |  |  |  |  |  |  |
| Unit | PHP | Yes | https://github.com/pounard/Unit |  |  |  |  |  |  |  |  |  |
| Converter (#8) | Objective-C | No | https://github.com/milkyNik/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#9) | Java | No | https://github.com/hirenj0009/converter |  |  |  |  |  |  |  |  |  |
| Converter (#10) | Swift | No | https://github.com/dhunten/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#11) | C++ | Yes | https://github.com/KerryL/Converter |  |  |  |  |  |  |  |  |  |
| Angular-Converter | JavaScript | Yes | https://github.com/cyrilf/angular-converter |  |  |  |  |  |  |  |  |  |
| Converter (#12) | HTML | No | https://github.com/annaavanesyan/converter |  |  |  |  |  |  |  |  |  |
| Converter (#13) | JavaScript | No | https://github.com/Urrby/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#14) | PureScript | No | https://github.com/moniyax/converter |  |  |  |  |  |  |  |  |  |
| Converter (#15) | Java | No | https://github.com/NaOHman/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#16) | Java | No | https://github.com/sunil512/Converter |  |  |  |  |  |  |  |  |  |
| Unit-Converter.js | JavaScript | No | https://github.com/angeshpokharel/unit-converter.js |  |  |  |  |  |  |  |  |  |
| Converter (#17) | Java | No | https://github.com/jessepasos/Converter |  |  |  |  |  |  |  |  |  |
| PreciseUnitConverter | JavaScript | Yes | https://github.com/bumxu/PreciseUnitConverter |  |  |  |  |  |  |  |  |  |
| Cropio_Units_Converter | C++ | Yes | https://github.com/cropio/cropio_units_converter |  |  |  |  |  |  |  |  |  |
| Converter (#18) | JavaScript | No | https://github.com/zlargon/converter |  |  |  |  |  |  |  |  |  |
| Converter (#19) | C# | No | https://github.com/sun-haha/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#20) | JavaScript | No | https://github.com/ziggy42/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#21) | Java | No | https://github.com/SurajPrasadd/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#22) | Python | No | https://github.com/hpjardon/converter |  |  |  |  |  |  |  |  |  |
| C0nv3rt3r | C# | No | https://github.com/torifat/C0nv3rt3r |  |  |  |  |  |  |  |  |  |
| Converter (#23) | Java | No | https://github.com/napnie/converter |  |  |  |  |  |  |  |  |  |
| Converter (#24) | Clojure | No | https://github.com/andreasfrom/converter |  |  |  |  |  |  |  |  |  |
| Converter (#25) | TypeScript | Yes | https://github.com/ialex90/Converter |  |  |  |  |  |  |  |  |  |
| DakaUnitConverter | Java | Yes | https://github.com/darrylfonseka/DakaUnitConverter |  |  |  |  |  |  |  |  |  |
| Converter (#26) | Python | No | https://github.com/XTremeRox/converter |  |  |  |  |  |  |  |  |  |
| UniCon | Java | No | https://github.com/davoraleksic/UniCon |  |  |  |  |  |  |  |  |  |
| MilesMeter | Swift | No | https://github.com/mirokolodii/milesmeter |  |  |  |  |  |  |  |  |  |
| Unit-Converter | JavaScript | No | https://github.com/jgalla/unit-converter |  |  |  |  |  |  |  |  |  |
| Unisum | Vue | No | https://github.com/askhat/unisum |  |  |  |  |  |  |  |  |  |
| Unit_Converter | Ruby | No | https://github.com/samuels410/unit_converter |  |  |  |  |  |  |  |  |  |
| Units (#26) | PHP | No | https://github.com/anstag/units |  |  |  |  |  |  |  |  |  |
| Convertoroid | Java | No | https://github.com/abhii2028/Convertoroid |  |  |  |  |  |  |  |  |  |
| Convertor | C++ | Yes | https://github.com/mihaelateo/Convertor |  |  |  |  |  |  |  |  |  |
| Converter (#27) | C++ | Yes | https://github.com/scruff3y/Converter |  |  |  |  |  |  |  |  |  |
| Converter (#28) | Java | No | https://github.com/urielvan/converter |  |  |  |  |  |  |  |  |  |
| Converter (#29) | HTML | No | https://github.com/AmitBuchnik/Converter |  |  |  |  |  |  |  |  |  |
| UnitConverter (#12) | Objective-C | No | https://github.com/basicsbeauty/UnitConverter |  |  |  |  |  |  |  |  |  |
| Groovy-Unitconverter | Groovy | No | https://github.com/rhyolight/groovy-unitconverter |  |  |  |  |  |  |  |  |  |
| Unit-Converter | JavaScript | Yes | https://github.com/GTLook/Unit-Converter |  |  |  |  |  |  |  |  |  |
| KingConverter | JavaScript | No | https://github.com/ryanr1230/KingConverter |  |  |  |  |  |  |  |  |  |
| UnitMan | C# | Yes | https://github.com/mbeloshapkin/UnitMan |  |  |  |  |  |  |  |  |  |
| UnitConverter (#13) | C# | No | https://github.com/github-ganesh/UnitConverter |  |  |  |  |  |  |  |  |  |
| PyUnitConverter | Python | Yes | https://github.com/jyri78/PyUnitConverter |  |  |  |  |  |  |  |  |  |
| Converter (#30) | Java | No | https://github.com/atsang36/Unit_Converter |  |  |  |  |  |  |  |  |  |
| Converter (#31) | C# | No | https://github.com/pfthroaway/Converter |  |  |  |  |  |  |  |  |  |
| TemperatureConverter | Python | No | https://github.com/bobo333/TemperatureConverter |  |  |  |  |  |  |  |  |  |
| BGConverter | C++ | No | https://github.com/bugeaggeorge/BGConverter |  |  |  |  |  |  |  |  |  |
| Quantity | Ruby | Yes | https://github.com/bhuga/quantity |  |  |  |  |  |  |  |  |  |
| Grobid-Quantities | JavaScript | No | https://github.com/kermitt2/grobid-quantities |  |  |  |  |  |  |  |  |  |
| UDUNITS-2 | C | Yes | https://github.com/Unidata/UDUNITS-2 |  |  |  |  |  |  |  |  |  |
| Quantities-Comparison | Python | No | https://github.com/tbekolay/quantities-comparison |  |  |  |  |  |  |  |  |  |
| Purescript-Quantities | PureScript | Yes | https://github.com/sharkdp/purescript-quantities |  |  |  |  |  |  |  |  |  |
| Quantities | Haskell | Yes | https://github.com/jdreaver/quantities |  |  |  |  |  |  |  |  |  |
| Quantities | Swift | Yes | https://github.com/BradLarson/Quantities |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities | Python | Yes | https://github.com/juhasch/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| Nim-Units | Nim | No | https://github.com/def-/nim-units |  |  |  |  |  |  |  |  |  |
| Quantity | PHP | Yes | https://github.com/phospr/quantity |  |  |  |  |  |  |  |  |  |
| Quantities | R | Yes | https://github.com/r-quantities/quantities |  |  |  |  |  |  |  |  |  |
| Quantiphy | Python | Yes | https://github.com/KenKundert/quantiphy |  |  |  |  |  |  |  |  |  |
| ScientificQuantities | C++ | Yes | https://github.com/nourani/ScientificQuantities |  |  |  |  |  |  |  |  |  |
| Quantities | MatLab | Yes | https://github.com/mikofski/Quantities |  |  |  |  |  |  |  |  |  |
| Physical-Quantities | Python | Yes | https://github.com/hplgit/physical-quantities |  |  |  |  |  |  |  |  |  |
| ScalaQuantity | Scala | Yes | https://github.com/zzorn/ScalaQuantity |  |  |  |  |  |  |  |  |  |
| Misu | Python | Yes | https://github.com/cjrh/misu |  |  |  |  |  |  |  |  |  |
| Physical-Quantities | Haskell | No | https://github.com/mtesseract/physical-quantities |  |  |  |  |  |  |  |  |  |
| Lua-Physical | Lua | Yes | https://github.com/tjenni/lua-physical |  |  |  |  |  |  |  |  |  |
| All_In_One_Converter | Python | Yes | https://github.com/pradeepjairamani/All_in_one_converter |  |  |  |  |  |  |  |  |  |
| QuantitiesLib | C# | No | https://github.com/isabellaalstrom/QuantitiesLib |  |  |  |  |  |  |  |  |  |
| Quantities | C++ | Yes | https://github.com/djbarker/quantities |  |  |  |  |  |  |  |  |  |
| Quantities | Haskell | No | https://github.com/mtesseract/quantities |  |  |  |  |  |  |  |  |  |
| Quantity | Ruby | Yes | https://github.com/aportnov/quantity |  |  |  |  |  |  |  |  |  |
| Quantities | Batchfile | Yes | https://github.com/greatfriends/Quantities |  |  |  |  |  |  |  |  |  |
| Quantities | JavaScript | No | https://github.com/jdrew1303/quantities |  |  |  |  |  |  |  |  |  |
| Quantities | C# | Yes | https://github.com/atmoos/Quantities |  |  |  |  |  |  |  |  |  |
| Physics-Measurement | JavaScript | Yes | https://github.com/victorpotasso/physics-measurement |  |  |  |  |  |  |  |  |  |
| RealizedQuantities | Python | No | https://github.com/BayerSe/RealizedQuantities |  |  |  |  |  |  |  |  |  |
| PyQuantity | Python | Yes | https://github.com/gabbpuy/PyQuantity |  |  |  |  |  |  |  |  |  |
| JS-Quantities | JavaScript | No | https://github.com/mugendi/js-quantities |  |  |  |  |  |  |  |  |  |
| Scala-Quantities | Scala | No | https://github.com/Lastik/scala-quantities |  |  |  |  |  |  |  |  |  |
| ConverterApp | C# | Yes | https://github.com/halezmo/ConverterApp |  |  |  |  |  |  |  |  |  |
| Sundew.Quantities | C# | Yes | https://github.com/hugener/Sundew.Quantities |  |  |  |  |  |  |  |  |  |
| Units (#27) | C# | No | https://github.com/cardassianscot/Units |  |  |  |  |  |  |  |  |  |
| Meteor-Quantities | JavaScript | Yes | https://github.com/luzlab/meteor-quantities |  |  |  |  |  |  |  |  |  |
| Quant | Python | No | https://github.com/colecocomo/quant |  |  |  |  |  |  |  |  |  |
| Quantity | Clojure | Yes | https://github.com/spellman/quantity |  |  |  |  |  |  |  |  |  |
| Convert-Quantities | JavaScript | Yes | https://github.com/kendru/convert-quantities |  |  |  |  |  |  |  |  |  |
| PhysicalQuantities | C# | No | https://github.com/KorzunK/PhysicalQuantities |  |  |  |  |  |  |  |  |  |
| Quantities.jl | Julia | No | https://github.com/ElOceanografo/Quantities.jl |  |  |  |  |  |  |  |  |  |
| Alchemist | Ruby | Yes | https://github.com/halogenandtoast/alchemist |  |  |  |  |  |  |  |  |  |
| UnitConversion (#2) | C# | Yes | https://github.com/gkampolis/UnitConversion |  |  |  |  |  |  |  |  |  |
| Currency | Java | No | https://github.com/billthefarmer/currency |  |  |  |  |  |  |  |  |  |
| Convert.js | JavaScript | Yes | https://github.com/YazilimMuhendisiyizBiz/convert.js |  |  |  |  |  |  |  |  |  |
| Convertor | PHP | Yes | https://github.com/olifolkerd/convertor |  |  |  |  |  |  |  |  |  |
| UnitConverter (#14) | Swift | No | https://github.com/SwiftEducation/UnitConverter |  |  |  |  |  |  |  |  |  |
| Alfred-Convert | Python | Yes | https://github.com/deanishe/alfred-convert |  |  |  |  |  |  |  |  |  |
| MeasureBundle | PHP | Yes | https://github.com/akeneo/MeasureBundle |  |  |  |  |  |  |  |  |  |
| Convertr | R | Yes | https://github.com/ropenscilabs/convertr |  |  |  |  |  |  |  |  |  |
| Ethereumjs-units | JavaScript | No | https://github.com/ethereumjs/ethereumjs-units |  |  |  |  |  |  |  |  |  |
| Metric | Java | Yes | https://github.com/gnapse/metric |  |  |  |  |  |  |  |  |  |
| Jsunitconverter | JavaScript | Yes | https://github.com/jerodvenemafm/jsunitconverter |  |  |  |  |  |  |  |  |  |
| Sius | Java | Yes | https://github.com/mbe24/sius |  |  |  |  |  |  |  |  |  |
| Unit | JavaScript | Yes | https://github.com/smartcar/unit |  |  |  |  |  |  |  |  |  |
| Rails-Units | Ruby | No | https://github.com/scpike/rails-units |  |  |  |  |  |  |  |  |  |
| Hazpy.Unit-conversion | Python | No | https://github.com/NOAA-ORR-ERD/hazpy.unit_conversion |  |  |  |  |  |  |  |  |  |
| Convert | Python | No | https://github.com/sugarlabs/convert |  |  |  |  |  |  |  |  |  |
| Ktunits | Kotlin | No | https://github.com/sargunv/ktunits |  |  |  |  |  |  |  |  |  |
| Unit-formula | Common Lisp | Yes | https://github.com/Ramarren/unit-formula |  |  |  |  |  |  |  |  |  |
| Silphid.Unity | C# | No | https://github.com/silphid/silphid.unity |  |  |  |  |  |  |  |  |  |
| Physikal (#2) | Kotlin | No | https://github.com/Tenkiv/Physikal |  |  |  |  |  |  |  |  |  |
| NUCOS | JavaScript | No | https://github.com/NOAA-ORR-ERD/NUCOS |  |  |  |  |  |  |  |  |  |
| Node-units | JavaScript | Yes | https://github.com/brettlangdon/node-units |  |  |  |  |  |  |  |  |  |
| Xiny | Go | Yes | https://github.com/bcicen/xiny |  |  |  |  |  |  |  |  |  |
| Units.js | JavaScript | Yes | https://github.com/jairtrejo/units.js |  |  |  |  |  |  |  |  |  |
| GenUnitApp | JavaScript | Yes | https://github.com/halcwb/GenUnitApp |  |  |  |  |  |  |  |  |  |
| Units (#28) | C++ | Yes | https://github.com/lonkamikaze/units |  |  |  |  |  |  |  |  |  |
| Unitconverter-Android | Java | Yes | https://github.com/dbrant/unitconverter-android |  |  |  |  |  |  |  |  |  |
| Unit.styl | JavaScript | Yes | https://github.com/diessica/unit.styl |  |  |  |  |  |  |  |  |  |
| Conversionr | R | Yes | https://github.com/alexnakagawa/conversionr |  |  |  |  |  |  |  |  |  |
| Math-units | Perl | Yes | https://github.com/kenfox/Math-Units |  |  |  |  |  |  |  |  |  |
| Converge | Swift | No | https://github.com/daneden/Converge |  |  |  |  |  |  |  |  |  |
| UnitConvert | JavaScript | Yes | https://github.com/agnoster/unitology |  |  |  |  |  |  |  |  |  |
| Unit-Conversion | PHP | No | https://github.com/h4kuna/unit-conversion |  |  |  |  |  |  |  |  |  |
| Ocalm-units | OCalm | No | https://github.com/pelzlpj/ocaml-units |  |  |  |  |  |  |  |  |  |
| Convertinator | C# | Yes | https://github.com/hartez/Convertinator |  |  |  |  |  |  |  |  |  |
| NGunits | Java | Yes | https://github.com/erussell/ngunits |  |  |  |  |  |  |  |  |  |
| Units (#29) | Swift | Yes | https://github.com/chrisjeane/Units |  |  |  |  |  |  |  |  |  |
| UnitConversion (#3) | Python | Yes | https://github.com/UnitConversion/unitConversion |  |  |  |  |  |  |  |  |  |
| Metiri | JavaScript | Yes | https://github.com/GCheung55/metiri |  |  |  |  |  |  |  |  |  |
| Scala-units | Scala | Yes | https://github.com/bwkimmel/scala-units |  |  |  |  |  |  |  |  |  |
| Convert-units | Ruby | Yes | https://github.com/tanvir002700/convert_unit |  |  |  |  |  |  |  |  |  |
| Unit | Go | No | https://github.com/kormoc/unit |  |  |  |  |  |  |  |  |  |
| Django-Unit-Field | Python | Yes | https://github.com/kohout/django-unit-field |  |  |  |  |  |  |  |  |  |
| Elm-Units | Elm | No | https://github.com/anfelor/elm-units |  |  |  |  |  |  |  |  |  |
| Aegon | Python | Yes | https://github.com/lukaskollmer/aegon |  |  |  |  |  |  |  |  |  |
| Units (#30) | PHP | Yes | https://github.com/rmasters/units |  |  |  |  |  |  |  |  |  |
| Unit_Conversion | Ruby | Yes | https://github.com/eternal44/unit_conversion |  |  |  |  |  |  |  |  |  |
| Maegor | JavaScript | Yes | https://github.com/lukaskollmer/maegor |  |  |  |  |  |  |  |  |  |
| Memory_Units | Rust | No | https://github.com/pepyakin/memory_units |  |  |  |  |  |  |  |  |  |
| Units-System | Ruby | Yes | https://github.com/jgoizueta/units-system |  |  |  |  |  |  |  |  |  |
| Physical | C++ | Yes | https://github.com/olsonse/physical |  |  |  |  |  |  |  |  |  |
| Conversion (#3) | Java | No | https://github.com/VaishnavRajesh/conversion |  |  |  |  |  |  |  |  |  |
| Conversion (#4) | Java | No | https://github.com/SoftronixGlobal/Conversion |  |  |  |  |  |  |  |  |  |
| Conversion (#5) | Java | No | https://github.com/2aredford/Conversion |  |  |  |  |  |  |  |  |  |
| Conversion (#6) | C++ | Yes | https://github.com/simonmeaden/conversion |  |  |  |  |  |  |  |  |  |
| Gorilla | Ruby | Yes | https://github.com/stephencelis/gorilla |  |  |  |  |  |  |  |  |  |
| Units by Stak Digital | JavaScript | Yes | https://github.com/stak-digital/units |  |  |  |  |  |  |  |  |  |
| Conversion (#7) | Java | No | https://github.com/ali-hamad/Conversion |  |  |  |  |  |  |  |  |  |
| Conversion (#8) | Java | No | https://github.com/ironwire/Conversion |  |  |  |  |  |  |  |  |  |
| Unitmaster | C++ | No | https://github.com/oswjk/unitmaster |  |  |  |  |  |  |  |  |  |
| ConversionsApp | Objective-C | No | https://github.com/JoeCortopassi/ConversionsApp |  |  |  |  |  |  |  |  |  |
| QtUnits | C++ | Yes | https://github.com/hrobeers/QtUnits |  |  |  |  |  |  |  |  |  |
| Unit_Soup | Ruby | Yes | https://github.com/rutvij47/unit_soup |  |  |  |  |  |  |  |  |  |
| Units (#32) | Ruby | Yes | https://github.com/woahdae/units |  |  |  |  |  |  |  |  |  |
| Unit_Conversion | Python | Yes | https://github.com/bastihaase/unit_conversion |  |  |  |  |  |  |  |  |  |
| convertR | R | Yes | https://github.com/colin-fraser/convertR |  |  |  |  |  |  |  |  |  |
| UnitConversion (#4) | C# | Yes | https://github.com/Mecteral/UnitConversion |  |  |  |  |  |  |  |  |  |
| UnitConversion (#5) | Java | No | https://github.com/yadavparmatma/UnitConversion |  |  |  |  |  |  |  |  |  |
| UnitConversion (#6) | Java | Yes | https://github.com/yfl007/UnitConversion |  |  |  |  |  |  |  |  |  |
| UnitConversion (#7) | C# | No | https://github.com/vsooraj/UnitsConversion |  |  |  |  |  |  |  |  |  |
| Unit-Conversion | JavaScript | Yes | https://github.com/srimanthk/unit-conversion |  |  |  |  |  |  |  |  |  |
| UnitComboLib | C# | No | https://github.com/Dirkster99/UnitComboLib |  |  |  |  |  |  |  |  |  |
| ConversionApp2 | Java | No | https://github.com/dpinero/ConversionApp2 |  |  |  |  |  |  |  |  |  |
| JSR 275 | Java | Yes | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |  |  |  |  |  |  |  |  |  |
| JSR 363 | Java | Yes | https://jcp.org/en/jsr/detail?id=363 |  |  |  |  |  |  |  |  |  |
| Units (#31) | Tcl | Yes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |  |  |  |  |  |  |  |  |  |
| Units (#32) | R | Yes | https://cran.r-project.org/web/packages/units/index.html |  |  |  |  |  |  |  |  |  |
| Quantified | Ruby | Yes | https://github.com/Shopify/quantified | - |  |  | Only has length + mass, make tier 2 | https://github.com/Shopify/quantified |  |  |  |  |
| Dimensional | Haskell | Yes | https://github.com/bjornbm/dimensional |  |  |  |  |  |  |  |  |  |
| Units (#33) | Haskell | Yes | https://hackage.haskell.org/package/units |  |  |  |  |  |  |  |  |  |
| PHYSICS | Multiple | Yes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |  |  |  |  |  |  |  |  |  |
| The Quantity Library | C++ | No | http://home.xnet.com/~msk/quantity/quantity.html |  |  |  |  |  |  |  |  |  |
