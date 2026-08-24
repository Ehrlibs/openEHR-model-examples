
Example template for educational purposes, see some background and swedish instructions at https://github.com/modellbibliotek/kurs-openEHR-jan-2021 and partially translated to english at https://github.com/modellbibliotek/kurs-openEHR-jan-2021/blob/main/readme.english.md.
After those were written the "motionslopp" archetype a been slightly reworked and renamed to "Sport event".

In subdirectory /templates you find several formats of the same template. The ones that hava a ".sv" infix have been exported from Archetype Designer with Swedish as primary language (the others wew exported with English as primary).

## Roadmap/todo

### Template changes
- change multiplicity of Vital signs section to 0..* so that it can be recorded at multiple times in the same composition (and in form make sure timing for each time can be adjusted) 
- Put NEWS2 under same repeated Vital signs section so that it also repeats
- Add options for joints protection (elbows/knees)
- Add body temperature to vital signs (needed for e.g. NEWS2)
- Pulse oximeter sensor site

### Form changes
- Add automatic calculation of NEWS2 from other fields

### Other
- Possibly add CDS (GDL2?) rules for NEWS2 calculation