FOPDoc
======

Documentation for the Fallout 3 and Fallout: New Vegas plugin file formats. 

The Oblivion, Skyrim, Fallout 3 and Fallout: New Vegas plugin file formats are all very similar, but while there exists good documentation for [Oblivion](http://www.uesp.net/wiki/Tes4Mod:Mod_File_Format) and [Skyrim](http://www.uesp.net/wiki/Tes5Mod:Mod_File_Format), there is no equivalent for Fallout 3 and Fallout: New Vegas. The aim is for this repository to become that equivalent.

### Contents

* The Fallout 3 plugin file format is documented in the [FO3](FO3) folder. The documentation matches the state of knowledge in TES5Edit as of 2 June 2014.
* The Fallout: New Vegas plugin file format is documented in the [FNV](FNV) folder. The documentation matches the state of knowledge in TES5Edit as of 2 June 2014.


### Format

This documentation is written in [GitHub Flavored Markdown](https://guides.github.com/overviews/mastering-markdown/) and stored in a Git repository on [GitHub](https://github.com/WrinklyNinja/fopdoc) because:

* Revision control is good.
* You can download the documentation for offline reading.
* Markdown gives readable plain text and can also be readily converted to HTML.
* GitHub offers in-browser editing and HTML preview for Markdown.
* GitHub makes it easier to make, share and integrate edits with others.

### File Format Data Source

The most complete open-source implementation of plugin parsers for these games is [TES5Edit](https://code.google.com/p/skyrim-plugin-decoding-project/), written in Delphi. The information on the file formats contained within its parsing code has been adapted into a reasonably generic format that programmers should be able to interpret regardless of their preferred language, similar to how it is presented by [UESP.net](http://www.uesp.net/wiki/Tes5Mod:Mod_File_Format).


### Contributing

I'm unfamiliar with Delphi / Pascal, so may have misinterpreted the TES5Edit source, missed out useful information, etc. Anyone who wants to double-check is very welcome to. If you have made further progress into decoding the data structures, please update the documentation with your findings. More generally, any potentially information that can be added is welcome.

To contribute, just fork the repository, and feel free to open issues on its issue tracker if you want to discuss something. You don't even need to leave your web browser, since the files can be edited and previewed on GitHub.
