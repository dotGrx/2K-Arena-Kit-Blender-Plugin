
# WWE 2K Arena Kit Blender Plugin

Assortment of utility functions for assisting Arena development in WWE 2K games.



## Crowd I/O
```http
  To create a new crowd member, you select an existing crowd arrow **AND** the chair arrow below it then duplicate. The names of these objects do not matter.
```

#### Import

```http
  The supported file format for crowds is .INST, the importer will only accept this format.
```
#### Export
```http
- 'Crowd' or a master parent must be selected before exporting.
- Groups (the collections inside the master parent) must be named number:Name, the number corrosponds to in-game animation sets.
```
#### Animation Groups
```http
Here are the known examples.

- 0 = Bored with occassional cheer
- 1 = Moody crowd (smarks)
- 2 = Moody crowd (smarks) 2
- 3 = Generic standing chants
- 4 = Generic standing chants 2
##
##
- 15 = Generic standing chants 3
```
## Support

For support, contact Grix#2942 on Discord.

