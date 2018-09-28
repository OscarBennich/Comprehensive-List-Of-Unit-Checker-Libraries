# A Comprehensive List of Unit Checker Libraries
## Abstract
In scientific applications, physical quantities and units ofmeasurement are used regularly. If the inherent incompati-bility between these units is not handled properly it can leadto major, and sometimes catastrophic, problems. Althoughthe risk of a miscalculation is high and the cost equally so, al-most none of the major programming languages has supportfor physical quantities. Instead, scientific code developersoften make their own tools or rely on external libraries tohelp them spot or prevent these mistakes.We employed a systematic approach to examine and anal-yse all available physical quantity open-source libraries. Thesearch results were then condensed into 82 libraries, cho-sen from approximately 3700 search results across sevenrepository hosting sites, as being the most comprehensiveand well-developed. In this group, 30 different programminglanguages are represented. Out of these 82 libraries, 38 havebeen updated within the last two years. These 38 are sum-marised in this paper as they are deemed the most relevant.The conclusion we draw from these results is that there isclearly too much diversity, duplicated efforts, a lack of codesharing and harmonisation to encourage use.

## Short description 
[TBD] 

You can contact me at: Oscar.Bennich@gmail.com

If you would like to read more, the master thesis can be found here: http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-353817 

The article can be found here: [TBD] 

## Data gathering information
Repository sites that were checked:
| Site Name  | Site Link |
| ------------- | ------------- |
| GitHub.com | https://github.com/ |
| Bit-Bucket.org | https://bitbucket.org/ |
| GitLab.com  | https://about.gitlab.com/  |
| SourceForge.net  | https://sourceforge.net/ |
| CodeProject.com  | https://www.codeproject.com/ |
| LaunchPad.net  | https://launchpad.net/  |
| Savannah.gnu.org  | http://savannah.gnu.org/ |

Keywords that were used: 
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

