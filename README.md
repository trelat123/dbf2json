<A name="toc1-0" title="dbf2json" />
# dbf2json

This small utility uses dbfread (from PyPI) to convert DBF files to JSON. Very simplistic. Could probably use a couple more features.

<A name="toc1-5" title="Usage" />
# Usage

    dbf2json <dbf_filename_input> (json_filename_input)

json filename is optional, will write to stdout if not given or `-`. If `-` is given for input, it will read from stdin.
