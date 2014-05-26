DEBR
====

Debris

## Format

Count | Field | Name | Type | Info
------|-------|------|------|-----
+ | EDID | Editor ID | cstring |
+* | | Debris Model | | This is a field collection, see beow for details.

### Debris Model Field Collection

Count | Field | Name | Type | Info
------|-------|------|------|-----
+ | DATA | Data | struct |
+ | MODT | Texture File Hashes | ?? |

#### DATA

Count | Name | Type | Info
------|------|------|-----
 | Percentage | uint8 |
 | Model Filename | cstring |
 | Flags | uint8 | See below for values.

##### Flag Values

Value | Meaning
------|--------
0x01 | Has Collision Data