## Links to different parts
- [Top tier libraries](#top-tier-libraries)

- [Second tier libraries](#second-tier-libraries)

- [All valid projects](#valid-projects)

- [Tools and applications](#tools)

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
| BoostUnits | C++ | ~200 units, 20 prefixes, ~150 constants | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |
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

## Valid projects
| Name | Language | Library or Tool | Source / URL |
|-----------------------------------------------------------------------------------------------------------------------------|-------------------|-----------------|-------------------------------------------------------------------------------------------------|
| Phriky-Units | Python | Tool | https://github.com/unl-nimbus-lab/phriky-units |
| UnitsNet | C# | Library | https://github.com/angularsen/UnitsNet |
| ParamPool | Python | Tool | https://github.com/hplgit/parampool |
| BoostUnits | C++ | Library | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |
| Convert Units (#1) | Java | Library | https://github.com/ben-ng/convert-units |
| Units (#1) | C++ | Library | https://github.com/nholthaus/units |
| Unit (#1) | Go | Library | https://github.com/martinlindhe/unit |
| Pint | Python | Library | https://github.com/hgrecco/pint |
| UnitConversionLib | C# | Library | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| EiffelUnits | Eiffel | Library | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Natu | Python | Library | https://github.com/kdavies4/natu |
| Buckingham | Python | Library | https://github.com/mdipierro/buckingham |
| Magnitude (#1) | Python | Library | https://github.com/juanre/magnitude |
| Units (#2) | Python | Library | https://bitbucket.org/adonohue/units |
| Unum (#1) | Python | Library | https://bitbucket.org/kiv/unum |
| Scimath | Python | Library | https://github.com/enthought/scimath |
| Python Quantities | Python | Library | https://github.com/python-quantities/python-quantities |
| Astropy | Python | Library | https://github.com/astropy/astropy |
| CF_Units | Python | Library | https://github.com/SciTools/cf_units |
| DimPy | Python | Library | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| NumericalUnits | Python | Tool | https://github.com/sbyrnes321/numericalunits |
| Efficient Scalars in Scala | Scala | Library | http://russp.us/scalar-scala.htm |
| Efficient Scalars in Python | Python | Library | http://russp.us/scalar-python.htm |
| Units of Measure (#1) | C# | Library | https://archive.codeplex.com/?p=unitsofmeasure |
| Units of Measurement | C# | Other | https://github.com/mangh/unitsofmeasurement |
| Physical Measure | C# | Library | https://github.com/KiloBravoLima/PhysicalMeasure |
| Quantity System | C# | Library | https://github.com/ibluesun/QuantitySystem |
| Quantity Types | C# | Library | https://github.com/objorke/QuantityTypes |
| NGenericDimensions | C# | Library | https://github.com/MafuJosh/NGenericDimensions |
| Quantities.net | C# | Library | https://sourceforge.net/projects/quantitiesnet/ |
| .NET Unit Conversion Library | C# | Library | https://sourceforge.net/projects/unitcon/ |
| Measurement Unit Conversion Library (#1) | C# | Library | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Unit of Measure Library for .NET | C# | Library | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Unit of Measure Validator for C# | C# | Library | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Working with Units and Amounts | C# | Library | https://www.codeproject.com/script/Articles/ListVersions.aspx?aid=611731 |
| GNU Units | C# | Tool | https://www.gnu.org/software/units/ |
| RedStar.Amounts | C# | Library | https://github.com/petermorlion/RedStar.Amounts/ |
| Units of Measurement Systems | Java | Library | https://github.com/unitsofmeasurement/uom-systems |
| CaliperSharp | C# | Library | https://github.com/point85/CaliperSharp |
| Units (#3) | Java | Library | https://github.com/SamCarlberg/units |
| Units (#4) | C# | Library | https://github.com/engineers-tools/Units |
| Cubico | C# | Library | https://github.com/irperez/Cubico |
| Unitful.jl | Julia | Library | https://github.com/ajkeller34/Unitful.jl |
| PHP Unit Conversion | PHP | Library | https://github.com/pimlie/php-unit-conversion |
| The Units of Measure Library | C++ | Library | https://sourceforge.net/projects/tuoml/ |
| Squants | Scala | Library | https://github.com/typelevel/squants |
| Quantities (#1) | Idris | Library | https://github.com/timjb/quantities |
| Rink | Rust | Tool | https://github.com/tiffany352/rink-rs |
| Unit API | Java | Library | https://github.com/unitsofmeasurement/unit-api |
| PhysUnits (#1) | C++ | Library | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| Coulomb | Scala | Library | https://github.com/erikerlandson/coulomb |
| Metric (#1) | Rust | Library | https://github.com/coder543/metric |
| ScalaU | Scala | Library | https://github.com/adrianfr/scalau |
| Units (#5) | Go | Library | https://github.com/smyrman/units |
| Superquants | Scala | Library | https://github.com/rudogma/scala-superquants |
| Elixir Unit Converter | Elixir | Library | https://github.com/carturoch/ex_uc |
| Metric (#2) | Nim | Library | https://github.com/mjendrusch/metric |
| Units of Measure (#2) | Kotlin | Library | https://github.com/kunalsheth/units-of-measure |
| Units (#6) | C++ | Library | https://github.com/tonypilz/units |
| Units D | D | Library | https://github.com/nordlow/units-d |
| Quantities (#2) | D | Library | https://github.com/biozic/quantities |
| Measures with Dimensions | Racket | Library | https://github.com/AlexKnauth/measures-with-dimensions |
| Units and Measurements | Racket | Library | https://github.com/Metaxal/measures |
| Units (#7) | Multiple | Library | https://github.com/saroad2/units |
| Caliper | Java | Library | https://github.com/point85/caliper |
| Uncodium.Units | F# | Library | https://github.com/stefanmaierhofer/Uncodium.Units |
| PHP Units of Measure | PHP | Library | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |
| SIUnits (#1) | Haskell | Library | https://github.com/joewkr/SIUnits |
| Physikal | Kotlin | Library | https://github.com/Tenkiv/Physikal |
| Engineering | C# | Library | https://github.com/zhofre/engineering |
| ProgParam | C++ | Library | https://github.com/qPCR4vir/ProgParam |
| InkUnits | Swift | Library | https://github.com/angelsolaorbaiceta/InkUnits |
| Flowsnake | JavaScript | Library | https://github.com/Eldelshell/flowsnake |
| Insect | PureScript | Tool | https://github.com/sharkdp/insect |
| Ruby Units | Ruby | Library | https://github.com/olbrich/ruby-units |
| JS-quantities | JavaScript | Library | https://github.com/gentooboontoo/js-quantities |
| Dimensioned | Rust | Library | https://github.com/paholg/dimensioned |
| SwiftMeasurement | Swift | Library | https://github.com/ken0nek/SwiftMeasurement |
| Units 2 | Clojure | Library | https://github.com/mfey/units2 |
| Units (#8) | JavaScript | Tool | https://github.com/dohliam/units |
| Smart Units | Sidef | Tool | https://github.com/trizen/smart-units |
| JNum | Java | Library | https://github.com/attipaci/jnum |
| MagickScience | C++ | Library | https://github.com/Iarfen/MagickScience |
| Unitwise | Ruby | Library | https://github.com/joshwlewis/unitwise |
| Unit.py | Python | Library | https://github.com/fabian0010/Unit.py |
| Chimp | Python | Tool | https://github.com/mhetrerajat/chimp |
| Libquantify | C++ | Library | https://github.com/damianorenfer/libquantify |
| Constants and Units | MatLab | Library | https://github.com/mariomerinomartinez/constants_and_units |
| UOM-Domain | Java | Library | https://github.com/unitsofmeasurement/uom-domain |
| Units (#9) | C# | Library | https://github.com/LabyrinthApps/Units |
| Scale | Swift | Library | https://github.com/onmyway133/Scale |
| XamConverter | C# | Tool | https://github.com/brminnick/XamConverter |
| UnitConverter (#1) | Java | Tool | https://github.com/nevack/UnitConverter |
| SIConv | Haskell | Library | https://github.com/owainlewis/conventional-si-unit-converter |
| Convert | Swift | Library | https://github.com/danielbyon/Convert |
| Convertee | JavaScript | Tool | https://github.com/isquaredcreative/Convertee |
| Converter (#1) | PHP | Library | https://github.com/cartalyst/converter |
| Conversion Calculator | C++ | Tool | https://github.com/dtuivs/Converter |
| Quantify | Ruby | Library | https://github.com/spatchcock/quantify |
| SY | Ruby | Library | https://github.com/boris-s/sy |
| FURY | Fortran | Library | https://github.com/szaghi/FURY |
| PhysicalQuantities (#1) | Common Lisp | Library | https://github.com/mrossini-ethz/physical-quantities |
| UOM | Ruby | Library | https://github.com/madriska/uom |
| Physical Units for Matlab | MatLab | Library | https://github.com/sky-s/physical-units-for-matlab |
| VUnits | Java | Library | https://github.com/vaslabs/vunits |
| PhysicalQuantities (#2) | C# | Library | https://github.com/timdetering/PhysicalQuantities |
| PhysicalQuantities (#5) | Haskell | Library | https://github.com/fehu/PhysicalQuantities |
| Python-Physical | Python | Library | https://github.com/EdwinChan/python-physical |
| PhysicalValue | Swift | Library | https://github.com/antonvmironov/PhysicalValue |
| Lathexa Units | JavaScript | Library | https://github.com/lethexa/lethexa-units |
| Units.jl (#2) | Julia | Library | https://github.com/autocorr/Units.jl |
| M2py | Python/Matlab | Tool | https://github.com/caiorss/m2py |
| Units (#11) | Go | Library | https://github.com/zn8nz/units |
| AutoUnits | C++ | Library | https://github.com/Fifty-Nine/AutoUnits |
| Physical Math | Python | Library | https://github.com/matthagy/physmath |
| Dimanalyser | Java | Library | https://github.com/cymi/dimanalyser |
| Dftu | C++ | Library | https://github.com/triblatron/dftu |
| Scaler | Shell | Tool | https://github.com/emugel/scaler |
| Physcon | Python | Library | https://github.com/georglind/physcon |
| Praktool | Python | Tool | https://github.com/zombofant/praktool |
| Units-v2 | C++ | Library | https://github.com/Corristo/units-v2 |
| UDUnits | Julia | Library | https://github.com/Alexander-Barth/UDUnits.jl |
| Quantity.Net | C# | Library | https://github.com/bcachet/Quantity.Net |
| ParamPy | Python | Library | https://github.com/matthewwardrop/python-parampy |
| UnitManipulationLibrary | C++ | Library | https://github.com/OuaisBla/UnitManipulationLibrary |
| Dimension-TF | Haskell | Library | https://github.com/nushio3/dimensional-tf |
| Phys-Types | C++ | Library | https://github.com/akubera/phys_types |
| Unit | C++/CMake/Python | Library | https://github.com/njoy/unit |
| Pyvalem | Python | Library | https://github.com/xnx/pyqn |
| ValueWithUnit | C# | Library | https://github.com/vbfox/ValueWithUnit |
| UnitKit | Swift | Library | https://github.com/otaviocc/UnitKit |
| qMetrics | C++ | Tool | https://launchpad.net/qmetrics |
| SimpleUnitConverter | C | Tool | https://launchpad.net/simpleunitconverter |
| o2scl | C | Library | https://github.com/awsteiner/o2scl |
| Units and measures for C++ 11 | C++ | Library | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |
| Using physical quantities and units of measure in C# programs | C# | Library | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |
| Decibel Units of Measurement with C# Framework | C# | Library | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | C# | Tool | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |
| Quantities, Units, and Values: An Object Oriented Implementation | C | Library | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |
| Automatic Conversion of Physical Units | C# | Library | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |
| Unit Conversions in C#/WPF | C# | Other | https://www.codeproject.com/Articles/30569/Unit-Conversions-in-C-WPF |
| TCX Unit Conversion Library | C++ | Library | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |
| Complete Unit Conversion Sample in C# .NET | C# | Other | https://www.codeproject.com/Articles/22470/Complete-Unit-Conversion-Sample-in-C-NET |
| Measurement Unit Conversion Library (#2) | C# | Library | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |
| International System of Units Notation | C# | Library | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |
| Converting a value to an SI Unit String | C# | Library | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |
| Validation Dimensions of Physical Quantities .NET | C# | Tool | https://www.codeproject.com/Tips/1005796/Validation-Dimensions-of-Physical-Quantities-NET |
| Application of C++11 User-Defined Literals to Handling Scientific Quantities, Number Representation and String Manipulation | C++ | Other | https://www.codeproject.com/Articles/447922/Application-of-Cplusplus-User-Defined-Literals-t |
| Units of measurement for Ada | Ada | Library | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |
| Unit Management Framework | Java | Library | https://sourceforge.net/projects/quantitymanager/?source=directory |
| UOM Conversion Library | Java | Library | https://sourceforge.net/projects/uomcl/?source=directory |
| UnitParser | C# | Library | https://www.codeproject.com/Articles/1211504/UnitParser |
| Libre Unit Conveter | C# | Tool | https://sourceforge.net/projects/libreunitconverter/?source=directory |
| ConvertAll | Python | Tool | https://sourceforge.net/projects/convertall/?source=directory |
| NumericalChameleon | Java | Library | https://sourceforge.net/projects/numchameleon/?source=directory |
| JFX Konwerter | Java | Tool | https://sourceforge.net/projects/jfx-konwerter/?source=directory |
| Unit Converter (#2) | Scratch | Tool | https://sourceforge.net/projects/unitconverter12/?source=directory |
| MAIA Unit Converter | C++ | Tool | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Unit Conveter (#3) | C# | Tool | https://sourceforge.net/projects/unitconversion/?source=directory |
| Converter (#2) | Java | Tool | https://sourceforge.net/projects/con-vert/?source=directory |
| LibreEngineering | Python | Tool | https://sourceforge.net/projects/libreeng/ |
| UNeedIT Converter | C# | Tool | https://sourceforge.net/projects/uneedconverter/?source=directory |
| Unit Converter (#4) | Python | Tool | https://sourceforge.net/projects/unit-converter/?source=directory |
| Portable Unit Converter | JavaScript | Tool | https://sourceforge.net/projects/puc/?source=directory |
| Libunits | C | Library | https://sourceforge.net/projects/libunits/?source=directory |
| Web Unit Converter | C# | Tool | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| ChemicalA | C++ | Tool | https://sourceforge.net/projects/chemicala/?source=directory |
| Computing with Units | Java | Tool | https://sourceforge.net/projects/units-in-java/?source=directory |
| EngineeringCalculator | C++ | Tool | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| Quick Unit Converter | Java | Tool | https://sourceforge.net/projects/qunitconverter/?source=directory |
| Unit Converter (#5) | REBOL | Tool | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| ConverTo | C++ | Tool | https://sourceforge.net/projects/converto/?source=directory |
| UConverter | Java | Tool | https://sourceforge.net/projects/uconverter/?source=directory |
| Quantities (#3) | C++ | Library | https://sourceforge.net/projects/quantity/?source=directory |
| Magnitude (#2) | Java | Library | https://sourceforge.net/projects/magnitude/?source=directory |
| PyPhys Class Library | Python | Library | https://sourceforge.net/projects/pyphys/?source=directory |
| Physical | C++ | Library | https://sourceforge.net/projects/physical/?source=directory |
| mcs::units | C++ | Library | https://sourceforge.net/projects/mcs-units/?source=directory |
| Quan | C++ | Library | https://sourceforge.net/projects/quan/?source=directory |
| Unum (#2) | Python | Library | https://sourceforge.net/projects/unum/?source=directory |
| puny | Python | Library | https://sourceforge.net/projects/puny/?source=directory |
| JQuantity: Precision Math Java Framework | Java | Library | https://sourceforge.net/projects/jquantity/?source=directory |
| GodSend | PHP | Tool | https://sourceforge.net/projects/godsend/?source=directory |
| Java library and framework: quantity | Java | Library | https://sourceforge.net/projects/javaquantity/?source=directory |
| PhysicalUnits (#2) | C++ | Library | https://sourceforge.net/projects/physicalunits/?source=directory |
| QUDAL | C++ | Library | https://sourceforge.net/projects/qudal/?source=directory |
| C++ Unit Library | C++ | Library | https://sourceforge.net/projects/cppunitlibrary/?source=directory |
| UnitsC++ | C++ | Library | https://sourceforge.net/projects/unitscpp/?source=directory |
| C++ Units | C++ | Library | https://sourceforge.net/projects/cppunits/?source=directory |
| JConvert | Java | Tool | https://sourceforge.net/projects/jconvert/?source=directory |
| Unit Var | Python | Library | https://sourceforge.net/projects/unitvar/?source=directory |
| SIMConverter | C# | Tool | https://sourceforge.net/projects/simconverter/?source=directory |
| Java Measure | Java | Library | https://sourceforge.net/projects/javameasure/?source=directory |
| Esos | C++ | Tool | https://sourceforge.net/projects/esos/?source=directory |
| Punits - Pluggable units | C | Tool | https://sourceforge.net/projects/punits/?source=directory |
| Python Unit Conversion Library | Python | Library | https://sourceforge.net/projects/pythonconvert/?source=directory |
| .NET Unit Conversion Library | C# | Library | https://sourceforge.net/projects/unitcon/?source=directory |
| SI -- A Scala Library of Units of Measurement | Scala | Library | https://gitlab.com/h2b/SI |
| Red-units | Red | Library | https://gitlab.com/maxvel/red-units |
| Units (#12) | C++ | Library | https://gitlab.com/eclufsc/eda/units |
| .NET Units of Measure | C# | Library | https://bitbucket.org/Thecentury/.net-units-of-measure |
| BeConverter | C++ | Tool | https://bitbucket.org/Teknomancer/beconverter |
| Unit (#2) | Java | Tool | https://bitbucket.org/hansolo/unit |
| Unit-converter (#1) | Python | Tool | https://bitbucket.org/brayvasq/unit-converter |
| Unum (#3) | Python | Library | https://bitbucket.org/kiv/unum |
| Physics | Python | Tool | https://bitbucket.org/hppavilion1/physics |
| Measurement.js | JavaScript | Library | https://github.com/Philzen/measurement.js |
| Frinj | Clojure | Tool | https://github.com/martintrojer/frinj |
| UnitsKit | Objective-C | Library | https://github.com/stevemoser/UnitsKit |
| UOM-Plugin | Haskell | Library | https://github.com/adamgundry/uom-plugin |
| Units-of-Measure (#1) | Scala | Library | https://github.com/Mononofu/Units-of-Measure |
| Units (#15) | Rust | Library | https://github.com/Boddlnagg/units |
| Fhir.Metrics | C# | Library | https://github.com/FirelyTeam/Fhir.Metrics |
| FSharp.Units | F# | Library | https://github.com/putridparrot/FSharp.Units |
| Units (#16) | Scala | Library | https://github.com/nestorpersist/units |
| Units-Ruby | Ruby | Library | https://github.com/bfoz/units-ruby |
| Python-Units-Of-Measure | Python | Library | https://github.com/katerina7479/python-units-of-measure |
| PPX_Measure | OCalm | Library | https://github.com/xvw/ppx_measure |
| IMT.Units | Java | Library | https://github.com/imt-ag/imt.units-java |
| Converter (#3) | Java | Tool | https://github.com/samWson/converter |
| SimpleMeasurementConverter | Java | Tool | https://github.com/michaelstoops/SimpleMeasurementConverter |
| Converter (#4) | C++ | Tool | https://github.com/dtalaba/convertor |
| Frins | Scala | Tool | https://github.com/martintrojer/frins |
| PHPMeasures | PHP | Library | https://github.com/dcabanaw/phpMeasures |
| PHP-Units | PHP | Library | https://github.com/hiqdev/php-units |
| Cuis-Smalltalk-Aconcagua | Smalltalk | Library | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| Measurements | PHP | Library | https://github.com/marfurt/measurements |
| UnitsOfMeasureBundle | PHP | Library | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| UnitsOfMeasure (#2) | C# | Library | https://github.com/capnmidnight/UnitsOfMeasure |
| Units (#17) | PHP | Library | https://github.com/ARCANEDEV/Units |
| Units_of_measure | C++ | Library | https://github.com/Skeen/units_of_measure |
| Units (#18) | Go | Library | https://github.com/antha-lang/units |
| Units of Measure Prototype | Haskell | Library | https://github.com/adamgundry/uom-prototype |
| Uom.Dart | Dart | Library | https://github.com/damondouglas/uom.dart |
| RockUnits | C# | Library | https://github.com/gareth-reid/RockUnits |
| TundraMeasure.java | Java | Library | https://github.com/Permafrost/TundraMeasure.java |
| Units (#19) | PHP | Library | https://github.com/marando/Units |
| UnitOfMeasure (#1) | C# | Library | https://github.com/Chef-Code/UnitOfMeasure |
| Units-api | PHP | Library | https://github.com/shrimpza/units-api |
| cppDegRad | C++ | Library | https://github.com/grahamboree/cppDegRad |
| Unit (#3) | VB .NET | Library | https://github.com/AdamSpeight2008/Unit |
| Simple.Units | C# | Library | https://github.com/oriches/Simple.Units |
| Class-Measure | Perl | Library | https://github.com/bluefeet/Class-Measure |
| Measurements | Ruby | Library | https://github.com/Krustal/Measurements |
| Purescript-Units | PureScript | Library | https://github.com/fluffynukeit/purescript-units |
| Mezur | JavaScript | Library | https://github.com/guyisra/mezur |
| MeasurementConverter | Java | Tool | https://github.com/SBrooks75/MeasurementConverter |
| Uom | Ruby | Library | https://github.com/caruby/uom |
| GenUnits | F# | Library | https://github.com/halcwb/GenUnits |
| Ruby-Units | Ruby | Library | https://github.com/davearonson/Ruby-Units |
| JavaMeasure | Java | Library | https://github.com/tkuebler/JavaMeasure |
| AS3Units | ActionScript | Library | https://github.com/erussell/AS3Units |
| UnitConverter (#4) | Java | Tool | https://github.com/MarioDudjak/UnitConverter |
| PHPConverter | PHP | Library | https://github.com/chapmang/PHPConverter |
| NGX-UOM | JavaScript | Library | https://github.com/catellanir/ngx-uom |
| Physical Quantities | Smalltalk/C# | Library | https://github.com/timdetering/PhysicalQuantities |
| GIM.Quantities | C# | Library | https://github.com/togakangaroo/GIM.Quantities |
| JUNitConv | Java | Library | https://github.com/duckler/JUnitConv |
| Dimensional | Ruby | Library | https://github.com/cch1/Dimensional |
| Maser | JavaScript/Python | Tool | https://github.com/justinbangerter/maser |
| UnitOfMeasure (#2) | Scala | Library | https://github.com/ricemery/unitofmeasure |
| Umpy | Python | Library | https://github.com/perdixsw/umpy |
| SBUnits | Swift | Library | https://github.com/EBGToo/SBUnits |
| Units (#21) | Haskell | Library | https://github.com/goldfirere/units |
| MKUnits | Swift | Library | https://github.com/michalkonturek/MKUnits |
| JC-Units | Python | Tool | https://github.com/jason0x43/jc-units |
| Gu.Units | C# | Library | https://github.com/JohanLarsson/Gu.Units |
| DDUnitConverter | Objective-C | Library | https://github.com/davedelong/DDUnitConverter |
| CSUnits | C# | Library | https://github.com/cureos/csunits |
| PHP-Conversion | PHP | Library | https://github.com/crisu83/php-conversion |
| SIUnitX | TeX | Library | https://github.com/josephwright/siunitx |
| Units (#24) | Scala | Library | https://github.com/KarolS/units |
| UnitConverterUltimate | Java | Tool | https://github.com/physphil/UnitConverterUltimate |
| SI-Units | Java | Library | https://github.com/unitsofmeasurement/si-units |
| Measured | Ruby | Library | https://github.com/Shopify/measured |
| Units (#25) | Java | Tool | https://github.com/xxv/Units |
| Conversion (#1) | PHP | Library | https://github.com/abhimanyu003/conversion |
| UnitConverter (#5) | Python | Library | https://github.com/mattgd/UnitConverter |
| Unit-converter | PHP | Library | https://github.com/jordanbrauer/unit-converter |
| HHUnitConverter | Objective-C | Library | https://github.com/HiveHicks/HHUnitConverter |
| Unit-Converter (#1) | JavaScript | Tool | https://github.com/TheMarco/Unit-Converter |
| Alfred-Converter | Python | Tool | https://github.com/WoLpH/alfred-converter |
| Unitz | JavaScript | Library | https://github.com/ClickerMonkey/unitz |
| UnitConverter.htm | JavaScript | Tool | https://github.com/iterami/UnitConverter.htm |
| UnitConverter (#7) | Java | Tool | https://github.com/impateljay/UnitConverter |
| Angular-Unit-Converter | JavaScript | Library | https://github.com/alexandernst/angular-unit-converter |
| UnitConverterWin | C | Library | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| Unit-Converter (#3) | Java | Tool | https://github.com/AmitKumarSah/Unit-Converter |
| PythonUnitConverter | Python | Tool | https://github.com/Aaron1011/PythonUnitConverter |
| Converter (#5) | Java | Tool | https://github.com/HanSolo/converter |
| Mather | Java | Tool | https://github.com/icasdri/Mather |
| Vandelay | C++ | Tool | https://github.com/HaikuArchives/Vandelay |
| Unit-Converter (#3) | PHP | Tool | https://github.com/b-sebastian/unit-converter |
| Unit-Converter (#4) | C++ | Tool | https://github.com/mikeleppane/Unit-Converter |
| Unit-Converter (#6) | JavaScript | Tool | https://github.com/MaicolBen/unit-converter |
| UnitConversion (#1) | Objective-C | Library | https://github.com/unixpickle/UnitConversion |
| UnitConverter (#10) | PHP | Library | https://github.com/nfraz007/UnitConverter |
| Unit | PHP | Tool | https://github.com/pounard/Unit |
| Converter (#11) | C++ | Tool | https://github.com/KerryL/Converter |
| Angular-Converter | JavaScript | Tool | https://github.com/cyrilf/angular-converter |
| PreciseUnitConverter | JavaScript | Tool | https://github.com/bumxu/PreciseUnitConverter |
| Cropio_Units_Converter | C++ | Library | https://github.com/cropio/cropio_units_converter |
| Converter (#25) | TypeScript | Tool | https://github.com/ialex90/Converter |
| DakaUnitConverter | Java | Tool | https://github.com/darrylfonseka/DakaUnitConverter |
| Convertor | C++ | Tool | https://github.com/mihaelateo/Convertor |
| Converter (#27) | C++ | Tool | https://github.com/scruff3y/Converter |
| Unit-Converter | JavaScript | Tool | https://github.com/GTLook/Unit-Converter |
| UnitMan | C# | Tool | https://github.com/mbeloshapkin/UnitMan |
| PyUnitConverter | Python | Tool | https://github.com/jyri78/PyUnitConverter |
| Quantity | Ruby | Library | https://github.com/bhuga/quantity |
| UDUNITS-2 | C | Library | https://github.com/Unidata/UDUNITS-2 |
| Purescript-Quantities | PureScript | Library | https://github.com/sharkdp/purescript-quantities |
| Quantities | Haskell | Library | https://github.com/jdreaver/quantities |
| Quantities | Swift | Library | https://github.com/BradLarson/Quantities |
| PhysicalQuantities | Python | Library | https://github.com/juhasch/PhysicalQuantities |
| Quantity | PHP | Library | https://github.com/phospr/quantity |
| Quantities | R | Library | https://github.com/r-quantities/quantities |
| Quantiphy | Python | Library | https://github.com/KenKundert/quantiphy |
| ScientificQuantities | C++ | Library | https://github.com/nourani/ScientificQuantities |
| Quantities | MatLab | Library | https://github.com/mikofski/Quantities |
| Physical-Quantities | Python | Library | https://github.com/hplgit/physical-quantities |
| ScalaQuantity | Scala | Library | https://github.com/zzorn/ScalaQuantity |
| Misu | Python | Library | https://github.com/cjrh/misu |
| Lua-Physical | Lua | Library | https://github.com/tjenni/lua-physical |
| All_In_One_Converter | Python | Tool | https://github.com/pradeepjairamani/All_in_one_converter |
| Quantities | C++ | Library | https://github.com/djbarker/quantities |
| Quantity | Ruby | Library | https://github.com/aportnov/quantity |
| Quantities | Batchfile | Library | https://github.com/greatfriends/Quantities |
| Quantities | C# | Library | https://github.com/atmoos/Quantities |
| Physics-Measurement | JavaScript | Library | https://github.com/victorpotasso/physics-measurement |
| PyQuantity | Python | Library | https://github.com/gabbpuy/PyQuantity |
| ConverterApp | C# | Tool | https://github.com/halezmo/ConverterApp |
| Sundew.Quantities | C# | Library | https://github.com/hugener/Sundew.Quantities |
| Meteor-Quantities | JavaScript | Library | https://github.com/luzlab/meteor-quantities |
| Quantity | Clojure | Library | https://github.com/spellman/quantity |
| Convert-Quantities | JavaScript | Library | https://github.com/kendru/convert-quantities |
| Alchemist | Ruby | Library | https://github.com/halogenandtoast/alchemist |
| UnitConversion (#2) | C# | Library | https://github.com/gkampolis/UnitConversion |
| Convert.js | JavaScript | Library | https://github.com/YazilimMuhendisiyizBiz/convert.js |
| Convertor | PHP | Library | https://github.com/olifolkerd/convertor |
| Alfred-Convert | Python | Tool | https://github.com/deanishe/alfred-convert |
| MeasureBundle | PHP | Library | https://github.com/akeneo/MeasureBundle |
| Convertr | R | Library | https://github.com/ropenscilabs/convertr |
| Metric | Java | Library | https://github.com/gnapse/metric |
| Jsunitconverter | JavaScript | Library | https://github.com/jerodvenemafm/jsunitconverter |
| Sius | Java | Library | https://github.com/mbe24/sius |
| Unit | JavaScript | Library | https://github.com/smartcar/unit |
| Unit-formula | Common Lisp | Library | https://github.com/Ramarren/unit-formula |
| Node-units | JavaScript | Library | https://github.com/brettlangdon/node-units |
| Xiny | Go | Tool | https://github.com/bcicen/xiny |
| Units.js | JavaScript | Library | https://github.com/jairtrejo/units.js |
| GenUnitApp | JavaScript | Tool | https://github.com/halcwb/GenUnitApp |
| Units (#28) | C++ | Library | https://github.com/lonkamikaze/units |
| Unitconverter-Android | Java | Tool | https://github.com/dbrant/unitconverter-android |
| Unit.styl | JavaScript | Library | https://github.com/diessica/unit.styl |
| Conversionr | R | Library | https://github.com/alexnakagawa/conversionr |
| Math-units | Perl | Library | https://github.com/kenfox/Math-Units |
| UnitConvert | JavaScript | Library | https://github.com/agnoster/unitology |
| Convertinator | C# | Library | https://github.com/hartez/Convertinator |
| NGunits | Java | Library | https://github.com/erussell/ngunits |
| Units (#29) | Swift | Library | https://github.com/chrisjeane/Units |
| UnitConversion (#3) | Python | Library | https://github.com/UnitConversion/unitConversion |
| Metiri | JavaScript | Library | https://github.com/GCheung55/metiri |
| Scala-units | Scala | Library | https://github.com/bwkimmel/scala-units |
| Convert-units | Ruby | Library | https://github.com/tanvir002700/convert_unit |
| Django-Unit-Field | Python | Library | https://github.com/kohout/django-unit-field |
| Aegon | Python | Library | https://github.com/lukaskollmer/aegon |
| Units (#30) | PHP | Library | https://github.com/rmasters/units |
| Unit_Conversion | Ruby | Library | https://github.com/eternal44/unit_conversion |
| Maegor | JavaScript | Library | https://github.com/lukaskollmer/maegor |
| Units-System | Ruby | Library | https://github.com/jgoizueta/units-system |
| Physical | C++ | Library | https://github.com/olsonse/physical |
| Conversion (#6) | C++ | Library | https://github.com/simonmeaden/conversion |
| Gorilla | Ruby | Library | https://github.com/stephencelis/gorilla |
| Units by Stak Digital | JavaScript | Library | https://github.com/stak-digital/units |
| QtUnits | C++ | Library | https://github.com/hrobeers/QtUnits |
| Unit_Soup | Ruby | Library | https://github.com/rutvij47/unit_soup |
| Units (#32) | Ruby | Library | https://github.com/woahdae/units |
| Unit_Conversion | Python | Tool | https://github.com/bastihaase/unit_conversion |
| convertR | R | Library | https://github.com/colin-fraser/convertR |
| UnitConversion (#4) | C# | Library | https://github.com/Mecteral/UnitConversion |
| UnitConversion (#6) | Java | Tool | https://github.com/yfl007/UnitConversion |
| Unit-Conversion | JavaScript | Tool | https://github.com/srimanthk/unit-conversion |
| JSR 275 | Java | Library | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| JSR 363 | Java | Library | https://jcp.org/en/jsr/detail?id=363 |
| Units (#31) | Tcl | Library | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Units (#32) | R | Library | https://cran.r-project.org/web/packages/units/index.html |
| Quantified | Ruby | Library | https://github.com/Shopify/quantified |
| Dimensional | Haskell | Library | https://github.com/bjornbm/dimensional |
| Units (#33) | Haskell | Library | https://hackage.haskell.org/package/units |
| PHYSICS | Multiple | Library | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |

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
