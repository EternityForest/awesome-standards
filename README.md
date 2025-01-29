# awesome-standards

A celebration of materials, methods, formats, and protocols that are available anywhere and generally work without a fuss, and which are relevant to average DIYers or working engineers.

Entries should be widely accepted, with only a small number of alternatives covering most of their market, and they should be unlikely to be replaced within the next decade or two.

They should be highly compatible, not pseudo standards with subtle variations between manufacturers, or at least with small enough variation that it can be ignored.


These should be things that, if one were to require them for a project tutorial, nobody would be annoyed about having to go get them just for this one project.


They should not have any major health, safety, or environmental issues, and they should be relatively fault tolerant, requiring no special storage or handling, and they should still be usable even if they are off brand variants.

Unlike most lists, this one also aims to include a short bit of information on the items and how they are used.


## Mechanical 

### 1 1/8 Hole Panel Mount

A de facto common hole size. Lots of random stuff uses it.

### DIN 1/32

Panel Mount meters and the like use this size.

### 1/4-20 Screw

International tripod thread, common for general use in the US.  A very large range of cheap accessories exists, it's possible to mount almost anything this way.


### ISO Metric Screws

### Gridfinity

FOSS modular 3D printable system for storing small parts on a 42mm grid.


### 1.75mm filament 

Overwhelmingly common in 3D printing.  The raw filament can be cut by hand into things like hinge pins and connectors.



### Pipes and Plumbing 

The pipe and fitting sizes are highly standardized, only varying between countries.

### Lumber

At least in the US, a small set of sizes are overwhelmingly common.

They seem to be settled now, but the definitions of nominal sizes like a "2x4" have changed over time.

### Lego

These pieces have been compatible for decades, and now there are even high quality third party bricks.

### Velcro

Terrible for frequent use, but there is a semi-standard for it: the movable part usually has the scratchy side.


## Numbers

There are many sets of choices for "Preferred numbers", used for things like choosing what sizes of ropes or screws to make, ao that there's a "close enough" value for most purposes, without needing a million different sizes.

### 1, 2.5, 5, 10, 25, 50, etc

This sequence is used on test equipment when you only need enough options to get vaguely close enough.


### Practical and Highly Composite Numbers 

These show up everywhere due to how maby ways they can be divided.

## Failure Points

While they are not desirable, they are common and worth documenting, as many different devices fail in common ways.

### Brushed Motors

The brushes are made of carbon and can wear down.  They can sometimes be replaced easily.

### Long projections or cantilevers

Especially when they meet a much wider item at a sharp angle, a lot of sstrain is placed on the base, and it must be pretty strong to be reliable.

### Flash Memory 

It wears out if written too many times, and on some systems suddenly power failure corrupts it's content.

### Switches

Cheap switches fail fairly often. This includes things like rotary encoders.



## Paper

### Index Cards

The standard varies by country, but they are definitely common!

### A4/Letter


### A5

This size is great because it is close to half a US letter, and binders are widely available.  


### A6

Watch out with this one, filofax personal size are sometimes called A6, but they are not the same

### Golf Pencils

I'm not aware of any real competition for these, when extremely cheap and reliable writing utensils are needed.


### Six hole pattern 

There are different variations, but the majority use two groups with 19mm spacing within a group, meaning that a single adjustable punch can cover almost all the different paper sizes

## Batteries 

These sizes could be considered relatively common in modern devices.

### Chemistries

There are four modern rechargeable types, Li-ion, LiFePo4, Sodium-ion, and NiMh, and two disposable types, alkaline and 3v lithium found in button batteries.  It is very important not to try to recharge a disposable lithium (Although some disposable devices contain proper rechargeable batteries).

There are also 1.5v lithium, lead acid, and many other very specialized, outdated, expensive, or pollutive types that don't belong on this list.

### AA, AAA

AAA could be considered "The most standard" because devices that have any business using 1.5v batteries are generally so low power than size is a bigger factor than capacity.

### CR2023

Rechargeable versions have very different voltage. Unsuitable for almost anyone except 10+ year standby devices.

### 18650
Common in flashlights.

### 18500

Not easy to mistake for a non-lithium cell or a non-rechargable one.

### 21700

Common in larger flashlights.

### 16340

Common in headlamps and pocked sized lights.



## Cryptography

### SHA-256

This ancient hash algorithm still seems to be used in security critical applications, and it has hardware support almost everywhere

### SHA-3

Not as widely supported, but nonetheless probably the future of hashing, it seems to be beating out Blake in lots of applications, probably largely because it's a government standard.

### AES

Still seems to be the most common block cipher, after decades of use, with no significant progress in breaking it.


## Data

### Base64

### BIP-039
Word list of 2048 words for encoding binary data

### ISO8601

The world standard for encoding date and time as text.

