#cain space
Project to establish cain space.

What it takes to anchor spacetime is the act of defining some specific event in some CMB's phase space as a standard origin. Then any past or future event relative to it will have a universal and unique phase space coordinate with the same meaning to everyone simply prepared, everywhere. Universal, persistant spacetime stamps seems to me to have conceptual value and contain useful information. I'm not sure what all value yet, just a hunch.

I can see their use, for example, with blockchain or other crypto technologies where consistency, reliability and utility of meaning is important.

Canonical Hamiltonian phase space transformations between universal phase space points can be thought of or applied as services if you have common coin and a common map. That can't be a burdensome process though. Transform decompositions and optimizations must abound.  Arithmetic must be quick. 

Smartphones (and other systems) should have a cain1 = cainEvent(cainXform1) system call that returns an immutable token, type CAINEVENT, in cain1 for an event representing a transformation of the current approximate coordinate of the device in cain space. A CAINEVENT and a CAIN are the same object except that a CAIN cannot be made into a CAINEVENT, CAINEVENTS are immutable and are the same as a measurement.  A CAIN has the three standard components of a Hamiltonian phase space measurement: p, position Q, momentum vector and t, time. p q and t are the only things in a CAIN.  More complex objects can grow around them.  Units will be Planck length and time.  Finer is futile.  Large integers suggest themselves for internal representation.  How large?  There are 4.35E60 Planck units of time since the big bang, fits in a double int.  The size of the visible universe is 5.5E61 Planck units of length, also fits in a double int.  There are 3+6+1 = 10 individual pieces of information.  If double ints are used that's 640 bits of entropy.  The future range of time is 4600 times the current age of the universe.  The range of addressable space outside the visible universe is 364 times its size down to the Planck length where it becomes physically pointless to go any further.  This should be adequate and sufficient and even allows for the use of speedy residue arithmetic for + and *.  I don't remember what the best mutually prime factors of two integers is and whether that's big enough.

Instantiations of type CAINXFORM can hold any standard canonical phase space transformation and they can be composed as 

cainXform3 = cainCompose(cainXform1, cainXform2,...)

cain2 = cainXform(cain1, cainXform1) applies cainXform1 to cain1 where cain1 is type CAIN or CAINEVENT and the return is an event of type CAIN.

cain2 = cain1.cainFuzz(Entropy) fuzzes the event.  (plops a random number into the low order "Entropy" bits of representation.  Can be used to create a random cain space event if "Entropy" is zero.)

Functions are the usual Hamiltonian ones and obey Hamilton's Principle.

cainXform2 = cainXform1.cainDot is the time derivative of the transform cainXform1

cainXform3 = cainXform1.cainDotProd(cainXform2) has the ususal dot product meaning.

DATA = cain1.cainPosition is instantaneous Minkowski position of event cain1 in cain space.

DATA = cain1.cainMomentum is instantaneous Minkowski momentum of event cain1 in cain space.

cainXform2 = cainXform1.cainPosition is a transform for conversion of any CAIN to the Minkowski position in cain space.

cainXform2 = cainXform1.cainMomentum is a transform for conversion of any CAIN to the Minkowski momentum in cain space.

cainXform2 = cainXform1.cainPoissonBracket(cainXform2) has the usual definition of Poisson Bracket.

I need help with this set of member functions particularly with regards to what canonical set of tranformations should be admitted and how they should be represented, created, and edited.  Also generating functions and actions.  The heart of the matter.  Anyone?

A JavaScript first implementation would be best.  Of course the Web and and there is almost no device where a JavaScript environment isn't available.  Need a tidy interpreter ans/or simple IDE to develop it.

A CAIN can be used as a hypertext link that actually takes you somewhere in the space or presents some information about the point or both.  Information can be associated with it or not.  (Where is that stored?  Let it be always local.  No such burden should be placed on the infrastructure.) The associated information can be, among other things, the hypertext of a standard web site.  It is totally private until shared in some fashion which could be point to point.  Architecture needed here.  No authorities of any kind allowed.

https://en.wikipedia.org/wiki/Canonical_transformation.  One can use libraries of canonical transformation tools with a bridge between.  Perhaps such an environment would be the best place to put this.  Anybody know of an existing canonical transform library for Hamiltonian mechanics?  

