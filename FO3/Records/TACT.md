TACT
====

Talking Activator

## Format

Count | Field | Name | Type | Info
------|-------|------|------|-----
+ | EDID | Editor ID | cstring |
+ | [OBND](Fields/OBND.md) | Object Bounds | struct |
 | FULL | Name | cstring |
+ | | [Model Data](Fields/Model.md) | | This is a field collection.
 | SCRI | Script | formid | FormID of a [SCPT](SCPT.md) record.
 | | [Destruction Data](Fields/Destruction.md) | | This is a field collection.
 | SNAM | Sound | formid | FormID of a [SOUN](SOUN.md) record.
 | VNAM | Voice Type | formid | FormID of a [VTYP](VTYP.md) record.
 