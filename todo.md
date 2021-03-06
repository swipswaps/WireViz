# To-do:

## Support for more connector types

* Inline connectors (IDC)
  * Possibly join two logical wires into one physical wire, add up length for BOM creation
  * Designators like W1_1, W1_2 or similar to group them?

## Support for more wire types

* Coax cables
  * Graphical representation
* Twisted pairs
  * Logical representation
  * Graphical representation
* Ribbon cables
  * Folds
  * Splits
  * Orientation of IDC connectors

## Support for more links/connections

* Cable splicing
  * as pseudo-connector?
* Heatshrink / sheathing

## Visualization

* Parse and render double-colored, striped cables ('RDBU' etc)
* Display picture of connector underneath (including pin 1 location)

## Export

* Export to PDF with frame, title block, ...

## Other

* Imrpove tutorial texts
* Create syntax reference / cheat sheet
* Set global parameters (show_pins, ...) and allow override on per-item basis
* Allow custom GraphViz code before/after WireViz-generated code
* Make "unit tests" for different features/situations
  * Missing parameters
  * Connection formats
    * single wire       1
    * multiple wires    [1,2,3]
    * wire ranges       [1-10]
  * Loops
  * ...