http://www.thp.uni-koeln.de/gross/files/diplom.pdf goes deep into that.  Uses Mathematica which could be problematic if my RaspBerry Pi 3 with latest Raspbian didn't have that as well as full net access.  I might could just fire that up and see what it can do.  The paper tells me that the proper framework for defining and operating on all this is Mathematica.  With it and the packages he has added one can do anything I've contemplated here.  Connect that to a data source and this is under way.  I just wish I was facile in Mathematica.  Anyone? Some kind of simpler and more specific API such as I've started is also in order.  On the other hand, requiring a Mathematica license everywhere isn't a very good idea.  For development and test it can be a handy tool.  Tie it into IFTTT.  Asap.  It could be set up from the RPi and accessed by IFTTT as we limp our way up and it would be a fantastic tool thereafter.  Anyone?  To collaborate, use a RPi 3 with updated and upgraded raspbian.  Might as well swim in the same tidy ocean.  Dirt cheap too and accessable headless from LAN or WAN.  Just the board with a USB hard drive.  Sound adequate.  No voice.

It could (should) be a standard for the presentation and sensing of virtual reality. My left hand can know where your face is no matter whose gear you wear. The phase (sub)space position of everything in my environment becomes standardized. Virtual reality spaces can be unversally "mounted" in real spaces by transformation across sensors, brands, and brand names. The Tower of Babel is gone in a stroke.

Conceptually there is a tie in to the user-centric QBist view of quantum mechanics and to the thinking of Neal Stephenson in his brilliant novel Anathem.

Using a pair of cains one could arrange to track the (somewhat) real-time, universal interval between other events (or their transformations), which is what is usually of greatest interest, and easily allow the saving of Universal World Lines, or cainLines, either absolute or relative (after some arbitrary transformation.)

It could provide a new standard framework for geo-history that could be easy to explore and interact with.

A verifiable vote could be registered anywhere. A beacon could be established at any point in spacetime and tracked. You might want to compare what the beacon says with what something else at that same physical point says. Surveying becomes a simple matter of clicking a button at chosen points and saving the results. All are on the same standard.  Pairs of these beacons (with suitable dynamic and cryptographic transforms for and between them) could be used as private communication channels.  Such arbitrary channels can be completely beyond private eyes.  If you don't know the pair of cains defining the end points and the transforms in between it simply doesn't exist for you.  Channels can contain a perfectly private video chat created by any application at all.  Want to talk securely to someone's computer or phone or Alexa based on simply knowing where they are?  Piece of cake.

In fact I consider this an important thing to do if it hasn't been done. It's time, perhaps, to send up a bird with the right horns and some master synchronization capabilities to calibrate our other birds.

If I'm describing something that can be done short of flying birds I'd love to know more about it.

I created this project as a place for people who might understand it and its possible importance in order to discuss it and perhaps eventually create the Origin Event, or cainZero, and the framework for its use. I have few skills to apply to actually accomplishing it myself. Consider it preliminary at this particular cain.

The reason for calling it cain space is obscure and probably won't last. A rationalization is "CMB as inertial name". Heavy sigh.

A description I just wrote a friend: In simple terms it allows one to time stamp his place in the cosmos, including all relevant motion information, so that even a suitably informed creature halfway across the visible universe, would give it the exact same meaning relative to the cosmos that you and your friend in Santa Cruz do. A consecutive sequence of these stamps comprise something called a worldline. You could create a movie and anyone, anywhere in the connected universe would know and agree exactly where and when that was shot. It could be embedded there as a world line.  You could then anchor it to a camera so that anybody going there in cain space could see through it in a semblance of real time or delayed.  One could tune in to the same place at some other time to possibly get more information about it. So could someone in the once disconnected universe.  If two disconnected universes run into each other a tracking transform can embed either one into the other.  It's a static, continuous zipcode system for the cosmos. It's also, and probably most importantly, a universal indexable file system.  Not distributed, yet and maybe never.

A beacon, which is just a CAIN anywhere in cain space, could be established as a feed.  All who can address it can listen or watch using that point.  All who can reach close enough can add or delete.  Segmented rings of restrictions can be applied.  As many bits as must describe a CAIN the entropy of the space is huge.  As many bits remain after reasonably tracking something that the entropy of the subspace remains huge.  Room for lots of special events around the main attraction that are appropriately cordoned.

A product to which it's position in cain space could be added:

https://github.com/jins-meme/home/wiki

This would get the idea in people's hands before it did their heads. I ask for the priviledge of setting physical cainCMB while using them. All I need for that is the ability one time to grab a phase space point that is "known" relative to some static CMB that can be defined and sensed somewhere. The firmer tied to our GPS system that can be the better.  Publish that here and it's done. Then zero in cain space, cainZero, can become a transformed point from that point by declaration. A transform choice to be carefully made.

