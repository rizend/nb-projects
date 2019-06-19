# Noisebridge Technical Projects list

The "point person" for each project is someone who is familiar with its current state that you should feel free to reach out to
about it.  Generally they are also around Noisebridge on a semi-regular basis and can answer questions in person.  Pull requests
to update the state of projects here, add Noisebridge projects, etc. are welcome.

## Infrastructure projects
---
### ansible

Noisebridge's "critical" infrastructure (website, wiki, mailing list, etc.) is deployed by an ansible playbook we store on github.

Code: [noisebridge/infrastructure formerly noisebridge/ansible](https://github.com/noisebridge/infrastructure)

Point person: [@_ar](https://discuss.noisebridge.info/u/_ar)

### donate.noisebridge.net
donate.noisebridge.net was written in ruby but has ended up unmaintained due to lack of people familiar with ruby at Noisebridge.
We're rewriting it in python since many more people at Noisebridge are familiar with it and we have an active weekly python class to teach
more people in our community.  The server that ran the old ruby version has been decomissioned so there is added pressure to get the python
version working.

Code:
 [old ruby version](https://github.com/noisebridge/donate.noisebridge.net)
 [new python version](https://github.com/noisebridge/python-nb-donate)

Point person (python version): [@rando](https://discuss.noisebridge.info/u/rando)

Point person (ansible deployment playbook): [@_ar](https://discuss.noisebridge.info/u/_ar)

### meetthings
Noisebridge's event listings are often out of data or inconsistent.  We hope to alleviate some issues by having a unified platform for
posting events.  Events are primarily post on the [wiki](https://www.noisebridge.net/wiki/Category:Events)
and [meetup.com](https://www.meetup.com/noisebridge/).

Point person: [@rando](https://discuss.noisebridge.info/u/rando)

Code: [noisebridge/meetthings on github](https://github.com/noisebridge/meetthings)

## In space projects
---
### Python space library
pyspacelib (Python space library) aims to be a python library that allows control of everything that can be controlled in Noisebridge.

Things it has some level of support for: [Flaschen-Taschen](https://www.noisebridge.net/wiki/Flaschen_Taschen),
the [DMX Lights](https://www.noisebridge.net/wiki/Disco_Lighting), and [Mary](https://www.noisebridge.net/wiki/Mary), Noisebridge's
in-space voice.

Point person: [@_ar](https://discuss.noisebridge.info/u/_ar)

Code: [noisebridge/pyspacelib](https://github.com/noisebridge/pyspacelib)

### Book Scanner
Noisebridge's [book scanner](https://www.noisebridge.net/wiki/Bookscanner) was built by the
[Noisebridge Digital Archivists](https://www.noisebridge.net/wiki/Digital_Archivists) a number of years back.
It's currently functional, but could use some love.  Things I think would be useful:

- Make sure everything is setup properly (it got moved around recently and the computer that runs it was hanging off
the table it was on by various cables).
- Write / update documentation for using it.
  - Print out, laminate, and attach documentation so that someone who just walks up can easily figure out how to operate it.
- Create gui for the diybookscanner software.
- Write up setup instructions for the software on the book scanner computer incase something happens to it.

Point person (for wiki editing issues, printing problems, and basic info): [@_ar](https://discuss.noisebridge.info/u/_ar)

Code: [danyq/diybookscanner](https://github.com/danyq/diybookscanner)

### Ordi Booth
[Ordi booth](https://www.noisebridge.net/wiki/Ordi) is a photo booth that uses [StippleGen](https://wiki.evilmadscientist.com/StippleGen)
to render the picture as a single line drawn by an [AxiDraw](https://wiki.evilmadscientist.com/AxiDraw).  Things that could be worked on:

- Add wooden panelling, paint, and make it look cool; see the second of the [Ordi sketches](https://www.noisebridge.net/wiki/Ordi#Sketches) for a design reference.
- Clean up / refactor the code and put it into a git repository.
- Move as much of the code as is possible python.
- Write up instructions for setting up the ordibooth software from scratch (e.g. in case of harddrive failure).

### NGALAC
The [Noisebridge Gaming Archivists Live Arcade Cabinet](https://www.noisebridge.net/wiki/NGALAC) is a thing.  Things to work on:

- figure out what needs to be fixed / work on and add it here :)
