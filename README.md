## planifolia 0.3.1

`Planifolia` (from the second name of the orchid 'Vanilla planifolia') is a set of Pure Data abstractions designed to work without any compiled externals.

The abstractions implement a series of useful operations like arbitrary unary and binary operations in lists and arrays, quicksort, logical operators to check equality of arbitrary datatypes, easy OSC formatting/routing/sending/receiveing, etc. It also comes with toggle-based matrix GUI (designed to work with `iemmatrix` objects) and a matrix based step sequencer with some non usual features (independent tempo, beat and duration patterns, col/row/colrow modes, nice colors, etc).

Some bugs may still be there... ;)

#### abstractions

| abstraction | description |
|---|---|
| `[any.==]` | compares datatypes |
| `[array.binop]` | binary operations in arrays |
| `[array.rand]` | random populates an arrays |
| `[array.unop]` | unary operations in arrays |
| `[ls.binop]` | binary operations in list |
| `[ls.butlast]` | list but the last element |
| `[ls.choose]` | random choose an element of the list |
| `[ls.circgroup]` | groups elements into a circular list |
| `[ls.getRotate]` / `[ls.get]` | N rotated element of a list |
| `[ls.group]` | groups elements into a list |
| `[ls.iter]` | list iteration |
| `[ls.last]` | last element of the list |
| `[ls.max]` | greatest element of a list |
| `[ls.mean]` | mean of the floats in a list |
| `[ls.min]` | minimum element in a list |
| `[ls.mode]` | mode of a list |
| `[ls.nearest]` | gets closest value, index and difference in a list by giving a target value |
| `[ls.quicksort]` | quicksort algorithm implemented as a vanilla abstraction |
| `[ls.removeAt]` | removes element at index |
| `[ls.rotate]` | N rotation of a list |
| `[ls.scramble]` / `[ls.shuffle]` | randomize elements in a list |
| `[ls.ser.arithm]` | build an artithmetic series list |
| `[ls.splice]` | replaces element in a list with anothe list |
| `[ls.sum]` | sums elements in a list |
| `[ls.unop]` | perform arbitrary unary operations in elements of a list |
| `[mtxgui]` | vanilla matrix interface |
| `[mtxstep]` | vanilla step sequencer with some non-usual features |
| `[osc.in]` | simple way to receive OSC messages (UDP/binary, -f -u -b) |
| `[osc.io]` / `[osc.out]` | simple one-way or two-way OSC communication (over UDP/binary) |
| `[osc.match]` / `[osc.route]` | simple osc message matching/routing |
| `[packOSC]` | alias for `[slash.oscformat]` |
| `[slash.oscformat]` | tool to formating slash-styled osc lists |
| `[slash.oscroute]` | tool to routing slash-styled osc lists |
| `[slash.rawlist]` | removes slashes and returns raw list of osc address elements and message arguments |
| `[symbol.==]` | test if two symbols are equal |
| `[symbol.split]` | splits a symbol according to a char |
| `[symbol.value]` / `[symbol.v]` | stores a symbol value, just like `[value]` does for floats |

Brazilian percussion samples were gently provided by [Chico Correa](https://www.youtube.com/c/ChicoCorrea).