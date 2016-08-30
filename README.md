Simple Diceware Password Generators
===================================

Tools for generating [diceware passwords]("Diceware homepage" http://world.std.com/~reinhold/diceware.html).

Because we don't always have dice by our side (nor do we want to roll them 30+ times).

If you don't want to spend the handful of minutes coding this yourself, I've
done it for you in a way that you should be able to run out of box for most
platforms. No compiling, no exotic toolchain required. Download and execute. If
figuring out how to run these takes longer than a couple of seconds, I've
probably failed.

What's Included
---------------

+ A Python version

        $ python diceware.py
        slat zloty chris gripe coyote pond
        $ python diceware.py -h
        usage: diceware.py [-h] [N]

        Generate a diceware password.

        positional arguments:
          N           The desired number of diceware words for your password

        optional arguments:
          -h, --help  show this help message and exit

+ A Bash version (uses `/dev/urandom`). 

        $ chmod u+x diceware.sh
        $ ./diceware.sh
        slog mammal ra den k's qb
        $ ./diceware.sh -h
        usage: diceware.sh [-h] [N]

        Generate a diceware password.

        propositional arguments:
          N    The desired number of diceware words for your password

        optional arguments:
          -h, --help  show this help message and exit
