# Kisparse - Parse Kismet output into Google Earth KML files

# Usage

    kisparse [-h] [--netxml [NETXML]] [--gpsxml [GPSXML]]
                    [--outfile [OUTFILE]] [--verbose]

    Change the meta data of the target commit(s)

    optional arguments:
      -h, --help            show this help message and exit
      --netxml [NETXML], -n [NETXML]
                            netxml file output by kismet
      --gpsxml [GPSXML], -g [GPSXML]
                            gpsxml file output by kismet
      --outfile [OUTFILE], -o [OUTFILE]
                            Name of the output file
      --verbose, -v         Generate verbose output

# About

I thought it would be nice to visualize the output of Kismet.

I found the beginnings of this code somewhere on Google Code, and I think it is attributed to this guy: https://github.com/grutz/pykismetkml (the node graphics are most definately his ... at least I think they are)

Regardless, it's been a while since I originally found it, and I've made some changes (improvements?) here, so ... that's the best effort I'm going to make at attribution.