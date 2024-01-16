# MS Sans Serif Raster
A modern .otb conversion of the classic Windows font.

This is a complete conversion of Microsoft's old "MS Sans Serif" font, introduced in Windows 1.0 and used as the main system font all the way until Windows 2000, when it was replaced by Tahoma as the main system font and vector Microsoft Sans Serif was introduced.
In other words, this is a compilation of various localized versions of MS Sans Serif, converted to .otb format in order for it to be usable in modern Linux distros (and also converted to .pcf format for Qt-based applications).

It supports the following codepages: the entire Windows-125x series (1250, 1251, 1252, 1253, 1254, 1255, 1256, 1257, 1258) and also Windows-874. Which means the following scripts are supported: Latin, Cyrillic, Greek, Turkish, Hebrew, Arabic, Baltic, Vietnamese, Thai.

IMPORTANT: if you're planning on using this font for Qt-based apps, please use the PCF version. If you use the OTB version, some windows may be rendered super stretched-out.

WARNING: As I currently don't have a way to test this font out on many different installs, some things may not look quite right - things such as letter spacing not being right for certain symbols, or some symbols themselves not looking right. If something doesn't look right, please mention it in the issues (and, above all else, send screenshots).