### QR Codes

Amazing how completely these dominate the 2D barcode space!


### File Formats 

#### PDF

This document format, if used correctly, will probably be readable in 100 years. Or 1000.

#### Zip

This is so common that many other file formats are actually just renamed zips.  It is not strictly the best format, but it is a standard that works reliably just about anywhere, and the compression performance is usually good enough.

#### PNG

Still the common file format for lossless images such as line drawings.

##### SVG

The standard vector graphics format.  There are no other well known competitors.

#### Opus 

Essentially has made almost all other audio codecs obsolete in new designs.

#### MP3

Due to being one of the first popular standards, MP3 is highly compatible and remains absolutely relevant in 2024 despite Opus being far more bandwidth efficient.


#### AVIF

This image format is newly supported in all browsers and has excellent compression.  It is controversial because some prefer JPEG-XL, but that is not supported in most browsers.

#### JPG

This format remains completely relevant despite it's age because it is so universally supported, and still often good enough.

#### AV1

Hardware support is still up and coming for this video codec, but it appears that it may eventually be the most common standard.

#### h264/MP4

Still everywhere. Hardware supported by everything. Pretty much perfectly good.


#### M3U8

Standard for playlist files

#### JSON

The most common format for representing nested data.

#### SQLite

A SQL database in a single file. Extremely common, likely billions of instances globally, some say trillions.


#### HTML

The format used in web pages and many other applications.

#### Emulation ROMs

All popular game console formats from before 2010 or so, and many later ones, will probably be playable indefinitely in emulators.

#### STEP

The most common 3D CAD file format.

#### GCode

Instruction data for CNC machines or 3D printers

### Streaming Data

#### MPEG-TS

Sends video in fixed size packets for easy parsing


#### HLS

A method for streaming media on the Internet by polling for m3u8 playlist files.


## Apps

### Git

Almost nothing takes over the way Git has. For many it's essentially synonymous with version control.

### Bash

There are vast numbers of attempts to replace this, many are significantly better, but Bash is everywhere, and for the small set of things a shell is used for in more modern workflows, it's perfectly good.

### Excalidraw

This open web-based drawing app appears to be almost universally loved, is embeddabe in other applications,  and has no real competition as far as I know.




## Misc

### Standard and Olympic weight plates

These plates are used for weightlifting, or anything else that must be weighed down.   Standard is approximately 1 inch hole size,and Olympic is 2 inches, with the real size varying, I have heard 52mm hole size quoted for Olympic.

A 1 inch bar can be and often is used with an adapter sleeve for a 2 inch plate(these can be bought or 3D printed), but the reverse is obviously impossible, so I would consider 2 inches to be the "more standard" plate.


### 0.5 and 0.7mm mechanical pencils

Other sizes exist, but these two are by far the most common. 0.5 breaks a bit easier though, making it hard to say which is "The most standard".

### Sandpaper

"1/4 sheet" seems to be a pretty universal common size, although there are an insane number of special purposes ones.  It measures 4.5 x 3.5 inches.

Another size that may even be more common than that is 9 x 3.6, which also seems to be somewhat close to a quarter of a full sheet, just cut a  different way.

90mm x 30mm, sold as 3.5 x 1.2 inch or similar, seems to be a standard for micro detail sanding.

### No. 11 Blades

The common x-acto knife blade


### 1.88 inch, 3in core tape

Duct tape, packing tape, and similar things are usually this size.  Sometimes they are sold as 2 inch, when they are really 1.88in/48mm.

The core is generally always 3inches on tapes.

Packing tape seems to have three length categories, the small disposable dispensers, 55-65 yards for refillable dispensers, and 100-110yard rolls that seem to be used with big unwieldy guns.



### 1/8 and 1/4 Hex driver bits

Most small screws outside a wood shop can be driven with 1/8 bits.

### #8 and #6 wood screws

Any "medium size" ish screw in the US will probably be one of these two.

### 608 Bearings

There are many types of ball bearings, but the 608 size found in skateboards is perhaps the best known.


## Data Storage

### microSD/TF

### m.2 SSDs

### 2.5 and 3.5" hard drives


## Electronics


### Misc Parts

#### Cherry MX switches 

These were made for mechanical keyboards, tend to be highly reliable, and are widely cloned by many brands in different variations, all with a common pinout.

Notably, there are sockets available for them.

### Voltages


#### 90-260v 50/60hz

The world does not have a single voltage standard, but for many things this doesn't matter, modern devices are often made to work with the entire worldwide range of power supplies.

### 9v, 15v, 20v, 48v
These are the USB-PD common voltage levels, designing for one of these may make things a lot easier.

### 9-16v

Approximately range used for automotive-type devices, and things billed as nominally 12v.

#### 9-32v

