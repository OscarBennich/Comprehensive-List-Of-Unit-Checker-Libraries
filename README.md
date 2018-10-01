# A Comprehensive List of Unit Checker Libraries
## Table of Contents
- [Short description of the project](#short-description)
- [Data gathering information](#data-gathering-information)
- [Top tier libraries](#top-tier-libraries)
- [Second tier libraries](#second-tier-libraries)
- [Tools and applications](#tools)
- [All projects](#all-projects)

## Short description 
In the spring of 2018 I (Oscar Bennich-Björkman) wrote my master thesis as part of my degree in Information Systems at Uppsala University. The main goal of this thesis involved a comprehensive and systematic analysis of libraries related to the handling of physical quantities or units of measurement. The end result was a group of what I chose to call 'top tier' libraries, which are the best and most well-developed libraries in a range of different programming languages. 

Me and my supervisor (Steve McKeever) also remade the core of this thesis into a paper which is to be published in the ACM Journals in conjunction with being presented at the 2018 ACM SIGPLAN International Conference on Software Language Engineering (https://conf.researchr.org/track/sle-2018/papers#About). 

This GitHub repository is primarily provided as a way of giving easy access to this data for anyone looking for a library of this kind, as this type of database did not exist prior to this study. Secondarily, this database is a way of making the data more transparent for any reader of either the paper or the thesis. 

The most relevant results of the study (the top tier group) is presented first in this repository as this is what is of interest to most readers, but the later sections present the rest of the data in its entirety. 

If you have any questions or thoughts you can contact me at: oscar.bennich@gmail.com

If you would like to read more, the master thesis can be found here: http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-353817 
and the paper can be found here: [To be added]

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
[Back to top](#table-of-contents)

| Name | Language | Amount of units/constants/prefixes supported | Source / URL |
|---------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| CaliperSharp | C# | 132 units, 16 constants, 23 prefixes | https://github.com/point85/CaliperSharp |
| Convertinator | C# | ~20 units | https://github.com/hartez/Convertinator |
| CSUnits | C# | 500+ units (including prefixes) | https://github.com/cureos/csunits |
| Cubico | C# | ~140 units | https://github.com/irperez/Cubico |
| Fhir.Metrics | C# | ~150 units, 24 prefixes | https://github.com/FirelyTeam/Fhir.Metrics |
| Gu.Units | C# | ~50 units | https://github.com/JohanLarsson/Gu.Units |
| Quantity System | C# | 300+ units | https://github.com/ibluesun/QuantitySystem |
| Quantity Types | C# | 300+ units | https://github.com/objorke/QuantityTypes |
| RedStar.Amounts | C# | ~80 units, 16 constants | https://github.com/petermorlion/RedStar.Amounts/ |
| UnitParser | C# | ~300 units | https://www.codeproject.com/Articles/1211504/UnitParser |
| UnitsNet | C# | 600+ units (including prefixes) | https://github.com/angularsen/UnitsNet |
| Using physical quantities and units of measure in C# programs | C# | ~100 units | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |
| Working with Units and Amounts | C# | 70+ units, 16 constants | https://www.codeproject.com/Articles/611731/Working-with-Units-and-Amounts |
| Aegon | Python | 150+ units | https://github.com/lukaskollmer/aegon |
| Astropy | Python | ~150 units, 35 constants | https://github.com/astropy/astropy |
| Efficient Scalars in Python | Python | ~150 units | http://russp.us/scalar-python.htm |
| Misu | Python | ~450 units, 20 prefixes | https://github.com/cjrh/misu |
| ParamPy | Python | 50+ units, 16 prefixes | https://github.com/matthewwardrop/python-parampy |
| Pint | Python | 300+ units, 20 constants, 27 prefixes | https://github.com/hgrecco/pint |
| Pyvalem | Python | 70+ units | https://github.com/xnx/pyqn |
| Quantiphy | Python | ~40 units, 19 prefixes, 19 constants | https://github.com/KenKundert/quantiphy |
| Quantities (#1) | Python | 300+ units, 28 prefixes | https://github.com/python-quantities/python-quantities |
| Scimath | Python | 300+ units | https://github.com/enthought/scimath |
| BoostUnits | C++ | ~200 units, 20 prefixes, ~150 constants | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |
| PhysUnits | C++ | 100+ units, 7 constants, 28 prefixes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| Units | C++ | ~150 units, 22 prefixes | https://github.com/nholthaus/units |
| Units | C++ | ~30 units, 330+ constants, 14 prefixes | https://github.com/tonypilz/units |
| Units and measures for C++ 11 | C++ | ~50 units | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |
| Alchemist | Ruby | 500+ units, 88 prefixes | https://github.com/halogenandtoast/alchemist |
| Phys-Units | Ruby | 2300+ units, 85 prefixes | https://github.com/masa16/phys-units |
| Quantity | Ruby | ~40 units, 25 prefixes, | https://github.com/bhuga/quantity |
| Ruby Units | Ruby | ~150 units, 30 prefixes | https://github.com/olbrich/ruby-units |
| SY | Ruby | 30+ units, ~10 constants | https://github.com/boris-s/sy |
| Unit_Soup | Ruby | 0 units preloaded? | https://github.com/rutvij47/unit_soup |
| Units-Ruby | Ruby | 74 units, 5 prefixes | https://github.com/bfoz/units-ruby |
| Unitwise | Ruby | 300+ units | https://github.com/joshwlewis/unitwise |
| Uom | Ruby | 63 units | https://github.com/caruby/uom |
| Flowsnake | JavaScript | 650+ units | https://github.com/Eldelshell/flowsnake |
| JS-quantities | JavaScript | ~150 units, 30 prefixes | https://github.com/gentooboontoo/js-quantities |
| Mezur | JavaScript | ~100 units | https://github.com/guyisra/mezur |
| Units by Stak Digital | JavaScript | ~50 units | https://github.com/stak-digital/units |
| Unitz | JavaScript | ~70 units | https://github.com/ClickerMonkey/unitz |
| Caliper | Java | ~130 units,  23 prefixes, 16 constants | https://github.com/point85/caliper |
| JSR 363 | Java | 35 units | https://jcp.org/en/jsr/detail?id=363 |
| SI-Units | Java | 120+ units, 4 constants | https://github.com/unitsofmeasurement/si-units |
| Unit API - JSR 385 | Java | 30+ units, 28 prefixes | https://github.com/unitsofmeasurement/unit-api |
| Coulomb | Scala | ~70 units, 28 prefixes | https://github.com/erikerlandson/coulomb |
| Efficient Scalars in Scala | Scala | ~150 units | http://russp.us/scalar-scala.htm |
| Scala-units | Scala | ~120 units | https://github.com/bwkimmel/scala-units |
| SI -- A Scala Library of Units of Measurement | Scala | ~50 units, 20 prefixes | https://gitlab.com/h2b/SI |
| Squants | Scala | ~300 units, 28 prefixes | https://github.com/typelevel/squants |
| Convertor | PHP | 70+ units | https://github.com/olifolkerd/convertor |
| PHP Units of Measure | PHP | ~100 units | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |
| UnitConverter | PHP | 130+ units | https://github.com/nfraz007/UnitConverter |
| Dimensional | Haskell | ~200 units, 21 prefixes | https://github.com/bjornbm/dimensional |
| Quantities | Haskell | 200+ units, 28 prefixes, 3 constants | https://github.com/jdreaver/quantities |
| UOM-Plugin | Haskell | 0 units preloaded | https://github.com/adamgundry/uom-plugin |
| Physical Units for Matlab | MatLab | 800+ units | https://github.com/sky-s/physical-units-for-matlab |
| Quantities | MatLab | 200+ units, 28 prefixes, 18 constants | https://github.com/mikofski/Quantities |
| MKUnits | Swift | 80 units | https://github.com/michalkonturek/MKUnits |
| UnitKit | Swift | 100+ units | https://github.com/otaviocc/UnitKit |
| PHYSICS | Multiple | ~190 units, 25 prefixes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |
| Units | Multiple | 65 units, 70 constants | https://github.com/saroad2/units |
| Dimensioned | Rust | ~450 units & constants (hard to differentiate) | https://github.com/paholg/dimensioned |
| EiffelUnits | Eiffel | ~100 units, 21 prefixes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Elixir Unit Converter | Elixir | 60+ units | https://github.com/carturoch/ex_uc |
| FURY | Fortran | ? | https://github.com/szaghi/FURY |
| Lua-Physical | Lua | ~150 units, 10 prefixes, 21 constants | https://github.com/tjenni/lua-physical |
| Measurement Units for R | R | Has 0 preloaded units itself, uses other Library "UDUNITS-2" for this | https://github.com/r-quantities/units/ |
| Measures with Dimensions | Racket | ~150 units, 20 prefixes | https://github.com/AlexKnauth/measures-with-dimensions |
| PhysicalQuantities | Common Lisp | ~40 units, 28 prefixes | https://github.com/mrossini-ethz/physical-quantities |
| PPX_Measure | OCalm | 0 units preloaded. Generates a lot of code from simple commands instead (see documentation) | https://github.com/xvw/ppx_measure |
| Purescript-Quantities | PureScript | ~100 units, 23 prefixes, 14 constants | https://github.com/sharkdp/purescript-quantities |
| Quantities | Idris | ~200 units, 24 prefixes | https://github.com/timjb/quantities |
| Quantities | D | ~50 units, 20 prefixes | https://github.com/biozic/quantities |
| Red-units | Red | 960 units, 1100+ constants, 100+ prefixes | https://gitlab.com/maxvel/red-units |
| Uncodium.Units | F# | ~350 units, 28 prefixes, ~50 constants | https://github.com/stefanmaierhofer/Uncodium.Units |
| Unitful.jl | Julia | ~170 units, 50 prefixes, 21 constants | https://github.com/ajkeller34/Unitful.jl |
| Units | Tcl | 60 units, 21 prefixes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Units 2 | Clojure | ~45 units, 28 prefixes | https://github.com/mfey/units2 |
| Units of Measure | Kotlin | 350+ units | https://github.com/kunalsheth/units-of-measure |
| Units of measurement for Ada | Ada | 100+ units, 20 prefixes | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |

## Second tier libraries 
| Name | Language | Source / URL |
|------------------------------------------------------------------|------------------|-------------------------------------------------------------------------------------------------|
| .NET Unit Conversion Library | C# | https://sourceforge.net/projects/unitcon/ |
| .NET Unit Conversion Library | C# | https://sourceforge.net/projects/unitcon/?source=directory |
| .NET Units of Measure | C# | https://bitbucket.org/Thecentury/.net-units-of-measure |
| Angular-Unit-Converter | JavaScript | https://github.com/alexandernst/angular-unit-converter |
| AS3Units | ActionScript | https://github.com/erussell/AS3Units |
| Automatic Conversion of Physical Units | C# | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |
| AutoUnits | C++ | https://github.com/Fifty-Nine/AutoUnits |
| Buckingham | Python | https://github.com/mdipierro/buckingham |
| C++ Unit Library | C++ | https://sourceforge.net/projects/cppunitlibrary/?source=directory |
| C++ Units | C++ | https://sourceforge.net/projects/cppunits/?source=directory |
| CF_Units | Python | https://github.com/SciTools/cf_units |
| Class-Measure | Perl | https://github.com/bluefeet/Class-Measure |
| Constants and Units | MatLab | https://github.com/mariomerinomartinez/constants_and_units |
| Conversion | PHP | https://github.com/abhimanyu003/conversion |
| Conversion | C++ | https://github.com/simonmeaden/conversion |
| Conversionr | R | https://github.com/alexnakagawa/conversionr |
| Convert | Swift | https://github.com/danielbyon/Convert |
| Convert Units | Java | https://github.com/ben-ng/convert-units |
| Convert-Quantities | JavaScript | https://github.com/kendru/convert-quantities |
| Convert-units | Ruby | https://github.com/tanvir002700/convert_unit |
| Convert.js | JavaScript | https://github.com/YazilimMuhendisiyizBiz/convert.js |
| Converter | PHP | https://github.com/cartalyst/converter |
| Converting a value to an SI Unit String | C# | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |
| Convertr | R | https://github.com/ropenscilabs/convertr |
| convertR | R | https://github.com/colin-fraser/convertR |
| cppDegRad | C++ | https://github.com/grahamboree/cppDegRad |
| Cropio_Units_Converter | C++ | https://github.com/cropio/cropio_units_converter |
| Cuis-Smalltalk-Aconcagua | Smalltalk | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| DDUnitConverter | Objective-C | https://github.com/davedelong/DDUnitConverter |
| Decibel Units of Measurement with C# Framework | C# | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |
| Dftu | C++ | https://github.com/triblatron/dftu |
| Dimanalyser | Java | https://github.com/cymi/dimanalyser |
| Dimension-TF | Haskell | https://github.com/nushio3/dimensional-tf |
| Dimensional | Ruby | https://github.com/cch1/Dimensional |
| DimPy | Python | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| Django-Unit-Field | Python | https://github.com/kohout/django-unit-field |
| Engineering | C# | https://github.com/zhofre/engineering |
| FSharp.Units | F# | https://github.com/putridparrot/FSharp.Units |
| GenUnits | F# | https://github.com/halcwb/GenUnits |
| GIM.Quantities | C# | https://github.com/togakangaroo/GIM.Quantities |
| Gorilla | Ruby | https://github.com/stephencelis/gorilla |
| HHUnitConverter | Objective-C | https://github.com/HiveHicks/HHUnitConverter |
| IMT.Units | Java | https://github.com/imt-ag/imt.units-java |
| InkUnits | Swift | https://github.com/angelsolaorbaiceta/InkUnits |
| International System of Units Notation | C# | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |
| Java library and framework: quantity | Java | https://sourceforge.net/projects/javaquantity/?source=directory |
| Java Measure | Java | https://sourceforge.net/projects/javameasure/?source=directory |
| JavaMeasure | Java | https://github.com/tkuebler/JavaMeasure |
| JNum | Java | https://github.com/attipaci/jnum |
| JQuantity: Precision Math Java Framework | Java | https://sourceforge.net/projects/jquantity/?source=directory |
| JSR 275 | Java | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| Jsunitconverter | JavaScript | https://github.com/jerodvenemafm/jsunitconverter |
| JUNitConv | Java | https://github.com/duckler/JUnitConv |
| Lathexa Units | JavaScript | https://github.com/lethexa/lethexa-units |
| Libquantify | C++ | https://github.com/damianorenfer/libquantify |
| Libunits | C | https://sourceforge.net/projects/libunits/?source=directory |
| Maegor | JavaScript | https://github.com/lukaskollmer/maegor |
| MagickScience | C++ | https://github.com/Iarfen/MagickScience |
| Magnitude (#1) | Python | https://github.com/juanre/magnitude |
| Magnitude (#2) | Java | https://sourceforge.net/projects/magnitude/?source=directory |
| Math-units | Perl | https://github.com/kenfox/Math-Units |
| mcs::units | C++ | https://sourceforge.net/projects/mcs-units/?source=directory |
| MeasureBundle | PHP | https://github.com/akeneo/MeasureBundle |
| Measurement Unit Conversion Library | C# | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Measurement Unit Conversion Library | C# | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |
| Measurement.js | JavaScript | https://github.com/Philzen/measurement.js |
| Measurements | PHP | https://github.com/marfurt/measurements |
| Measurements | Ruby | https://github.com/Krustal/Measurements |
| Meteor-Quantities | JavaScript | https://github.com/luzlab/meteor-quantities |
| Metiri | JavaScript | https://github.com/GCheung55/metiri |
| Metric | Java | https://github.com/gnapse/metric |
| Metric | Rust | https://github.com/coder543/metric |
| Metric | Nim | https://github.com/mjendrusch/metric |
| Natu | Python | https://github.com/kdavies4/natu |
| NGenericDimensions | C# | https://github.com/MafuJosh/NGenericDimensions |
| NGunits | Java | https://github.com/erussell/ngunits |
| NGX-UOM | JavaScript | https://github.com/catellanir/ngx-uom |
| Node-units | JavaScript | https://github.com/brettlangdon/node-units |
| NumericalChameleon | Java | https://sourceforge.net/projects/numchameleon/?source=directory |
| o2scl | C | https://github.com/awsteiner/o2scl |
| PHP Unit Conversion | PHP | https://github.com/pimlie/php-unit-conversion |
| PHP-Conversion | PHP | https://github.com/crisu83/php-conversion |
| PHP-Units | PHP | https://github.com/hiqdev/php-units |
| PHPConverter | PHP | https://github.com/chapmang/PHPConverter |
| PHPMeasures | PHP | https://github.com/dcabanaw/phpMeasures |
| Phys-Types | C++ | https://github.com/akubera/phys_types |
| Physcon | Python | https://github.com/georglind/physcon |
| Physical | C++ | https://sourceforge.net/projects/physical/?source=directory |
| Physical | C++ | https://github.com/olsonse/physical |
| Physical Math | Python | https://github.com/matthagy/physmath |
| Physical Measure | C# | https://github.com/KiloBravoLima/PhysicalMeasure |
| Physical Quantities | Smalltalk/C# | https://github.com/timdetering/PhysicalQuantities |
| Physical-Quantities | Python | https://github.com/hplgit/physical-quantities |
| PhysicalQuantities | Python | https://github.com/juhasch/PhysicalQuantities |
| PhysicalQuantities | C# | https://github.com/timdetering/PhysicalQuantities |
| PhysicalQuantities | Haskell | https://github.com/fehu/PhysicalQuantities |
| PhysicalUnits | C++ | https://sourceforge.net/projects/physicalunits/?source=directory |
| PhysicalValue | Swift | https://github.com/antonvmironov/PhysicalValue |
| Physics-Measurement | JavaScript | https://github.com/victorpotasso/physics-measurement |
| Physikal | Kotlin | https://github.com/Tenkiv/Physikal |
| ProgParam | C++ | https://github.com/qPCR4vir/ProgParam |
| puny | Python | https://sourceforge.net/projects/puny/?source=directory |
| Purescript-Units | PureScript | https://github.com/fluffynukeit/purescript-units |
| PyPhys Class Library | Python | https://sourceforge.net/projects/pyphys/?source=directory |
| PyQuantity | Python | https://github.com/gabbpuy/PyQuantity |
| Python Unit Conversion Library | Python | https://sourceforge.net/projects/pythonconvert/?source=directory |
| Python-Physical | Python | https://github.com/EdwinChan/python-physical |
| Python-Units-Of-Measure | Python | https://github.com/katerina7479/python-units-of-measure |
| QtUnits | C++ | https://github.com/hrobeers/QtUnits |
| Quan | C++ | https://sourceforge.net/projects/quan/?source=directory |
| Quantified | Ruby | https://github.com/Shopify/quantified |
| Quantify | Ruby | https://github.com/spatchcock/quantify |
| Quantities | Swift | https://github.com/BradLarson/Quantities |
| Quantities | R | https://github.com/r-quantities/quantities |
| Quantities | C++ | https://github.com/djbarker/quantities |
| Quantities | Batchfile | https://github.com/greatfriends/Quantities |
| Quantities | C# | https://github.com/atmoos/Quantities |
| Quantities | C++ | https://sourceforge.net/projects/quantity/?source=directory |
| Quantities, Units, and Values: An Object Oriented Implementation | C | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |
| Quantities.net | C# | https://sourceforge.net/projects/quantitiesnet/ |
| Quantity | Ruby | https://github.com/bhuga/quantity |
| Quantity | Ruby | https://github.com/aportnov/quantity |
| Quantity | Clojure | https://github.com/spellman/quantity |
| Quantity.Net | C# | https://github.com/bcachet/Quantity.Net |
| QUDAL | C++ | https://sourceforge.net/projects/qudal/?source=directory |
| RockUnits | C# | https://github.com/gareth-reid/RockUnits |
| Ruby Units | Ruby | https://github.com/olbrich/ruby-units |
| Ruby-Units | Ruby | https://github.com/davearonson/Ruby-Units |
| SBUnits | Swift | https://github.com/EBGToo/SBUnits |
| ScalaQuantity | Scala | https://github.com/zzorn/ScalaQuantity |
| ScalaU | Scala | https://github.com/adrianfr/scalau |
| Scale | Swift | https://github.com/onmyway133/Scale |
| ScientificQuantities | C++ | https://github.com/nourani/ScientificQuantities |
| SI-Units | Java | https://github.com/unitsofmeasurement/si-units |
| SIConv | Haskell | https://github.com/owainlewis/conventional-si-unit-converter |
| Simple.Units | C# | https://github.com/oriches/Simple.Units |
| SIUnits (#1) | Haskell | https://github.com/joewkr/SIUnits |
| SIUnitX | TeX | https://github.com/josephwright/siunitx |
| Sius | Java | https://github.com/mbe24/sius |
| Sundew.Quantities | C# | https://github.com/hugener/Sundew.Quantities |
| Superquants | Scala | https://github.com/rudogma/scala-superquants |
| SwiftMeasurement | Swift | https://github.com/ken0nek/SwiftMeasurement |
| TCX Unit Conversion Library | C++ | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |
| The Units of Measure Library | C++ | https://sourceforge.net/projects/tuoml/ |
| TundraMeasure.java | Java | https://github.com/Permafrost/TundraMeasure.java |
| UDUnits | Julia | https://github.com/Alexander-Barth/UDUnits.jl |
| UDUNITS-2 | C | https://github.com/Unidata/UDUNITS-2 |
| Umpy | Python | https://github.com/perdixsw/umpy |
| Unit | C++/CMake/Python | https://github.com/njoy/unit |
| Unit | JavaScript | https://github.com/smartcar/unit |
| Unit | Go | https://github.com/martinlindhe/unit |
| Unit | VB .NET | https://github.com/AdamSpeight2008/Unit |
| Unit Management Framework | Java | https://sourceforge.net/projects/quantitymanager/?source=directory |
| Unit of Measure Library for .NET | C# | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Unit of Measure Validator for C# | C# | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Unit Var | Python | https://sourceforge.net/projects/unitvar/?source=directory |
| Unit_Conversion | Ruby | https://github.com/eternal44/unit_conversion |
| Unit-converter | PHP | https://github.com/jordanbrauer/unit-converter |
| Unit-formula | Common Lisp | https://github.com/Ramarren/unit-formula |
| Unit.py | Python | https://github.com/fabian0010/Unit.py |
| Unit.styl | JavaScript | https://github.com/diessica/unit.styl |
| UnitConversion  | Objective-C | https://github.com/unixpickle/UnitConversion |
| UnitConversion  | C# | https://github.com/gkampolis/UnitConversion |
| UnitConversion | Python | https://github.com/UnitConversion/unitConversion |
| UnitConversion  | C# | https://github.com/Mecteral/UnitConversion |
| UnitConversionLib | C# | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| UnitConvert | JavaScript | https://github.com/agnoster/unitology |
| UnitConverter  | Python | https://github.com/mattgd/UnitConverter |
| UnitConverterWin | C | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| UnitManipulationLibrary | C++ | https://github.com/OuaisBla/UnitManipulationLibrary |
| UnitOfMeasure | C# | https://github.com/Chef-Code/UnitOfMeasure |
| UnitOfMeasure | Scala | https://github.com/ricemery/unitofmeasure |
| Units | Go | https://github.com/zn8nz/units |
| Units | Rust | https://github.com/Boddlnagg/units |
| Units | Scala | https://github.com/nestorpersist/units |
| Units | PHP | https://github.com/ARCANEDEV/Units |
| Units | Go | https://github.com/antha-lang/units |
| Units | PHP | https://github.com/marando/Units |
| Units | Python | https://bitbucket.org/adonohue/units |
| Units | Haskell | https://github.com/goldfirere/units |
| Units | Scala | https://github.com/KarolS/units |
| Units | C++ | https://github.com/lonkamikaze/units |
| Units | Swift | https://github.com/chrisjeane/Units |
| Units | Java | https://github.com/SamCarlberg/units |
| Units | PHP | https://github.com/rmasters/units |
| Units | Ruby | https://github.com/woahdae/units |
| Units | Haskell | https://hackage.haskell.org/package/units |
| Units | C# | https://github.com/engineers-tools/Units |
| Units | Go | https://github.com/smyrman/units |
| Units | C# | https://github.com/LabyrinthApps/Units |
| Units and Measurements | Racket | https://github.com/Metaxal/measures |
| Units D | D | https://github.com/nordlow/units-d |
| Units of Measure | C# | https://archive.codeplex.com/?p=unitsofmeasure |
| Units of Measure Prototype | Haskell | https://github.com/adamgundry/uom-prototype |
| Units of Measurement Systems | Java | https://github.com/unitsofmeasurement/uom-systems |
| Units_of_measure | C++ | https://github.com/Skeen/units_of_measure |
| Units-api | PHP | https://github.com/shrimpza/units-api |
| Units-of-Measure | Scala | https://github.com/Mononofu/Units-of-Measure |
| Units-System | Ruby | https://github.com/jgoizueta/units-system |
| Units-v2 | C++ | https://github.com/Corristo/units-v2 |
| Units.jl | Julia | https://github.com/autocorr/Units.jl |
| Units.js | JavaScript | https://github.com/jairtrejo/units.js |
| UnitsC++ | C++ | https://sourceforge.net/projects/unitscpp/?source=directory |
| UnitsKit | Objective-C | https://github.com/stevemoser/UnitsKit |
| UnitsOfMeasure | C# | https://github.com/capnmidnight/UnitsOfMeasure |
| UnitsOfMeasureBundle | PHP | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| Unum | Python | https://bitbucket.org/kiv/unum |
| Unum | Python | https://sourceforge.net/projects/unum/?source=directory |
| UOM | Ruby | https://github.com/madriska/uom |
| UOM Conversion Library | Java | https://sourceforge.net/projects/uomcl/?source=directory |
| UOM-Domain | Java | https://github.com/unitsofmeasurement/uom-domain |
| Uom.Dart | Dart | https://github.com/damondouglas/uom.dart |
| ValueWithUnit | C# | https://github.com/vbfox/ValueWithUnit |
| VUnits | Java | https://github.com/vaslabs/vunits |

## Tools
| Name | Language | Source / URL |
|-------------------------------------------------------------------------|-------------------|--------------------------------------------------------------------------------------------|
| Alfred-Convert | Python | https://github.com/deanishe/alfred-convert |
| Alfred-Converter | Python | https://github.com/WoLpH/alfred-converter |
| All_In_One_Converter | Python | https://github.com/pradeepjairamani/All_in_one_converter |
| Angular-Converter | JavaScript | https://github.com/cyrilf/angular-converter |
| BeConverter | C++ | https://bitbucket.org/Teknomancer/beconverter |
| ChemicalA | C++ | https://sourceforge.net/projects/chemicala/?source=directory |
| Chimp | Python | https://github.com/mhetrerajat/chimp |
| Computing with Units | Java | https://sourceforge.net/projects/units-in-java/?source=directory |
| Conversion Calculator | C++ | https://github.com/dtuivs/Converter |
| ConvertAll | Python | https://sourceforge.net/projects/convertall/?source=directory |
| Convertee | JavaScript | https://github.com/isquaredcreative/Convertee |
| Converter | C++ | https://github.com/KerryL/Converter |
| Converter  | Java | https://sourceforge.net/projects/con-vert/?source=directory |
| Converter  | TypeScript | https://github.com/ialex90/Converter |
| Converter  | C++ | https://github.com/scruff3y/Converter |
| Converter | Java | https://github.com/samWson/converter |
| Converter | C++ | https://github.com/dtalaba/convertor |
| Converter  | Java | https://github.com/HanSolo/converter |
| ConverterApp | C# | https://github.com/halezmo/ConverterApp |
| ConverTo | C++ | https://sourceforge.net/projects/converto/?source=directory |
| Convertor | C++ | https://github.com/mihaelateo/Convertor |
| DakaUnitConverter | Java | https://github.com/darrylfonseka/DakaUnitConverter |
| EngineeringCalculator | C++ | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | C# | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |
| Esos | C++ | https://sourceforge.net/projects/esos/?source=directory |
| Frinj | Clojure | https://github.com/martintrojer/frinj |
| Frins | Scala | https://github.com/martintrojer/frins |
| GenUnitApp | JavaScript | https://github.com/halcwb/GenUnitApp |
| GNU Units | C# | https://www.gnu.org/software/units/ |
| GodSend | PHP | https://sourceforge.net/projects/godsend/?source=directory |
| Insect | PureScript | https://github.com/sharkdp/insect |
| JC-Units | Python | https://github.com/jason0x43/jc-units |
| JConvert | Java | https://sourceforge.net/projects/jconvert/?source=directory |
| JFX Konwerter | Java | https://sourceforge.net/projects/jfx-konwerter/?source=directory |
| Libre Unit Conveter | C# | https://sourceforge.net/projects/libreunitconverter/?source=directory |
| LibreEngineering | Python | https://sourceforge.net/projects/libreeng/ |
| M2py | Python/Matlab | https://github.com/caiorss/m2py |
| MAIA Unit Converter | C++ | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Maser | JavaScript/Python | https://github.com/justinbangerter/maser |
| Mather | Java | https://github.com/icasdri/Mather |
| MeasurementConverter | Java | https://github.com/SBrooks75/MeasurementConverter |
| NumericalUnits | Python | https://github.com/sbyrnes321/numericalunits |
| ParamPool | Python | https://github.com/hplgit/parampool |
| Phriky-Units | Python | https://github.com/unl-nimbus-lab/phriky-units |
| Physics | Python | https://bitbucket.org/hppavilion1/physics |
| Portable Unit Converter | JavaScript | https://sourceforge.net/projects/puc/?source=directory |
| Praktool | Python | https://github.com/zombofant/praktool |
| PreciseUnitConverter | JavaScript | https://github.com/bumxu/PreciseUnitConverter |
| Punits - Pluggable units | C | https://sourceforge.net/projects/punits/?source=directory |
| PythonUnitConverter | Python | https://github.com/Aaron1011/PythonUnitConverter |
| PyUnitConverter | Python | https://github.com/jyri78/PyUnitConverter |
| qMetrics | C++ | https://launchpad.net/qmetrics |
| Quick Unit Converter | Java | https://sourceforge.net/projects/qunitconverter/?source=directory |
| Rink | Rust | https://github.com/tiffany352/rink-rs |
| Scaler | Shell | https://github.com/emugel/scaler |
| SIMConverter | C# | https://sourceforge.net/projects/simconverter/?source=directory |
| SimpleMeasurementConverter | Java | https://github.com/michaelstoops/SimpleMeasurementConverter |
| SimpleUnitConverter | C | https://launchpad.net/simpleunitconverter |
| Smart Units | Sidef | https://github.com/trizen/smart-units |
| UConverter | Java | https://sourceforge.net/projects/uconverter/?source=directory |
| UNeedIT Converter | C# | https://sourceforge.net/projects/uneedconverter/?source=directory |
| Unit | PHP | https://github.com/pounard/Unit |
| Unit | Java | https://bitbucket.org/hansolo/unit |
| Unit Converter  | Scratch | https://sourceforge.net/projects/unitconverter12/?source=directory |
| Unit Converter  | Python | https://sourceforge.net/projects/unit-converter/?source=directory |
| Unit Converter | REBOL | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| Unit Conveter  | C# | https://sourceforge.net/projects/unitconversion/?source=directory |
| Unit_Conversion | Python | https://github.com/bastihaase/unit_conversion |
| Unit-Conversion | JavaScript | https://github.com/srimanthk/unit-conversion |
| Unit-Converter | JavaScript | https://github.com/GTLook/Unit-Converter |
| Unit-converter  | Python | https://bitbucket.org/brayvasq/unit-converter |
| Unit-Converter | JavaScript | https://github.com/TheMarco/Unit-Converter |
| Unit-Converter  | Java | https://github.com/AmitKumarSah/Unit-Converter |
| Unit-Converter  | PHP | https://github.com/b-sebastian/unit-converter |
| Unit-Converter | C++ | https://github.com/mikeleppane/Unit-Converter |
| Unit-Converter  | JavaScript | https://github.com/MaicolBen/unit-converter |
| UnitConversion  | Java | https://github.com/yfl007/UnitConversion |
| UnitConverter  | Java | https://github.com/nevack/UnitConverter |
| UnitConverter  | Java | https://github.com/MarioDudjak/UnitConverter |
| UnitConverter | Java | https://github.com/impateljay/UnitConverter |
| Unitconverter-Android | Java | https://github.com/dbrant/unitconverter-android |
| UnitConverter.htm | JavaScript | https://github.com/iterami/UnitConverter.htm |
| UnitConverterUltimate | Java | https://github.com/physphil/UnitConverterUltimate |
| UnitMan | C# | https://github.com/mbeloshapkin/UnitMan |
| Units | Java | https://github.com/xxv/Units |
| Units | JavaScript | https://github.com/dohliam/units |
| Vandelay | C++ | https://github.com/HaikuArchives/Vandelay |
| Web Unit Converter | C# | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| XamConverter | C# | https://github.com/brminnick/XamConverter |
| Xiny | Go | https://github.com/bcicen/xiny |

## All projects
| Name | Language | Valid project? | Source / URL |
|-----------------------------------------------------------------------------------------------------------------------------|-------------------|----------------|-------------------------------------------------------------------------------------------------|
| .NET Unit Conversion Library | C# | Yes | https://sourceforge.net/projects/unitcon/ |
| .NET Unit Conversion Library | C# | Yes | https://sourceforge.net/projects/unitcon/?source=directory |
| .NET Units of Measure | C# | Yes | https://bitbucket.org/Thecentury/.net-units-of-measure |
| A look at the Boost Units Library | C++ | No | https://www.codeproject.com/Articles/988932/Boost-Units-Library |
| Aegon | Python | Yes | https://github.com/lukaskollmer/aegon |
| Alchemist | Ruby | Yes | https://github.com/halogenandtoast/alchemist |
| Alfred-Convert | Python | Yes | https://github.com/deanishe/alfred-convert |
| Alfred-Converter | Python | Yes | https://github.com/WoLpH/alfred-converter |
| All Unit Converter | Java | No | https://bitbucket.org/Chawakorn_A/all-unit-converter |
| All_In_One_Converter | Python | Yes | https://github.com/pradeepjairamani/All_in_one_converter |
| Angular-Converter | JavaScript | Yes | https://github.com/cyrilf/angular-converter |
| Angular-Unit-Converter | JavaScript | Yes | https://github.com/alexandernst/angular-unit-converter |
| Application of C++11 User-Defined Literals to Handling Scientific Quantities, Number Representation and String Manipulation | C++ | Yes | https://www.codeproject.com/Articles/447922/Application-of-Cplusplus-User-Defined-Literals-t |
| AS3Units | ActionScript | Yes | https://github.com/erussell/AS3Units |
| Astropy | Python | Yes | https://github.com/astropy/astropy |
| Automatic Conversion of Physical Units | C# | Yes | https://www.codeproject.com/Articles/714545/Automatic-Conversion-of-Physical-Units |
| AutoUnits | C++ | Yes | https://github.com/Fifty-Nine/AutoUnits |
| Aviation Tool | VB .NET | No | https://sourceforge.net/projects/aviationtool/?source=directory |
| BeConverter | C++ | Yes | https://bitbucket.org/Teknomancer/beconverter |
| BGConverter | C++ | No | https://github.com/bugeaggeorge/BGConverter |
| BoostUnits | C++ | Yes | https://www.boost.org/doc/libs/1_66_0/doc/html/boost_units.html |
| Buckingham | Python | Yes | https://github.com/mdipierro/buckingham |
| C++ Unit Library | C++ | Yes | https://sourceforge.net/projects/cppunitlibrary/?source=directory |
| C++ Units | C++ | Yes | https://sourceforge.net/projects/cppunits/?source=directory |
| C0nv3rt3r | C# | No | https://github.com/torifat/C0nv3rt3r |
| Caliper | Java | Yes | https://github.com/point85/caliper |
| CaliperSharp | C# | Yes | https://github.com/point85/CaliperSharp |
| Cerebro Converter | JavaScript | No | https://github.com/KELiON/cerebro-converter |
| CF_Units | Python | Yes | https://github.com/SciTools/cf_units |
| ChemicalA | C++ | Yes | https://sourceforge.net/projects/chemicala/?source=directory |
| Chimp | Python | Yes | https://github.com/mhetrerajat/chimp |
| Class-Measure | Perl | Yes | https://github.com/bluefeet/Class-Measure |
| Comment-Units | Rust | No | https://github.com/willi-kappler/comment_units |
| Complete Unit Conversion Sample in C# .NET | C# | Yes | https://www.codeproject.com/Articles/22470/Complete-Unit-Conversion-Sample-in-C-NET |
| Computing with Units | Java | Yes | https://sourceforge.net/projects/units-in-java/?source=directory |
| Constants and Units | MatLab | Yes | https://github.com/mariomerinomartinez/constants_and_units |
| Converge | Swift | No | https://github.com/daneden/Converge |
| Conversion | PHP | Yes | https://github.com/abhimanyu003/conversion |
| Conversion | Java | No | https://github.com/VaishnavRajesh/conversion |
| Conversion | Java | No | https://github.com/SoftronixGlobal/Conversion |
| Conversion | Java | No | https://github.com/2aredford/Conversion |
| Conversion | C++ | Yes | https://github.com/simonmeaden/conversion |
| Conversion | Java | No | https://github.com/ali-hamad/Conversion |
| Conversion | Java | No | https://github.com/ironwire/Conversion |
| Conversion Calculator | C++ | Yes | https://github.com/dtuivs/Converter |
| ConversionApp2 | Java | No | https://github.com/dpinero/ConversionApp2 |
| Conversionr | R | Yes | https://github.com/alexnakagawa/conversionr |
| ConversionsApp | Objective-C | No | https://github.com/JoeCortopassi/ConversionsApp |
| Convert | Swift | Yes | https://github.com/danielbyon/Convert |
| Convert | Python | No | https://github.com/sugarlabs/convert |
| Convert Units | Java | Yes | https://github.com/ben-ng/convert-units |
| Convert-Quantities | JavaScript | Yes | https://github.com/kendru/convert-quantities |
| Convert-units | Ruby | Yes | https://github.com/tanvir002700/convert_unit |
| Convert.js | JavaScript | Yes | https://github.com/YazilimMuhendisiyizBiz/convert.js |
| ConvertAll | Python | Yes | https://sourceforge.net/projects/convertall/?source=directory |
| Convertee | JavaScript | Yes | https://github.com/isquaredcreative/Convertee |
| Converter | PHP | Yes | https://github.com/cartalyst/converter |
| Converter | Swift | No | https://github.com/dhunten/Converter |
| Converter | C++ | Yes | https://github.com/KerryL/Converter |
| Converter | HTML | No | https://github.com/annaavanesyan/converter |
| Converter | JavaScript | No | https://github.com/Urrby/Converter |
| Converter | PureScript | No | https://github.com/moniyax/converter |
| Converter | Java | No | https://github.com/NaOHman/Converter |
| Converter | Java | No | https://github.com/sunil512/Converter |
| Converter | Java | No | https://github.com/jessepasos/Converter |
| Converter | JavaScript | No | https://github.com/zlargon/converter |
| Converter | C# | No | https://github.com/sun-haha/Converter |
| Converter | Java | Yes | https://sourceforge.net/projects/con-vert/?source=directory |
| Converter | JavaScript | No | https://github.com/ziggy42/Converter |
| Converter | Java | No | https://github.com/SurajPrasadd/Converter |
| Converter | Python | No | https://github.com/hpjardon/converter |
| Converter | Java | No | https://github.com/napnie/converter |
| Converter | Clojure | No | https://github.com/andreasfrom/converter |
| Converter | TypeScript | Yes | https://github.com/ialex90/Converter |
| Converter | Python | No | https://github.com/XTremeRox/converter |
| Converter | C++ | Yes | https://github.com/scruff3y/Converter |
| Converter | Java | No | https://github.com/urielvan/converter |
| Converter | HTML | No | https://github.com/AmitBuchnik/Converter |
| Converter | Java | Yes | https://github.com/samWson/converter |
| Converter | Java | No | https://github.com/atsang36/Unit_Converter |
| Converter | C# | No | https://github.com/pfthroaway/Converter |
| Converter | C++ | Yes | https://github.com/dtalaba/convertor |
| Converter | Java | Yes | https://github.com/HanSolo/converter |
| Converter | C++ | No | https://github.com/stevenharradine/Converter |
| Converter | Java | No | https://github.com/khaldi-yass/Converter |
| Converter | Objective-C | No | https://github.com/milkyNik/Converter |
| Converter | Java | No | https://github.com/hirenj0009/converter |
| Converter Application | Python | No | https://sourceforge.net/projects/converter-application/?source=directory |
| Converter_Classes | Ruby | No | https://github.com/gschool-g5/converter_classes |
| ConverterApp | C# | Yes | https://github.com/halezmo/ConverterApp |
| Convertinator | C# | Yes | https://github.com/hartez/Convertinator |
| Converting a value to an SI Unit String | C# | Yes | https://www.codeproject.com/Tips/414254/Converting-a-value-to-an-SI-unit-string |
| ConverTo | C++ | Yes | https://sourceforge.net/projects/converto/?source=directory |
| Convertor | C++ | Yes | https://github.com/mihaelateo/Convertor |
| Convertor | PHP | Yes | https://github.com/olifolkerd/convertor |
| Convertoroid | Java | No | https://github.com/abhii2028/Convertoroid |
| Convertr | R | Yes | https://github.com/ropenscilabs/convertr |
| convertR | R | Yes | https://github.com/colin-fraser/convertR |
| Coulomb | Scala | Yes | https://github.com/erikerlandson/coulomb |
| cppDegRad | C++ | Yes | https://github.com/grahamboree/cppDegRad |
| Cropio_Units_Converter | C++ | Yes | https://github.com/cropio/cropio_units_converter |
| CSharp-UnitsOfMeasure | C# | No | https://github.com/hediet/csharp-UnitsOfMeasure |
| CSUnits | C# | Yes | https://github.com/cureos/csunits |
| Cubico | C# | Yes | https://github.com/irperez/Cubico |
| Cue | C++ | No | https://github.com/OMGtechy/Cue |
| Cuis-Smalltalk-Aconcagua | Smalltalk | Yes | https://github.com/hernanwilkinson/Cuis-Smalltalk-Aconcagua |
| Currency | Java | No | https://github.com/billthefarmer/currency |
| DakaUnitConverter | Java | Yes | https://github.com/darrylfonseka/DakaUnitConverter |
| DDUnitConverter | Objective-C | Yes | https://github.com/davedelong/DDUnitConverter |
| Decibel Units of Measurement with C# Framework | C# | Yes | https://www.codeproject.com/Articles/1236193/Decibel-Units-of-Measurement-with-Csharp-Framework |
| Dftu | C++ | Yes | https://github.com/triblatron/dftu |
| Dimanalyser | Java | Yes | https://github.com/cymi/dimanalyser |
| Dimension-TF | Haskell | Yes | https://github.com/nushio3/dimensional-tf |
| Dimensional | Ruby | Yes | https://github.com/cch1/Dimensional |
| Dimensional | Haskell | Yes | https://github.com/bjornbm/dimensional |
| DimensionalAnalysis | Python | No | https://sourceforge.net/projects/dimensionalanalysis/?source=directory |
| Dimensioned | Rust | Yes | https://github.com/paholg/dimensioned |
| DimPy | Python | Yes | http://www.inference.org.uk/db410/dimpy/docs/docs/docs.html |
| Django-Unit-Field | Python | Yes | https://github.com/kohout/django-unit-field |
| Easyunits-rs | Rust | No | https://gitlab.com/imp/easyunits-rs |
| Efficient Scalars in Python | Python | Yes | http://russp.us/scalar-python.htm |
| Efficient Scalars in Scala | Scala | Yes | http://russp.us/scalar-scala.htm |
| EiffelUnits | Eiffel | Yes | http://se.inf.ethz.ch/old/projects/markus_keller/EiffelUnits.html |
| Elixir Unit Converter | Elixir | Yes | https://github.com/carturoch/ex_uc |
| Elm-tunits | Elm | No | https://github.com/gyulalaszlo/elm-tunits |
| Elm-Units | Elm | No | https://github.com/anfelor/elm-units |
| Engineering | C# | Yes | https://github.com/zhofre/engineering |
| EngineeringCalculator | C++ | Yes | https://sourceforge.net/projects/alwaysontopcalc/?source=directory |
| Enhancing User Experience - Part 1: A Simple Unit Converter Application | C# | Yes | https://www.codeproject.com/Articles/6667/Enhancing-User-Experience-Part-A-Simple-Unit-Con |
| Esos | C++ | Yes | https://sourceforge.net/projects/esos/?source=directory |
| Ethereumjs-units | JavaScript | No | https://github.com/ethereumjs/ethereumjs-units |
| EveryConverter | Java | No | https://sourceforge.net/projects/everyconverter/?source=directory |
| Fan measure | Fan | No | https://bitbucket.org/qualidafial/fan-measure |
| Fhir.Metrics | C# | Yes | https://github.com/FirelyTeam/Fhir.Metrics |
| Flowsnake | JavaScript | Yes | https://github.com/Eldelshell/flowsnake |
| FP Units | JavaScript | No | https://github.com/anthonydugois/fp-units |
| Frinj | Clojure | Yes | https://github.com/martintrojer/frinj |
| Frins | Scala | Yes | https://github.com/martintrojer/frins |
| FSharp.Units | F# | Yes | https://github.com/putridparrot/FSharp.Units |
| FURY | Fortran | Yes | https://github.com/szaghi/FURY |
| Gas Flow Unit Conversion | Python | No | https://sourceforge.net/projects/gas-flow-unit-conversion/?source=directory |
| GenUnitApp | JavaScript | Yes | https://github.com/halcwb/GenUnitApp |
| GenUnits | F# | Yes | https://github.com/halcwb/GenUnits |
| GIM.Quantities | C# | Yes | https://github.com/togakangaroo/GIM.Quantities |
| GNU Units | C# | Yes | https://www.gnu.org/software/units/ |
| GodSend | PHP | Yes | https://sourceforge.net/projects/godsend/?source=directory |
| Gorilla | Ruby | Yes | https://github.com/stephencelis/gorilla |
| Grobid-Quantities | JavaScript | No | https://github.com/kermitt2/grobid-quantities |
| Groovy-Unitconverter | Groovy | No | https://github.com/rhyolight/groovy-unitconverter |
| Gu.Units | C# | Yes | https://github.com/JohanLarsson/Gu.Units |
| Hazpy.Unit-conversion | Python | No | https://github.com/NOAA-ORR-ERD/hazpy.unit_conversion |
| HHUnitConverter | Objective-C | Yes | https://github.com/HiveHicks/HHUnitConverter |
| Imp Converter | C++ | No | https://sourceforge.net/projects/impconvert/?source=directory |
| Imperial & Metric Converter | VB .NET | No | https://sourceforge.net/projects/exconverter/?source=directory |
| IMT.Units | Java | Yes | https://github.com/imt-ag/imt.units-java |
| InkUnits | Swift | Yes | https://github.com/angelsolaorbaiceta/InkUnits |
| Insect | PureScript | Yes | https://github.com/sharkdp/insect |
| International System of Units Notation | C# | Yes | https://www.codeproject.com/Tips/869419/International-System-of-Units-Notation |
| Java library and framework: quantity | Java | Yes | https://sourceforge.net/projects/javaquantity/?source=directory |
| Java Measure | Java | Yes | https://sourceforge.net/projects/javameasure/?source=directory |
| Java Numbers with Unit | Java | No | https://sourceforge.net/projects/jnumwu/?source=directory |
| Java Unit Conversion Library | Java | No | https://www.openhub.net/p/jucl |
| JavaMeasure | Java | Yes | https://github.com/tkuebler/JavaMeasure |
| JC-Units | Python | Yes | https://github.com/jason0x43/jc-units |
| JConvert | Java | Yes | https://sourceforge.net/projects/jconvert/?source=directory |
| JFX Konwerter | Java | Yes | https://sourceforge.net/projects/jfx-konwerter/?source=directory |
| JNum | Java | Yes | https://github.com/attipaci/jnum |
| JQuantity: Precision Math Java Framework | Java | Yes | https://sourceforge.net/projects/jquantity/?source=directory |
| JS-quantities | JavaScript | Yes | https://github.com/gentooboontoo/js-quantities |
| JS-Quantities | JavaScript | No | https://github.com/mugendi/js-quantities |
| JSR 275 | Java | Yes | https://github.com/unitsofmeasurement/jsr-275/tree/master/src/main/java |
| JSR 363 | Java | Yes | https://jcp.org/en/jsr/detail?id=363 |
| Jsunitconverter | JavaScript | Yes | https://github.com/jerodvenemafm/jsunitconverter |
| JUNitConv | Java | Yes | https://github.com/duckler/JUnitConv |
| KingConverter | JavaScript | No | https://github.com/ryanr1230/KingConverter |
| Ktunits | Kotlin | No | https://github.com/sargunv/ktunits |
| Kuants | Kotlin | No | https://github.com/evacchi/kuants |
| Lathexa Units | JavaScript | Yes | https://github.com/lethexa/lethexa-units |
| Libquantify | C++ | Yes | https://github.com/damianorenfer/libquantify |
| Libre Unit Conveter | C# | Yes | https://sourceforge.net/projects/libreunitconverter/?source=directory |
| LibreEngineering | Python | Yes | https://sourceforge.net/projects/libreeng/ |
| Libunits | C | Yes | https://sourceforge.net/projects/libunits/?source=directory |
| Lua-Physical | Lua | Yes | https://github.com/tjenni/lua-physical |
| M2py | Python/Matlab | Yes | https://github.com/caiorss/m2py |
| Maegor | JavaScript | Yes | https://github.com/lukaskollmer/maegor |
| MagickScience | C++ | Yes | https://github.com/Iarfen/MagickScience |
| Magnitude | Python | Yes | https://github.com/juanre/magnitude |
| Magnitude| Java | Yes | https://sourceforge.net/projects/magnitude/?source=directory |
| MAIA Unit Converter | C++ | Yes | https://sourceforge.net/projects/maia-unit-conv/?source=directory |
| Maser | JavaScript/Python | Yes | https://github.com/justinbangerter/maser |
| Math-units | Perl | Yes | https://github.com/kenfox/Math-Units |
| Mather | Java | Yes | https://github.com/icasdri/Mather |
| mcs::units | C++ | Yes | https://sourceforge.net/projects/mcs-units/?source=directory |
| Measure | Perl | No | https://github.com/bluefeet/Measure |
| Measure | Swift | No | https://github.com/sdrpa/measure |
| Measure.js | JavaScript | No | https://github.com/alnesjo/measure.js |
| MeasureBundle | PHP | Yes | https://github.com/akeneo/MeasureBundle |
| Measured | Ruby | Yes | https://github.com/Shopify/measured |
| Measurement Unit Conversion Library | C# | Yes | https://www.codeproject.com/Articles/23087/Measurement-Unit-Conversion-Library |
| Measurement Unit Conversion Library | C# | Yes | https://www.codeproject.com/Articles/662335/Measurement-Unit-Conversion-Library |
| Measurement with units | C++ | No | https://github.com/AndrewWasHere/measurements_with_units |
| Measurement_Converter | Java | No | https://github.com/KinYee/Measurement_Converter |
| Measurement.js | JavaScript | Yes | https://github.com/Philzen/measurement.js |
| MeasurementConverter | Java | Yes | https://github.com/SBrooks75/MeasurementConverter |
| Measurements | PHP | Yes | https://github.com/marfurt/measurements |
| Measurements | Ruby | Yes | https://github.com/Krustal/Measurements |
| Measures and Units | C# | No | https://sourceforge.net/projects/measure/?source=directory |
| Measures with Dimensions | Racket | Yes | https://github.com/AlexKnauth/measures-with-dimensions |
| Memory_Units | Rust | No | https://github.com/pepyakin/memory_units |
| Mensura | Python | No | https://github.com/ypsilus/mensura |
| Meshy-quantities | Python | No | https://bitbucket.org/meshy/meshy-quantities/src |
| Meteor-Quantities | JavaScript | Yes | https://github.com/luzlab/meteor-quantities |
| Metiri | JavaScript | Yes | https://github.com/GCheung55/metiri |
| Metric | Java | Yes | https://github.com/gnapse/metric |
| Metric | Rust | Yes | https://github.com/coder543/metric |
| Metric | Nim | Yes | https://github.com/mjendrusch/metric |
| Mezur | JavaScript | Yes | https://github.com/guyisra/mezur |
| MilesMeter | Swift | No | https://github.com/mirokolodii/milesmeter |
| Misu | Python | Yes | https://github.com/cjrh/misu |
| MKUnits | Swift | Yes | https://github.com/michalkonturek/MKUnits |
| Natu | Python | Yes | https://github.com/kdavies4/natu |
| NGenericDimensions | C# | Yes | https://github.com/MafuJosh/NGenericDimensions |
| NGunits | Java | Yes | https://github.com/erussell/ngunits |
| NGX-UOM | JavaScript | Yes | https://github.com/catellanir/ngx-uom |
| Nim-Units | Nim | No | https://github.com/def-/nim-units |
| Node-units | JavaScript | Yes | https://github.com/brettlangdon/node-units |
| NUCOS | JavaScript | No | https://github.com/NOAA-ORR-ERD/NUCOS |
| NumericalChameleon | Java | Yes | https://sourceforge.net/projects/numchameleon/?source=directory |
| NumericalUnits | Python | Yes | https://github.com/sbyrnes321/numericalunits |
| NUnitConverter | C# | No | http://jamesnewkirk.typepad.com/posts/nunit_converter_v11.html |
| o2scl | C | Yes | https://github.com/awsteiner/o2scl |
| Ocalm-units | OCalm | No | https://github.com/pelzlpj/ocaml-units |
| Open.Measuring | TypeScript | No | https://github.com/electricessence/Open.Measuring |
| ParamPool | Python | Yes | https://github.com/hplgit/parampool |
| ParamPy | Python | Yes | https://github.com/matthewwardrop/python-parampy |
| PHP Unit Conversion | PHP | Yes | https://github.com/pimlie/php-unit-conversion |
| PHP Unit Converter | PHP | No | https://sourceforge.net/projects/phpunitconvert/?source=directory |
| PHP Units of Measure | PHP | Yes | https://github.com/PhpUnitsOfMeasure/php-units-of-measure |
| PHP-Conversion | PHP | Yes | https://github.com/crisu83/php-conversion |
| PHP-Units | PHP | Yes | https://github.com/hiqdev/php-units |
| PHPConverter | PHP | Yes | https://github.com/chapmang/PHPConverter |
| PHPMeasures | PHP | Yes | https://github.com/dcabanaw/phpMeasures |
| Phriky-Units | Python | Yes | https://github.com/unl-nimbus-lab/phriky-units |
| Phys-Types | C++ | Yes | https://github.com/akubera/phys_types |
| Physcon | Python | Yes | https://github.com/georglind/physcon |
| Physical | C++ | Yes | https://sourceforge.net/projects/physical/?source=directory |
| Physical | C++ | Yes | https://github.com/olsonse/physical |
| Physical Math | Python | Yes | https://github.com/matthagy/physmath |
| Physical Measure | C# | Yes | https://github.com/KiloBravoLima/PhysicalMeasure |
| Physical Quantities | Smalltalk/C# | Yes | https://github.com/timdetering/PhysicalQuantities |
| Physical Units for Matlab | MatLab | Yes | https://github.com/sky-s/physical-units-for-matlab |
| Physical-Quantities | Python | Yes | https://github.com/hplgit/physical-quantities |
| Physical-Quantities | Haskell | No | https://github.com/mtesseract/physical-quantities |
| Physical-Units | Scala | No | https://github.com/ppiotrow/physical-units |
| PhysicalQuantities | Python | Yes | https://github.com/juhasch/PhysicalQuantities |
| PhysicalQuantities | C# | No | https://github.com/KorzunK/PhysicalQuantities |
| PhysicalQuantities | Common Lisp | Yes | https://github.com/mrossini-ethz/physical-quantities |
| PhysicalQuantities | C# | Yes | https://github.com/timdetering/PhysicalQuantities |
| PhysicalQuantities | Python | No | https://github.com/ppfaff/PhysicalQuantities |
| PhysicalQuantities | C# | No | https://github.com/Traquina/PhysicalQuantities |
| PhysicalQuantities | Haskell | Yes | https://github.com/fehu/PhysicalQuantities |
| PhysicalQuantities | Python | No | https://github.com/d0cod3r/physicalQuantitis |
| PhysicalUnits | F# | No | https://github.com/kainous/PhysicalUnits |
| PhysicalUnits | C++ | Yes | https://sourceforge.net/projects/physicalunits/?source=directory |
| PhysicalValue | Swift | Yes | https://github.com/antonvmironov/PhysicalValue |
| Physics | Python | Yes | https://bitbucket.org/hppavilion1/physics |
| PHYSICS | Multiple | Yes | http://sergey-l-gladkiy.narod.ru/index/physics/0-14 |
| Physics-Measurement | JavaScript | Yes | https://github.com/victorpotasso/physics-measurement |
| Physikal | Kotlin | Yes | https://github.com/unitsofmeasurement/Physikal |
| Physikal | Kotlin | No | https://github.com/Tenkiv/Physikal |
| PhysUnits | C++ | Yes | https://github.com/martinmoene/PhysUnits-CT-Cpp11 |
| PhysUnits | C++ | No | https://github.com/rdlabspl/PhysUnits |
| Pint | Python | Yes | https://github.com/hgrecco/pint |
| Portable Unit Converter | JavaScript | Yes | https://sourceforge.net/projects/puc/?source=directory |
| PPX_Measure | OCalm | Yes | https://github.com/xvw/ppx_measure |
| Praktool | Python | Yes | https://github.com/zombofant/praktool |
| PreciseUnitConverter | JavaScript | Yes | https://github.com/bumxu/PreciseUnitConverter |
| ProgParam | C++ | Yes | https://github.com/qPCR4vir/ProgParam |
| PUMA Repository | Pascal | No | https://sourceforge.net/projects/puma-repository/?source=directory |
| Punits - Pluggable units | C | Yes | https://sourceforge.net/projects/punits/?source=directory |
| puny | Python | Yes | https://sourceforge.net/projects/puny/?source=directory |
| Purescript-Quantities | PureScript | Yes | https://github.com/sharkdp/purescript-quantities |
| Purescript-Units | PureScript | Yes | https://github.com/fluffynukeit/purescript-units |
| PyPhys Class Library | Python | Yes | https://sourceforge.net/projects/pyphys/?source=directory |
| PyQuantity | Python | Yes | https://github.com/gabbpuy/PyQuantity |
| Python Quantities | Python | Yes | https://github.com/python-quantities/python-quantities |
| Python Unit Conversion Library | Python | Yes | https://sourceforge.net/projects/pythonconvert/?source=directory |
| Python-Physical | Python | Yes | https://github.com/EdwinChan/python-physical |
| Python-Units-Of-Measure | Python | Yes | https://github.com/katerina7479/python-units-of-measure |
| PythonUnitConverter | Python | Yes | https://github.com/Aaron1011/PythonUnitConverter |
| PyUnitConverter | Python | Yes | https://github.com/jyri78/PyUnitConverter |
| Pyvalem | Python | Yes | https://github.com/xnx/pyqn |
| qMetrics | C++ | Yes | https://launchpad.net/qmetrics |
| QSAS | C++ | No | https://sourceforge.net/projects/qsas/?source=directory |
| QtUnits | C++ | Yes | https://github.com/hrobeers/QtUnits |
| Quan | C++ | Yes | https://sourceforge.net/projects/quan/?source=directory |
| Quant | Python | No | https://github.com/colecocomo/quant |
| Quantified | Ruby | Yes | https://github.com/Shopify/quantified |
| Quantify | Ruby | Yes | https://github.com/spatchcock/quantify |
| Quantiphy | Python | Yes | https://github.com/KenKundert/quantiphy |
| Quantities | Haskell | Yes | https://github.com/jdreaver/quantities |
| Quantities | Swift | Yes | https://github.com/BradLarson/Quantities |
| Quantities | R | Yes | https://github.com/r-quantities/quantities |
| Quantities | MatLab | Yes | https://github.com/mikofski/Quantities |
| Quantities | C++ | Yes | https://github.com/djbarker/quantities |
| Quantities | Haskell | No | https://github.com/mtesseract/quantities |
| Quantities | Batchfile | Yes | https://github.com/greatfriends/Quantities |
| Quantities | JavaScript | No | https://github.com/jdrew1303/quantities |
| Quantities | C# | Yes | https://github.com/atmoos/Quantities |
| Quantities | Idris | Yes | https://github.com/timjb/quantities |
| Quantities | D | Yes | https://github.com/biozic/quantities |
| Quantities | C++ | Yes | https://sourceforge.net/projects/quantity/?source=directory |
| Quantities-Comparison | Python | No | https://github.com/tbekolay/quantities-comparison |
| Quantities, Units, and Values: An Object Oriented Implementation | C | Yes | https://www.codeproject.com/Articles/216191/Quantities-Units-and-Values-an-Object-Oriented-Imp |
| Quantities.jl | Julia | No | https://github.com/ElOceanografo/Quantities.jl |
| Quantities.net | C# | Yes | https://sourceforge.net/projects/quantitiesnet/ |
| QuantitiesLib | C# | No | https://github.com/isabellaalstrom/QuantitiesLib |
| Quantity | Haskell | No | https://github.com/irreverent-pixel-feats/quantity |
| Quantity | Ruby | Yes | https://github.com/bhuga/quantity |
| Quantity | PHP | Yes | https://github.com/phospr/quantity |
| Quantity | Ruby | Yes | https://github.com/aportnov/quantity |
| Quantity | Clojure | Yes | https://github.com/spellman/quantity |
| Quantity System | C# | Yes | https://github.com/ibluesun/QuantitySystem |
| Quantity Types | C# | Yes | https://github.com/objorke/QuantityTypes |
| Quantity.Net | C# | Yes | https://github.com/bcachet/Quantity.Net |
| QUDAL | C++ | Yes | https://sourceforge.net/projects/qudal/?source=directory |
| Quick Unit Converter | Java | Yes | https://sourceforge.net/projects/qunitconverter/?source=directory |
| Rails-Units | Ruby | No | https://github.com/scpike/rails-units |
| RealizedQuantities | Python | No | https://github.com/BayerSe/RealizedQuantities |
| Red-units | Red | Yes | https://gitlab.com/maxvel/red-units |
| RedStar.Amounts | C# | Yes | https://github.com/petermorlion/RedStar.Amounts/ |
| Rink | Rust | Yes | https://github.com/tiffany352/rink-rs |
| RockUnits | C# | Yes | https://github.com/gareth-reid/RockUnits |
| Rssfiz | Java | No | https://sourceforge.net/projects/rssfiz/?source=directory |
| Ruby Units | Ruby | Yes | https://github.com/olbrich/ruby-units |
| Ruby-Units | Ruby | Yes | https://github.com/davearonson/Ruby-Units |
| Run-Convert | JavaScript | No | https://github.com/cdbusby/run-convert |
| SBUnits | Swift | Yes | https://github.com/EBGToo/SBUnits |
| Scala-Quantities | Scala | No | https://github.com/Lastik/scala-quantities |
| Scala-units | Scala | Yes | https://github.com/bwkimmel/scala-units |
| ScalaQuantity | Scala | Yes | https://github.com/zzorn/ScalaQuantity |
| ScalaU | Scala | Yes | https://github.com/adrianfr/scalau |
| Scale | Swift | Yes | https://github.com/onmyway133/Scale |
| Scaler | Shell | Yes | https://github.com/emugel/scaler |
| Scientific Javascript | JavaScript | No | https://github.com/gkjohnson/scientific-javascript |
| Scientific Library | C++ | No | https://sourceforge.net/projects/scientificlib/?source=directory |
| ScientificQuantities | C++ | Yes | https://github.com/nourani/ScientificQuantities |
| Scimath | Python | Yes | https://github.com/enthought/scimath |
| SI | C++ | No | https://github.com/erdavila/SI |
| SI -- A Scala Library of Units of Measurement | Scala | Yes | https://gitlab.com/h2b/SI |
| SI-Units | Java | Yes | https://github.com/unitsofmeasurement/si-units |
| SIConv | Haskell | Yes | https://github.com/owainlewis/conventional-si-unit-converter |
| Silphid.Unity | C# | No | https://github.com/silphid/silphid.unity |
| SIMConverter | C# | Yes | https://sourceforge.net/projects/simconverter/?source=directory |
| Simple-Unit-Converter | JavaScript | No | https://github.com/smtaydemir/simple-unit-converter |
| Simple.Units | C# | Yes | https://github.com/oriches/Simple.Units |
| SimpleMeasurementConverter | Java | Yes | https://github.com/michaelstoops/SimpleMeasurementConverter |
| SimpleUnitConverter | C | Yes | https://launchpad.net/simpleunitconverter |
| SIUnits (#1) | Haskell | Yes | https://github.com/joewkr/SIUnits |
| SIUnits (#2) | C++ | No | https://github.com/Jajauma/SIUnits |
| SIUnits.jl | Julia | No | https://github.com/Keno/SIUnits.jl |
| SIUnitX | TeX | Yes | https://github.com/josephwright/siunitx |
| Sius | Java | Yes | https://github.com/mbe24/sius |
| Smart Units | Sidef | Yes | https://github.com/trizen/smart-units |
| Spectroscopist's Energy Converter | C | No | https://sourceforge.net/projects/specon/?source=directory |
| Squants | Scala | Yes | https://github.com/typelevel/squants |
| Sundew.Quantities | C# | Yes | https://github.com/hugener/Sundew.Quantities |
| Superquants | Scala | Yes | https://github.com/rudogma/scala-superquants |
| SwiftMeasurement | Swift | Yes | https://github.com/ken0nek/SwiftMeasurement |
| SY | Ruby | Yes | https://github.com/boris-s/sy |
| tConverter | PHP | No | https://github.com/tankotun/tConverter |
| TCX Unit Conversion Library | C++ | Yes | https://www.codeproject.com/Articles/103/TCX-Unit-Conversion-Library |
| TempConvert | Python | No | https://github.com/rootinchase/tempconvert |
| Temperature | Go | No | https://github.com/yanndr/temperature |
| Temperature Unit Converter | C | No | https://sourceforge.net/projects/temp-unit-converter/?source=directory |
| TemperatureConverter | Python | No | https://github.com/bobo333/TemperatureConverter |
| The Quantity Library | C++ | No | http://home.xnet.com/~msk/quantity/quantity.html |
| The Units of Measure Library | C++ | Yes | https://sourceforge.net/projects/tuoml/ |
| Trevor | JavaScript | No | https://github.com/ozgrozer/trevor |
| TundraMeasure.java | Java | Yes | https://github.com/Permafrost/TundraMeasure.java |
| UConverter | Java | Yes | https://sourceforge.net/projects/uconverter/?source=directory |
| UDUnits | Julia | Yes | https://github.com/Alexander-Barth/UDUnits.jl |
| UDUNITS-2 | C | Yes | https://github.com/Unidata/UDUNITS-2 |
| Udunitspy | Python | No | https://github.com/blazetopher/udunitspy |
| UltimateCalculator | Java | No | https://sourceforge.net/projects/ultimatecalculator/?source=directory |
| Umpy | Python | Yes | https://github.com/perdixsw/umpy |
| Uncodium.Units | F# | Yes | https://github.com/stefanmaierhofer/Uncodium.Units |
| UNeedIT Converter | C# | Yes | https://sourceforge.net/projects/uneedconverter/?source=directory |
| UniCon | Java | No | https://github.com/davoraleksic/UniCon |
| Unisum | Vue | No | https://github.com/askhat/unisum |
| Unit | Ruby | No | https://github.com/christinach/unit |
| Unit | C++/CMake/Python | Yes | https://github.com/njoy/unit |
| Unit | PHP | Yes | https://github.com/pounard/Unit |
| Unit | JavaScript | Yes | https://github.com/smartcar/unit |
| Unit | Go | No | https://github.com/kormoc/unit |
| Unit | Go | Yes | https://github.com/martinlindhe/unit |
| Unit | Java | Yes | https://bitbucket.org/hansolo/unit |
| Unit | VB .NET | Yes | https://github.com/AdamSpeight2008/Unit |
| Unit | PHP | No | https://github.com/komparu/unit |
| Unit | HTML | No | https://github.com/Bingde/unit |
| Unit API | Java | Yes | https://github.com/unitsofmeasurement/unit-api |
| Unit Conversion Wox Plugin | Python/PowerShell | No | https://github.com/rpalo/wox-unit-converter |
| Unit Conversions in C#/WPF | C# | Yes | https://www.codeproject.com/Articles/30569/Unit-Conversions-in-C-WPF |
| Unit Converter | C | No | https://github.com/nithjino/UnitConverter |
| Unit Converter | Scratch | Yes | https://sourceforge.net/projects/unitconverter12/?source=directory |
| Unit Converter | Java | No | https://sourceforge.net/projects/unitsconverter/?source=directory |
| Unit Converter | Python | Yes | https://sourceforge.net/projects/unit-converter/?source=directory |
| Unit Converter | REBOL | Yes | https://sourceforge.net/projects/tbunitconverter/?source=directory |
| Unit Converter Application | Java | No | https://bitbucket.org/cpresley/unit-converter-application |
| Unit Conveter | C# | Yes | https://sourceforge.net/projects/unitconversion/?source=directory |
| Unit Conveter using PHP and HTML | PHP | No | https://sourceforge.net/projects/stgmunitconvert/?source=directory |
| Unit Management Framework | Java | Yes | https://sourceforge.net/projects/quantitymanager/?source=directory |
| Unit of Measure Library for .NET | C# | Yes | https://www.codeproject.com/Articles/404573/Units-of-Measure-Library-for-NET |
| Unit of Measure Validator for C# | C# | Yes | https://www.codeproject.com/Articles/413750/Units-of-Measure-Validator-for-Csharp |
| Unit Var | Python | Yes | https://sourceforge.net/projects/unitvar/?source=directory |
| Unit_Conversion | Ruby | Yes | https://github.com/eternal44/unit_conversion |
| Unit_Conversion | Python | Yes | https://github.com/bastihaase/unit_conversion |
| Unit_Converter | Ruby | No | https://github.com/samuels410/unit_converter |
| Unit_Soup | Ruby | Yes | https://github.com/rutvij47/unit_soup |
| Unit-Conversion | PHP | No | https://github.com/h4kuna/unit-conversion |
| Unit-Conversion | JavaScript | Yes | https://github.com/srimanthk/unit-conversion |
| Unit-converter | PHP | Yes | https://github.com/jordanbrauer/unit-converter |
| Unit-Converter | JavaScript | No | https://github.com/jgalla/unit-converter |
| Unit-Converter | JavaScript | Yes | https://github.com/GTLook/Unit-Converter |
| Unit-converter | Python | Yes | https://bitbucket.org/brayvasq/unit-converter |
| Unit-Converter | JavaScript | Yes | https://github.com/TheMarco/Unit-Converter |
| Unit-converter | JavaScript | No | https://bitbucket.org/sergespaolonzi/unit-converter |
| Unit-Converter | JavaScript | No | https://github.com/war1025/Unit-Converter |
| Unit-converter | Java | No | https://github.com/ThanasiG/unit-converter |
| Unit-Converter | Java | Yes | https://github.com/AmitKumarSah/Unit-Converter |
| Unit-Converter | PHP | Yes | https://github.com/b-sebastian/unit-converter |
| Unit-Converter | C++ | Yes | https://github.com/mikeleppane/Unit-Converter |
| Unit-Converter | C++ | No | https://github.com/BoboTiG/unit-converter |
| Unit-Converter | JavaScript | Yes | https://github.com/MaicolBen/unit-converter |
| Unit-Converter.js | JavaScript | No | https://github.com/angeshpokharel/unit-converter.js |
| Unit-formula | Common Lisp | Yes | https://github.com/Ramarren/unit-formula |
| Unit.py | Python | Yes | https://github.com/fabian0010/Unit.py |
| Unit.styl | JavaScript | Yes | https://github.com/diessica/unit.styl |
| UnitComboLib | C# | No | https://github.com/Dirkster99/UnitComboLib |
| UnitConversion | Objective-C | Yes | https://github.com/unixpickle/UnitConversion |
| UnitConversion | C# | Yes | https://github.com/gkampolis/UnitConversion |
| UnitConversion | Python | Yes | https://github.com/UnitConversion/unitConversion |
| UnitConversion | C# | Yes | https://github.com/Mecteral/UnitConversion |
| UnitConversion | Java | No | https://github.com/yadavparmatma/UnitConversion |
| UnitConversion | Java | Yes | https://github.com/yfl007/UnitConversion |
| UnitConversion | C# | No | https://github.com/vsooraj/UnitsConversion |
| UnitConversionLib | C# | Yes | https://www.codeproject.com/Articles/787029/UnitConversionLib-Smart-Unit-Conversion-Library-in |
| UnitConvert | JavaScript | Yes | https://github.com/agnoster/unitology |
| UnitConverter | Java | Yes | https://github.com/nevack/UnitConverter |
| UnitConverter | PHP | Yes | https://github.com/nfraz007/UnitConverter |
| UnitConverter | Java | No | https://github.com/sunilthalore/UnitConverter |
| UnitConverter | Objective-C | No | https://github.com/basicsbeauty/UnitConverter |
| UnitConverter | C# | No | https://github.com/github-ganesh/UnitConverter |
| UnitConverter | Swift | No | https://github.com/SwiftEducation/UnitConverter |
| UnitConverter | C++ | No | https://github.com/Shaddox/UnitConverter |
| UnitConverter | Java | Yes | https://github.com/MarioDudjak/UnitConverter |
| UnitConverter | Python | Yes | https://github.com/mattgd/UnitConverter |
| UnitConverter | Java | No | https://github.com/sommukhopadhyay/UnitConverter |
| UnitConverter | Java | Yes | https://github.com/impateljay/UnitConverter |
| UnitConverter | Java | No | https://github.com/MarcKuniansky/UnitConverter |
| UnitConverter | Java | No | https://github.com/Ideally/UnitConverter |
| UnitConverter | Java | No | https://github.com/fnk0/UnitConverter |
| UnitConverter | Python | No | https://github.com/Demoleas715/UnitConverter |
| Unitconverter-Android | Java | Yes | https://github.com/dbrant/unitconverter-android |
| UnitConverter.htm | JavaScript | Yes | https://github.com/iterami/UnitConverter.htm |
| UnitConverterLibrary | C# | No | https://bitbucket.org/MADc0d3r/unitconverterpublic |
| UnitConverterUltimate | Java | Yes | https://github.com/physphil/UnitConverterUltimate |
| UnitConverterWin | C | Yes | https://github.com/NikolaiTyrMDS/UnitConverterWin |
| Unitful.jl | Julia | Yes | https://github.com/ajkeller34/Unitful.jl |
| UnitKit | Swift | Yes | https://github.com/otaviocc/UnitKit |
| UnitMan | C# | Yes | https://github.com/mbeloshapkin/UnitMan |
| UnitManipulationLibrary | C++ | Yes | https://github.com/OuaisBla/UnitManipulationLibrary |
| Unitmaster | C++ | No | https://github.com/oswjk/unitmaster |
| UnitOfMeasure (#1) | C# | Yes | https://github.com/Chef-Code/UnitOfMeasure |
| UnitOfMeasure (#2) | Scala | Yes | https://github.com/ricemery/unitofmeasure |
| UnitParser | C# | Yes | https://www.codeproject.com/Articles/1211504/UnitParser |
| Units | C++ | Yes | https://github.com/nholthaus/units |
| Units | Python | No | https://github.com/DanielSank/units |
| Units | Go | Yes | https://github.com/zn8nz/units |
| Units | C++ | No | https://gitlab.com/eclufsc/eda/units |
| Units | Go | No | https://bitbucket.org/ede/units |
| Units | Python | No | https://bitbucket.org/johanhake/units |
| Units | Rust | Yes | https://github.com/Boddlnagg/units |
| Units | Scala | Yes | https://github.com/nestorpersist/units |
| Units | PHP | Yes | https://github.com/ARCANEDEV/Units |
| Units | Go | Yes | https://github.com/antha-lang/units |
| Units | PHP | Yes | https://github.com/marando/Units |
| Units | Python | Yes | https://bitbucket.org/adonohue/units |
| Units | Elm | No | https://github.com/irpagnossin/units |
| Units | Haskell | Yes | https://github.com/goldfirere/units |
| Units | JavaScript | No | https://github.com/heygrady/Units |
| Units | Go | No | https://github.com/alecthomas/units |
| Units | Scala | Yes | https://github.com/KarolS/units |
| Units | Java | Yes | https://github.com/xxv/Units |
| Units | PHP | No | https://github.com/anstag/units |
| Units | C# | No | https://github.com/cardassianscot/Units |
| Units | C++ | Yes | https://github.com/lonkamikaze/units |
| Units | Swift | Yes | https://github.com/chrisjeane/Units |
| Units | Java | Yes | https://github.com/SamCarlberg/units |
| Units | PHP | Yes | https://github.com/rmasters/units |
| Units | Tcl | Yes | https://core.tcl.tk/tcllib/doc/trunk/embedded/www/tcllib/files/modules/units/units.html |
| Units | Ruby | Yes | https://github.com/woahdae/units |
| Units | R | Yes | https://cran.r-project.org/web/packages/units/index.html |
| Units | Haskell | Yes | https://hackage.haskell.org/package/units |
| Units | C# | Yes | https://github.com/engineers-tools/Units |
| Units | Go | Yes | https://github.com/smyrman/units |
| Units | C++ | Yes | https://github.com/tonypilz/units |
| Units | Multiple | Yes | https://github.com/saroad2/units |
| Units | JavaScript | Yes | https://github.com/dohliam/units |
| Units | C# | Yes | https://github.com/LabyrinthApps/Units |
| Units 2 | Clojure | Yes | https://github.com/mfey/units2 |
| Units and Measurements | Racket | Yes | https://github.com/Metaxal/measures |
| Units and measures for C++ 11 | C++ | Yes | https://www.codeproject.com/Articles/1088293/Units-and-measures-for-Cplusplus |
| Units by Stak Digital | JavaScript | Yes | https://github.com/stak-digital/units |
| Units Conversion Library | C | No | https://sourceforge.net/projects/units/?source=directory |
| Units D | D | Yes | https://github.com/nordlow/units-d |
| Units of Measure | C# | Yes | https://archive.codeplex.com/?p=unitsofmeasure |
| Units of Measure | Kotlin | Yes | https://github.com/kunalsheth/units-of-measure |
| Units of Measure Prototype | Haskell | Yes | https://github.com/adamgundry/uom-prototype |
| Units of Measurement | C# | Yes | https://github.com/mangh/unitsofmeasurement |
| Units of measurement for Ada | Ada | Yes | https://sourceforge.net/projects/unitsofmeasurementforada/?source=directory |
| Units of Measurement Systems | Java | Yes | https://github.com/unitsofmeasurement/uom-systems |
| Units of measurement types in C++ | C++ | No | https://www.codeproject.com/Articles/791511/Units-of-measurement-types-in-Cplusplus-Using-comp |
| Units_of_measure | C++ | Yes | https://github.com/Skeen/units_of_measure |
| Units-api | PHP | Yes | https://github.com/shrimpza/units-api |
| Units-Converter| C# | No | https://github.com/kolesnikova745/units-converter |
| Units-of-Measure | Scala | Yes | https://github.com/Mononofu/Units-of-Measure |
| Units-of-Measure | Java | No | https://github.com/timroejr/2.05-Units-of-Measurement |
| Units-parser | Haskell | No | https://github.com/adamgundry/units-parser |
| Units-Ruby | Ruby | Yes | https://github.com/bfoz/units-ruby |
| Units-System | Ruby | Yes | https://github.com/jgoizueta/units-system |
| Units-v2 | C++ | Yes | https://github.com/Corristo/units-v2 |
| Units.jl | Julia | No | https://github.com/sclereid/Units.jl |
| Units.jl | Julia | Yes | https://github.com/autocorr/Units.jl |
| Units.js | JavaScript | Yes | https://github.com/jairtrejo/units.js |
| Units4j | Java | No | https://github.com/echocat/units4j |
| UnitsC++ | C++ | Yes | https://sourceforge.net/projects/unitscpp/?source=directory |
| UnitsDotNet | F# | No | https://github.com/benhamner/UnitsDotNet |
| UnitsKit | Objective-C | Yes | https://github.com/stevemoser/UnitsKit |
| UnitsNet | C# | Yes | https://github.com/angularsen/UnitsNet |
| UnitsOfMeasure | C++ | No | https://github.com/ing200086/UnitsOfMeasure |
| UnitsOfMeasure | C# | Yes | https://github.com/capnmidnight/UnitsOfMeasure |
| UnitsOfMeasure | C++ | No | https://github.com/printfn/UnitsOfMeasure |
| UnitsOfMeasureBundle | PHP | Yes | https://github.com/PhpUnitsOfMeasure/UnitsOfMeasureBundle |
| UnitsOfMeasurement | C++ | No | https://github.com/grafwolg/UnitsOfMeasurement |
| Unitwise | Ruby | Yes | https://github.com/joshwlewis/unitwise |
| Unitz | JavaScript | Yes | https://github.com/ClickerMonkey/unitz |
| Unum | Python | Yes | https://bitbucket.org/kiv/unum |
| Unum | Python | Yes | https://sourceforge.net/projects/unum/?source=directory |
| Unum | Python | Yes | https://bitbucket.org/kiv/unum |
| Uom | Ruby | Yes | https://github.com/caruby/uom |
| UOM | Ruby | Yes | https://github.com/madriska/uom |
| UOM Conversion Library | Java | Yes | https://sourceforge.net/projects/uomcl/?source=directory |
| UOM-Domain | Java | Yes | https://github.com/unitsofmeasurement/uom-domain |
| UOM-Plugin | Haskell | Yes | https://github.com/adamgundry/uom-plugin |
| Uom.Dart | Dart | Yes | https://github.com/damondouglas/uom.dart |
| Using physical quantities and units of measure in C# programs | C# | Yes | https://www.codeproject.com/Articles/1066008/Using-physical-quantities-and-units-of-measurement |
| Validation Dimensions of Physical Quantities .NET | C# | Yes | https://www.codeproject.com/Tips/1005796/Validation-Dimensions-of-Physical-Quantities-NET |
| ValueWithUnit | C# | Yes | https://github.com/vbfox/ValueWithUnit |
| Vandelay | C++ | Yes | https://github.com/HaikuArchives/Vandelay |
| VUnits | Java | Yes | https://github.com/vaslabs/vunits |
| Web Unit Converter | C# | Yes | https://sourceforge.net/projects/web-unit-converter/?source=directory |
| Winds Units Converter | C++ | No | https://sourceforge.net/projects/windunitsconver/?source=directory |
| Working with Units and Amounts | C# | Yes | https://www.codeproject.com/script/Articles/ListVersions.aspx?aid=611731 |
| XamConverter | C# | Yes | https://github.com/brminnick/XamConverter |
| Xiny | Go | Yes | https://github.com/bcicen/xiny |
| XVertR - eXtensible units conVERTeR | JavaScript | No | https://sourceforge.net/projects/xvertr/?source=directory |
