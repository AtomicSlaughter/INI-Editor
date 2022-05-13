# INI-Editor
Code to modify and create INI files with qb64.

Usage

AddINI "FileName","Section","Key","Data"
  This adds, modifies or creates data in either a new ini file or edits an existsing one

DelINI "FileName","Section","Key"
  This deletes a specific key in an ini file

DelSec "FileName","Section"
  This Removes an entire section from an ini file

x$ = ReadINI ("FileName","Section","Key")
  This returns a string from an ini file entry