Nominal "24v" devices often need to be designed for this range, because 24v batteries can have a pretty high voltage.

#### 3.3v

Common for microcontrollers at the moment.

#### 4.5v-5.5v

Default USB power level, usual for anything labelled as "5v". many chips use it directly, but this is less common for modern devices.

#### 0.9v-1.8v

In some extreme low power or intermittent use devices, designing for a single alkaline cell is often convenient.


### Soldering 

Soldering tip formats are not exactly settled, and they keep inventing more, but there is a small set of common ones, and a large number of less common ones.

I would not consider the 951 tip format a common uncontroversial standard despite the fact that it used to be extremely common, it has no integrated heater and not much cost advantage, it's mostly obsolete.

#### TS100

Used in many USB-C soldering irons

#### T12

Used in many affordable mains-powered stations

#### C210

Used in a lot of newer USB-C systems, mostly for smaller precision stuff, with tips being hard to find.



### Connectors 

#### IEC power connectors

#### USB-C

Possibly the most beloved connector of all time for average consumers.

#### Neutrik Speakon

#### Wago

These connectors join bare wire quickly and easily.

#### 2.1mm barrel jacks

Generally used to carry regulated 12v, but there is a lot of other things one can do with them, without creating any risk if accidentally connected.  Splitters can easily be used, unlike with USB which requires active electronics.

#### 3.5mm audio jacks

Widely used for things other than audio. 

#### 0.1mm header connectors 


#### 5.08mm Phoenix 

The pluggable screw terminals you sometimes see.

### Fuses

#### 5x20mm glass fuses

These seem to be by far the most standard common fuse, although they are delicate. Notably, panel mount holders are easy to find.

#### 6.3x32 mm ceramic fuses 

Used in multimeters.


#### 10*38mm ceramic fuses

Used in higher power applications 


#### Full size Automotive Fuses

Still extremely common but becoming fragmented until everyone settles on a mini fuse variant.


### Eurorack

Standard size for modular synthesizers

### 19-inch rack

Standard size for tons of random stuff 

### DIN Rail

Industrial control gear mounts on this




## Electronics, Prototyping 



### Arduino and related devices

### PlatformIO

Probably the biggest competitor and upgrade path from Arduino


## Programming Languages 

### C/C++

The one language family that is used almost everywhere, even though many want to phase it out.

### Rust

Seems to be the most likely replacement for C/C++ in many areas, although to what degree this will happen is still controversial.

### JavaScript and Typescript

Due to its use in browsers, JS is insanely popular and has expanded well outside of browsers.

Typescript enhances it with static types and seems to be the most popular language to compile to JS.


### Python 

One of the most common general purpose languages out there.

### SQL

The most common language for interacting with relational databases


## Protocols

### MQTT

### HTTP

### RTP

### SIP

### DMX512

Nearly all stage lighting is controlled using this protocol, or the IP based ArtNet(Or a variant, but those are usually compatible).


## Software APIs and System Utilities

### XDG
Freedesktop standardizes a very large number of things on modern desktop Linux, such as icons, thumbnails, shortcuts, etc

