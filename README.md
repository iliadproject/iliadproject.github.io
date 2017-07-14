# Iliad Web Framework

Iliad is not a traditional web framework. Heavily based on reusable stateful widgets, Iliad lets you build powerful dynamic applications easily. Iliad was designed around tight integration between Javascript components on the client and Smalltalk components on the server. It has the following main features:

- AJAX is completely transparent, no need to write JavaScript code.
- Includes a Formula package which makes it easy to build validated forms.
- Iliad is Web Server agnostic.
- Iliad Widgets can append or prepend other widgets.
- Smalltalk code can be evaluated on DOM events.

Iliad allows you to trigger Smalltalk code when an user clicks on a link or submit a form instead of bothering you with low level details. Thanks to its JavaScript layer Iliad automatically uses AJAX requests to update the client state, and it will nicely degrade to normal requests if javascript is not enabled, so you don't have to bother about that either.

# Download

Iliad pre-loaded images can be downloaded from the following links:

- Latest Iliad bleeding edge (Pharo 5.0)
- Latest Iliad bleeding edge (Pharo 6.0)
- Latest Iliad stable (Pharo 5.0)
- Latest Iliad stable (Pharo 6.0) 


# Installation

To install the Iliad stable version in a Pharo Smalltalk environment, evaluate:

```smalltalk
Metacello new
    smalltalkhubUser: 'hernan' project: 'Iliad';
    configuration: 'Iliad';
    version: #stable;
    load
```

To install the Iliad "bleeding edge" version in a Pharo Smalltalk environment, evaluate:

```smalltalk
Metacello new
    smalltalkhubUser: 'hernan' project: 'Iliad';
    configuration: 'Iliad';
    version: #stable;
    load
```

# Documentation

Iliad's documentation is evolving. We encourage newcomers to start with the [basic tutorial](http://web.archive.org/web/20130618134016/http://www.iliadproject.org:80/pages/Documentation/Getting-started). We are looking for contributors to help us improve this documentation.

If you can't find what you're looking for in the documentation, you can post an email on the [mailing list](http://groups.google.com/group/iliad).

# Community

## Mailing list

You can join the Iliad community by joining the [mailing list](http://groups.google.com/group/iliad).

## Development

Iliad was developed initially under [GNU Smalltalk](http://smalltalk.gnu.org/ "GNU Smalltalk"), but now it is maintained mainly in [Pharo](http://www.pharo.org), although a [Squeak](http://squeak.org/) [port](http://squeaksource.com/IliadDev/) is also available..

Submit bug reports to the [issue tracker](https://github.com/iliadproject/iliadproject.github.io/issues).

## Core developpers

- Nicolas Petton
- Sébastien Audier

## Pharo maintainers

- Steven Costiou
- Contributors (By alphabetical order)
- Bernat Romagosa
- Bèrto ëd Sèra
- Canol Gökel
- Eli Green
- Germán Arduino
- Göran Krampe
- Gwenael Casaccio
- Hernán Morales Durand
- Janko Mivšek
- Joachim Jaeckel
- Paolo Bonzini
- Stefan Schmiedl
- Tony Fleig

# MIT Licence

Copyright (c) 2008-2017 Nicolas Petton , Sébastien Audier, The Iliad Community

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 