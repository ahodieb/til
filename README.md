# Today I learned (#TIL)
I always enjoy learning learning new things, so i made it a habbit to learn something new everyday. This documents different interesting topics i learend over the years.


## Random 
- Tuning forks are used to tune pianos. [Wikipedia](https://en.wikipedia.org/wiki/Tuning_fork#Uses)
- Tuning forks are a building block of the quartz crystal powering watches. [Wikipedia](https://en.wikipedia.org/wiki/Tuning_fork#Uses)
- 1st of jan wasn't always the first day in the year.  It was different in alot of countries, e.g. Russia.
- How regular locks work [gif](https://giphy.com/gifs/interesting-around-explain-OTnDHCCFNZHwc)

## Science
- Low level infinity, Infinitely countable. [The infinite hotel paradigm](https://www.youtube.com/watch?v=Uj3_KqkI9Zo)

## Tech
- [Pentium](https://en.wikipedia.org/wiki/Pentium) processor name orign comes from pent as the 5th arch, Ium as the ending of the checmical elements.
- [Packet switching](https://en.wikipedia.org/wiki/Packet_switching) vs [circuit switching](https://en.wikipedia.org/wiki/Circuit_switching)
- [The Open Graph protocol](https://ogp.me/)

## Development & Coding
- ```===``` [Strict equality operator in javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)
- Synchronous Singleton Optimization using two if conditions one is synchronous and one is not to avoid the locking performance hit.
- [Gradle build system](https://gradle.org/)
- [Groovy language](http://groovy-lang.org/) a fun scripting jvm language, good option for writing DSLs e.g. gradle build scripts.
- [MsgPack](https://msgpack.org/index.html) It's like JSON but fast and small.
- `mokcito.verify()` is implicittly equivlent to `mokcito.verify(times(1))` [docs](https://javadoc.io/static/org.mockito/mockito-core/3.3.3/org/mockito/Mockito.html#4)

- [Why software architects fail](https://youtu.be/AkYDsiRVqno)
  - Has very relatable engineering falacies that i deal with daily, i've done all those wrong things at some point :D
- [Conventional comments spec](https://conventionalcomments.org/) - I've been doing some version of this for the past two years, glad there is a "spec" :D 

### Python 
- **[Print method](https://realpython.com/lessons/basic-usage-and-string-literals/)** 
  - I knew most of it, but it had surprising small useful nuggets.
  - Didn't know about end=, that makes animation on the terminal possible (using sequences of '\r')
  - Mocking [print in unit tests](https://realpython.com/lessons/mocking-print-unit-tests/).
- **map** can take multiple iteratiors as extra parameters
  -  It passes 1 element for each iterator to to the function, similar to `zip`
  -  Example: `map(f, a1, a2, a3)  is equevelant to map(f, zip(a1, a2, a3)) #f in the zip case takes a tuple as a parameter`
  -  Also similar to zip if the arrays are of different length, the elements in the longer arrays are ignored from the combined operation
  -  Example
     ```python
     a1 = [1, 1, 1, 1]
     a2 = [1, 1, ,1]
     a3 = [1, 1]
     list(map(lambda a,b,c: a+b+c, a1, a2,a3)) =>  [3 , 3]
     ```
  
### Javascript 
- **The Event loop**
  - [In the loop](https://www.youtube.com/watch?v=cCOL7MC4Pl0) (the best i've seen so far
  - [What the heck is the event loop](https://youtu.be/8aGhZQkoFbQ) (very simple and doesn't add much)
  - [requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)
 
- **react-dnd**
  - [Exploring react-dnd](https://www.youtube.com/watch?v=NW8erkUgqus&t=4s)
  - Context
  - Providers

## Uncategorized dump of the remaining things.
```
The two generals problem. 
CORBA [common object request broker architecture].
MMX , SIMD SSE



The idea of prime factorization. 
The idea of packet switching vs circuit switching.

Euclidian GCD
The number of counts in a range is given by (range /gcd (range, increment ))

SPARC has a very clever idea of using windows to avoid accessing the memory alot for saving and reading.  Shifting the Window by one makes the output as input for the next instruction.

Quantum computers
The basic idea of qubits . But still no idea about the computation techniques.

The intellectual venture labs . Applying the hacker mind set solving world problems. 

A slight insight into string theory. Visualization of the 9/11 dimensions




Euclidian infinite prime numbers. 

The event horizon.  Black Holes. Thought it might be disproved.

How regular key locks work

Branch predectors.  The behavior of sorting an array of random numbers on their speed

The Apollo navigation system.  How software was woven by wires! 

Convix hull.  A region where any two points can be connected by a straight line.

A real life kinda . use for chain rule in defrentiation.because a variable is dependant on another variable

Before clocks the word "sunwise" was used to indicate "clockwise" direction.
Clocks traditionally rotate "clock wise" because of the clock's predecessor: the sundial.
Clocks with hands were first built in the Northern Hemisphere  and they were made to work like sundials.

Why female lions hunt.
Males protect the pride
Females are less conspicuous.

Gaussian curvature:
Curvature gives strength.
hyperboloid shape is better than regular cylindrical chimneys because its curved in both direction 

Hens vs chickens

Microsoft uses a multi layered approach for it's AVhttps://blogs.technet.microsoft.com/mmpc/2017/12/11/detonating-a-bad-rabbit-windows-defender-antivirus-and-layered-machine-learning-defenses/

Go is type oriented, struct != class. so you can define methods to types.
https://twitter.com/rob_pike/status/942528032887029760

rlwrap
mokcito.verify(times(1)) is implicit


```
