MM Autorewrite
========================

Dieses AddOn macht automatisch aus deinen Media Manager URLs schöne URLs (über den OUTPUT_FILTER).
Funktioniert für alle Attribute (src="index.php..", href="index.php...", jedoch nicht für SRCTAG). Die Attribute können eingestellt werden.

> index.php?rex_media_type=ImgTypeName&rex_media_file=ImageFileName

wird zu

> images/mediatype/filename.jpg

Es wird automatisch innerhalb von src, href und data-highresmobile gesucht. Es können weitere auf der AddOn Page angegeben werden.

Voraussetzungen
----

* yrewrite AddOn
* media_manager AddOn
