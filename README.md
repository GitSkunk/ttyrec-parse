# ttyrec-parse
Simple parser for ttyrec files, because I needed one.

Usage:

from ttyrec import ttyrec

foo = ttyrec('YetAnotherStupidNethackDeath.ttyrec')
foo.parse()
print("Total frames: {}".format(str(foo.frame_count)))

