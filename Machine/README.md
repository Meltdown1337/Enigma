# About the machine

The Enigma Machine is a device famously used in WWII by German forces to encrpyt messages. It worked by sending current through a series of "scrambled" rotors, and bouncing it from a reflection plate, in order to produce an output that could be mirrored and, in turn, decrypted.

### Project Scope 

This particular script is based on the M3 model, which features rotors I, II, III and a B Reflector. I encourage to fork my code and make it open to other models, or for that fact, any model. This project was compiled in GNU prolog.

### Usage

The predicate that deploys the enigma machine is enigma, which has five arguments.

``enigma([Input],[A,B,C],[[X,Y],[M,N]], Output)``.

The first argument is the input string, in the form a list.

The second argument are the three rings for encryption. They are in the order they are encountered, which is Rotor III, Rotor II and then Rotor I.

The third argument is a list of pairs that form the plugboard.

the fourth argument is the output, which should always be a variable.