Does anyone who stumbles here know where I could get my hands on a perfectly good, used even, phase space point measurement registered somewhere from such a CMB space?  https://www.youtube.com/watch?v=YX4PZ-fW2YA  The more recent the better.  Anybody well versed in transformations that could help me select a point relative to that?  Once set its use can immediately begin.  The device sensor can use whatever is the best global positioning channel available but its resolution partially governs the precision within which realities can be made to match.  Near field matching should be a piece of cake regardless of the global accuracy.

This in the end could be Internet n.0 where I don't know quite what n is.  Its uniqueness as a universally addressable virtual ether can be guaranteed by declaration. It can be kept universe-stable and physically tracking (or hugging) "Real Reality" if it's adjustable with feedback transforms.  Multiple disjoint virtual ethers should be possible rooted in this unique one time capture of "Reality" or in any other such virtual ether.  These latter can be set up as real time transform filters with subspaces, and cross referenced functionally.  Phase space is a magic carpet and with an anchor it becomes frighteningly useful.  As I think I might have said, the practical link to quantum mechanics is as close as possible.  The thing is fully adaptable and capable of maintaining its own conformance to measurable reference things.  Beeables.  By using phase space a world of simulation is opened up immediately if someone knows how to find a way to get access and a bridge to it.  Prognostication becomes formalized.  I'll bet that capability is in the cloud somewhere as a service.  (All right, this could be called "Tron n" but I'd rather keep an innocuous name.)

Can Bayesian calculation be factored into this?  A QBist's workshop.  Anyone?

Need to add world lines and their construction.  Biggie, that.  That may be in the reference.  World line networks allow for conditional forking.  The world line system must support a node edge/representation with Hamiltonian actions/functions/generating-functions at nodes and perhaps at edges.  Where stored again.  Locally again.  Suck up to using all local storage for persistence.  Any device or user employing the package accepts the responsibility for his own shit and presumes that it can be moved around elsewhere.  

The system outboard of the user is completely imaginary and occupies no resources.  It simply can't go down and will exist entirely of what is working on whatever platform it is running on.  Distribution of the cainSpace state is under user control and physically exists anywhere they want it to.  No login needed, all that happens inside an event.  A restricted access control can be fabricated inside an event.  What can an anonymous login do.  Well, anything he's allowed to do by specifying an event.  He must know it precisely by name.  He can then write scripts and create measurements and world lines etc.  How about protecting existing content from a wide open work space with wide open access?  If you don't know an event you can't use it or abuse it.  If you do you will play by its rules when communicating with it.

How can it do indexing, well the enormous size of the space allows for very high entropy hashing of things that have been resolved. JavaScript under Node.js has become the environment of choice.  If a remote asks for data from one of my events I give it to him blindly and let the event itself deal with access issues.  It's an implied behavior.  I'm always unconditionally serving anything in my namespace.  If it exists, anyone can see it.  What events do is the problem of what's at the event.  

