# PDF Export of PGP Survey Questions

## Quickstart
Got to the <a href="./Surveys">Surveys</a> folder above.

## To add a new survey to repository

* Git clone this repository.
* Use Google Chrome or Chromium browser. Login to pgp survey google account. Go to https://drive.google.com/drive/#, open the form in question (NOT the google spreadsheet, NOT the "live form"), and go to File>Print. "Save as PDF". The name should be based on the # and the name in https://my.pgp-hms.org/google_surveys. e.g. "[19] PGP Basic Phenotypes Survey 2015 [Form].pdf".
* Add the file to the /surveys folder
* In this readme file, update the total number of surveys, then make a new table with the latest number of responses. For help formatting the table, use http://www.tablesgenerator.com/markdown_tables
* Download the CSV response file and put in the /responses folder
* Add commit push changes (or fork and submit a pull request).

## About

Currently, the Harvard Personal Genome Project website provides a CSV export of the public results for each survey. While these CSVs have headers, the list of possible answers is not available.

As a temporary quickfix, I printed out to PDF the 13 surveys with publicly available results, as a temporary dump of both the survey questions and answer choices. Google Forms has a nice (css? javascript?) ctrl-p function. When you hit "ctrl-p" on the editable version of the form, it prints out a form you could fill out by hand (with all the options expanded).

For the "Participant Survey", which involved extensive dropdown menus (year and country), I printed out two version: one with all the choies (printed from the "editable" page) and one as the participant sees it, with the dropdown minimized (printed from the "submit" page).

I have included a CSV export of the responses as well (the filenames include a timestamp). For the most up-to-date dump of responses, see: https://my.pgp-hms.org/google_surveys

To make it easy to cross-reference the survey questions and the survey responses, I prefixed each file with the "PGP HMS Google Survey" number. These indices can also be found in the URL in the table below. For instance, Blood is marked with `[08]`.

## Todo

* Add these survey questions directly to the Tapestry website (https://my.pgp-hms.org/google_surveys), alongside the responses which are already available on there.
* Write a google script to allow import and export in something easy to parse (for instance, markdown).
* Write a script to automate updating of this repository

# Info

## Reference 

Total Number of Surveys: 14

### Dump, 2015-07-21

| URL # | Name                                                                           | Public Link                              | Responses (2015-07-21 22:15:12 UTC) | Participants (2015-07-21 22:15:12 UTC) |
|-------|--------------------------------------------------------------------------------|------------------------------------------|-------------------------------------|----------------------------------------|
| 1     | PGP Participant Survey                                                         | https://my.pgp-hms.org/google_surveys/1  | 3302                                | 2689                                   |
| 6     | PGP Trait & Disease Survey 2012: Cancers                                       | https://my.pgp-hms.org/google_surveys/6  | 1819                                | 1667                                   |
| 7     | PGP Trait & Disease Survey 2012: Endocrine, metabolic, nutritional, and immune | https://my.pgp-hms.org/google_surveys/7  | 1763                                | 1616                                   |
| 9     | PGP Trait & Disease Survey 2012: Blood                                         | https://my.pgp-hms.org/google_surveys/8  | 1696                                | 1581                                   |
| 9     | PGP Trait & Disease Survey 2012: Nervous system                                | https://my.pgp-hms.org/google_surveys/9  | 1663                                | 1553                                   |
| 10    | PGP Trait & Disease Survey 2012: Vision and hearing                            | https://my.pgp-hms.org/google_surveys/10 | 1717                                | 1625                                   |
| 11    | PGP Trait & Disease Survey 2012: Circulatory system                            | https://my.pgp-hms.org/google_surveys/11 | 1614                                | 1517                                   |
| 12    | PGP Trait & Disease Survey 2012: Respiratory system                            | https://my.pgp-hms.org/google_surveys/12 | 1573                                | 1502                                   |
| 13    | PGP Trait & Disease Survey 2012: Digestive system                              | https://my.pgp-hms.org/google_surveys/13 | 1596                                | 1514                                   |
| 14    | PGP Trait & Disease Survey 2012: Genitourinary systems                         | https://my.pgp-hms.org/google_surveys/14 | 1581                                | 1497                                   |
| 15    | PGP Trait & Disease Survey 2012: Skin and subcutaneous tissue                  | https://my.pgp-hms.org/google_surveys/15 | 1630                                | 1540                                   |
| 16    | PGP Trait & Disease Survey 2012: Musculoskeletal system and connective tissue  | https://my.pgp-hms.org/google_surveys/16 | 1628                                | 1513                                   |
| 17    | PGP Trait & Disease Survey 2012: Congenital traits and anomalies               | https://my.pgp-hms.org/google_surveys/17 | 1693                                | 1568                                   |

### Dump, 2015-09-03 20:46:23 UTC 

| URL # | Name                                                                           | Public Link                              | Responses | Participants |
|-------|--------------------------------------------------------------------------------|------------------------------------------|-------------------------------------|----------------------------------------|
| 19    | PGP Basic Phenotypes Survey 2015                                               | https://my.pgp-hms.org/google_surveys/19 | 259                                | 255                                     |

## Contact

Nancy Ouyang (nancy@curoverse.com)

## Export Date 

July 21, 2015.

## License

CC0 1.0 Universal
https://creativecommons.org/publicdomain/zero/1.0/

## Thanks

Thanks to www.tablesgenerator.com/markdown_tables, which I used to create tables in markdown (copy-pasting out of google docs).