[https://specifications.freedesktop.org/]

### WSGI and ASGI
Specifies how apps, servers, and plugins interact in python.

### Laguage Server Protocol

Defines how support for programming languages is added to editors like VS Code. Sopported by many editors and most popular languages.

[https://en.wikipedia.org/wiki/Language_Server_Protocol]



## Cordage 

### 550 Paracord

4mm wide, theoretically rated to 550lbs. In practice rated to whatever the counterfeit company you bought it from decided to design for.


### Knots

In keeping with the goals of this list, these are chosen for a balance of effectiveness, ease of tying, and how widely known they are.

#### Lark's Head

Nearly all lanyards attach to electronics this way.

#### Sheet Bend

A common way to join two ropes which can be doubled for more security.

#### Clove Hitch

Considered to not be ideal for all cases, but it is quick and easy to tie.  Used to attach a rope to a fixed object.

#### Round turn and two half hitches 

A more secure way to connect to a fixed anchor. Includes the clove hitch as a component, by learning one you basically get the other for free.

#### Tautline Hitch

Makes an adjustable-tension loop.  There are several knots with this name, not all are equal, but one seems to be the most widely used.

#### Bowline

Makes a loop at the end of a rope which will not tighten down on an object.

#### Alpine Butterfly Loop

Makes a loop in the middle of a rope without requiring access to the ends.

#### Uni-knot

Usable in modern synthetic cords like braided spectra, a very secure way to attach a line to an object.

#### Stevedore Knot

An excellent way to make a wad at the end of a rope so it doesn't go through a hole

#### Square Knot

Used to tie bundles together. Never use this to tie two ropes together or it might slip.

#### Doubly slipped square knot 

Also known as the shoelace bow.

#### Constrictor knot

This should never be tied around a finger or anything like that, it is nearly impossible to undo, and could be used where one might use a zip tie.

#### Highwayman's Hitch

Pull the quick release tag and this instantly comes undone.


### Over-Under coiling 

Not actually a knot, but it is the best way to coil up and store rope and cabling.




## Misc Materials 

These are materials one could feel safe including in an online tutorial. they must not be excessively toxic, hard to find, or expire quickly, and must be multipurpose enough that an average person would not be annoyed if they had to buy some just for one project.

### Duct Tape

### Packing tape

Cheap and also acts as a dry erase surface 

### Poster Putty

Useful for pretty much any temporary mounting, especially keeping things from sliding on a desk. Ironically, it is not that great for hanging posters on a wallm

### Foam

There are many types, but they are often interchangeable, and things like wads of paper towels can even be substituted.


### Orbeez

These are a common solution for both decorative use and weighting things down, but they are a very large choking  hazard.

### Printer Paper

### Hot Glue 

This exists in two sizes, mini and full size.  Due to the greater features and performance of full size, with only a pretty limited difference in portability, I consider full size the "more standard" one, outside of compact rechargeable guns.

### PVA Glue 

### Keyrings/Split Rings

### Rubber Bands

These must be considered consumables, they do not last forever 


### Synthetic Oil

It can be argued forever about what the best general lubricating oil is, but they mostly all are used interchangeably by non specialists and therefore can be considered a standard product category.


### A4 or letter size paper

### Toilet Paper

Surprisingly useful for making paper mache and similar. With stronger glues, especially hot glue, it can be good for certain repairs.


### Rubbing Alcohol 

This exists in isopropyl and ethyl versions, pretty much equivalent.  If you need to care which one you have, you may in fact be getting too fancy.
Ironically, despite having man other uses, it's generally considered a bad idea to use this for wound care(this is not medical advice).



## Placeholders 

### Memes

Strings like "Steamed Hams" are often used as placeholder texts.

### Lorem Ipsum

A corrupted form of a text by Cicero.

>>> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### The Harvard Sentences

This set of very short phrases is often used as examples in audio technology.

### Passwords

hunter2 is a very common example password, named for a classic meme.

### People 

John and Jane Doe are often found in English, while Alice, Bob, and Eve are often used in programming and especially security tech.

The use of John for a toilet may derive from "John" once being a common placeholder for objects as well as possible.

### Programming 

foo, bar, baz, plugh, xyzzy, are all commonly found in English, with foo and bar being overwhelmingly common.

## Tools

These are tools one could reasonably expected any casual to serious DIYer to have, or quickly obtain.

### Flashlight 

If it's not USB- C rechargeable and doesn't have a replaceable battery, it's probably junk.  But good ones are very cheap and common now.

### Pliers

### Scissors or EMT shears

### Tinner Snips

The large scissor like cutters that can go through almost anything 

### 1/8 precision screwdrivers

Anything bigger is less portable and therefore less likely to be on hand if needed. Avoid designing stuff with screw holes too deep for interchangeable bit drivers if possible.

Sets with magnetic cases are the only way I know to avoid lost bits unless you have very good discipline.

### 1/4 Bazillion in 1 screwdrivers

### Wire Strippers

There are several kinds. The best choice is the kind that looks like pliers, where the wires go in the head part. Any other kind is expensive or a fussy hassle.


### Digital Multimeter 

Not found universally, but extremely cheap.


### Hammer

The small stubby hammers give the most control, which is probably what one wants for the very occasional work most people do with a hammer.

### Hex Keys

### Utility Knife 

Avoid designs that require using these on anything tougher than cardboard if possible, because of difficulty in controlling them. They are banned in some workplaces because accidents are just that common.


### Measuring Tape

Be aware when writing manuals that some people's tapes may only have inches.


### Android or iOS device 

People frequently do not have a laptop on hand, ideally ensure that any smart device related maintenance tasks can be done using a phone.

### Arc lighter

### Butane Lighter

### Sharpening Stones

These are used by grinding a blade on them while keeping a consistent angle. During this process a "burr" forms on the opposite side, which is then removed when you flip the blade, alternating sides with progressively less force and time.

What they don't tell you is that if the burr is too big, it may rip off, leaving some dullness in it's place, and it is hard to feel a burr that is properly sized.  Using a flashlight at the right angle can make very tiny burrs visible, and even just kind of guessing may be a better plan.


## Excluded Items

### Super Glue

Due to short shelf life once opened, it cannot be relied on to "Just kind of always be lying around". It smells bad and is slightly hazardous.

### Welding equipment of any sort

A classic example of a skill you can't learn in a few minutes from a book of YouTube, and the equipment is large, expensive, and requires power.