[The TransPuter lives and deserves re-introduction. I wonder how many of those you could connect on today's silicon.  Runs like stink with high clock rate.  Hyper-efficient architecture for this kind of task. This would fit a Transputer with Node like a glove.  A single TransPuter with JavaScript (Node) running on it could still be a formidable component.  And doable as hardware from foundries in any configuration.]

The address range of a coordinate in an event is 2^64.  The units are Plank length for spatial coordinates and Planc time for the time coordinate.  This allows for a cain space which can contain (2^64 (Planck)/ 8.8e26 (m/universe) / 1.6e-35 (m/Planck)) =  131 * 10^25 visible universes.  That ought to be enough.  Time can range over (2^64 (Planck) / 1.855e43 (Planck/second) * 31536000 (seconds/year)) =  3.63e-17 a small fraction of 1(years).  t needs much more range than 64 bits can give.  Another 64 migh.  Does JavaScript natively support larger numbers?  May need methods that can reach down to assembler at worst.  Residue arithmetic arises again.  Separate investigation.  Can a method in JavaScript work its way all the way down to the bytes and the assembler code that actually do basic arithmetic?  The CAIN objects must be written with that capability of customization.  That allows relatively slow platforms to perform as well as possible in cainSpace.

Hmmm, what is a good range for the t coordinate.

cain1.Copy(cain2) leaves in cain1 a copy of the data content of event cain2 if any.  Whatever content it might have had associated is lost.  Fuzz if it doesn't exist(time out.)  Whoever has it will fork it over.  Should more than one place have it, results are indeterminate, perhaps should return first among responders.  Ask and ye shall receive.  Access control must be provided by whatever is at cain1.  None need be.

How to create a full event in the first place.  The amount of memory an event can have associated is arbitrary.  A system function to bind existing memory to events is needed.  

cain1.cainBind(data) bind an event to a workspace copy of a block of computer data.  The amount of bound memory can be virtually without limit.  Hashing comes through again to manage association if JavaScript lacks the facilities.  Anyone, anywhere can ask for a copy of that from me if they know cain1 and they will get it.  That unqualified server is always running and not normally visible to a user.  I'm not involved in that.  It can represent anything an imagination can cook up from web pages to data samples.  The WWW is thus enabled.  When I access one from someone else, I can dispatch it wherever I like within the platform of use.

cain1.cainDispatch(system command) offers the content from the event to the system.  A default mapping to the platform will be provided.  That could be a URL and end up in a browser.

Loss of power implies loss of all Node workspace content.  Empty.  Reset.  Saving important.

So at first milestone I should get to where, via a JavaScript console (node.js), I can request and receive an event between devices.  JavaScript must be built around node.js for communications, rather than dumb IP.  Next milestone presentation of results.  That's independant of the transport once it is working.  Transformations for the third milestone.  Make a world line out of a .gif and display it.  Time to stop thinking and learn Java on my Raspberry Pi.

Well, time to stop thinking for a while and spend some time learning how to straddle this node.js environment that seems so slick.  Not too goddamned long I hope.  I wonder if a node.js course might be the best way to learn JavaScript.  Communications problems non-existent and can serve the same data as whole the bloody internet.  Solved.  

Node.js is awesome.  It's REPL, invoked by the word node, can do everything I want in terms of system building and testing on any machine.  I can run it from my Raspberry Pi and identically from my Windows 7 machine.  Sharing is a breeze.  Again, the node dependance will remain under the covers and hidden so it can be replaced by something more appropriate or with greater speed.  Node.js remains as a tool for developers to use any other way they want.  I can actually begin coding for doing demonstrable things in cain space.  It exists merely because I say it does and anyone is free to use it.  A way to poke at it collaboratively shouldn't be too far off.  Back to JavaScript tutorials.

The existence statement: By commiting the JavaScript cainBang.js file at GitHub I have brought into existence the cain space.  Any information that can be gleaned from that creation may be used in any way, or not, to form "cainZero", the consensus (relative to some CMB) event in cain Space that represents zero in it will be named cainCMB.  Copyright is hereby expressly forbidden for the name cainZero or cainCMB.  The strings may prefix anything that names an event with full permission granted.  Events in cain space are very far apart and unlikely to collide.

Anybody is on the magic carpet should they wish to avail themselves or play in it a bit.  Usage details to follow.  It's pretty dead now and will be until I learn enough JavaScript to set it up.  There will be p(3),Q(6) and t(1) or 10 integers worth of data for an event in cain space.  The origin, of course, is a bit pattern of zeros.  Transforming that later to some actual, available if possible, CMB measurement called cainCMB will create an imaginary/real physical universe correspondence that can be refined.  That is where one would want to play for VR or geophyiscal application.  That will be my toy Operating Universe and soon can easily be yours too.  Currently cainZero and cainCMB coincide at the origin, zero.  When I give cainCMB a value it will be like the big bang for the physical universe.  References from that space correspond to real, physical stuff around you.  They won't at first unless I can find some data that references a known point in some CMB stationary frame.  I can in theory find here and now from that.  Then I set cainCMB to something physically meaningful once and for all.  Any error or drift can be handled through a transformed event.

So go to cainCMB (currently coincident with cainZero and containing the null or all zero data pattern.) and meet me there to get an enlightening and functional view of space time.  There's nothing there yet and only I am accessing it.  It is and will remain completely unrestricted and is still largely useless.  Improvements in that situation, including exactly how to get there and do something, will be announced here.

My best experience so far with a method for learning JavaScript is https://read.amazon.com/?asin=B00H1W9I6C I don't know where that link takes one who isn't me but hopefully to where and how it can be obtained.

My first task upon learning how will be to create and instantiate a variable event cainZero of type CAINZERO with contents of zero and publish it at GitHub in cainBang.js.  Arithemetic and coordinate members are JavaScript numbers. System only knows floating point real numbers so event arithmetic will have to resolve down to assembly code.  The length of a Javascript number is ok, just can't do normal arithemetic with them.  A primal variable of type CAINEVENT will have arithmetic methods defined to get to the best code for it.  That will be platform dependant, yuk, but workable.



Babylonians invented zero. Let's give it meaning once and for all.

This isn't a bad room to think in aloud.  I commit to posterity that everything about the room will remain free and open.  If courteous.
