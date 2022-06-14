---
title: 'SchemaBlocks Design Principles'
date: 2021-03-05
authors:
	- "@mbaudis"
---

## Mission Statement

SchemaBlocks aims to translate the work of the workstreams into data models that:

* Are usable by other internal GA4GH deliverables, such as the Beacon API.
* Are usable by Driver Projects as an exchange format.
* Aid in aligning the work streams across GA4GH.
* Do not create a hindrance in development work by other work streams. 

<!--more-->

## {S}[B] Status Levels

SchemaBlocks schemas ("blocks") provide blueprints for consensus schemas which help with the development of code based "products" throughout the GA4GH ecosystem. Here we propose a labeling system for those schemas, to provide
transparency about the level of support those schemas have from {S}[B] participants and observers.

The current status level of those recommendations is "proposed".

* `playground`
	- early development or import stage, of any quality
	- no recommendation; existence does not mean any current or future
	{S}[B] support
* `community`
	- reserved for schemas from GA4GH community contributors which are used in production (i.e. not individual ideas or concepts)
	- not recommended for direct integration into products
	- can serve as use-case based demonstrators and inspire GA44GH project modifications
* `proposed`
	- at least some {S}[B] contributors are in favour of such a block
	- the code may undergo considerable maturation
	- not recommended for integration into products w/o close tracking
	- contributions and discussions are encouraged
* `implemented`
	- mature block which is implemented in one or more {S}[B] aligned
	schemas
	- may be extended from a core block or be too specific for general
	("core") usability
* `core`
	- a schema block with recommended use
	- stable through minor version changes
	- has to be used in at least 2 standards/products approved by the GA4GH Steering Committee 
