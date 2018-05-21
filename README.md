# ArduSTM
Going from Arduino to professional with STM32 microcontrollers.

## Description
Going from nothing to programming microcontrollers is extremely difficult. Arduino makes that possible. Going from Arduino hobbyist/light professional to full professional is extremely difficult, my goal is for ArduSTM to make that more possible. 

I'd like to take the spirit of Arduino, which is what got me from not knowing what a microcontroller was in 2012, to now having invented a couple products (including one that helped with filming Hollywood movies) and to finally landing my dream job as an embedded systems software engineer on self-driving trucks at Uber Advanced Technologies Group\*. Now, I'd like to see if I can give back a little to help others like me--with my drive, dedication, and passion, to do what I've done too. 

I envision ArduSTM being an STM32-based toolkit which provides easy-to-use and easy-to-follow examples, including base source code and libraries as well as build tools, like Arduino does, to quickly get up and running with STM32. STM32 microcontrollers are a beast, and without this tool someone trying to get started with them needs either: several hundred hours and TONS OF RELENTLESS DEDICATION (was essentially my case), a job and peers/mentors to guide them (is now somewhat my case too), or something like this to break it all down and make it possible. Why does it have to be so hard!? Answer: it doesn't. Let's break it down a bit more.

## Approach
We will use the STM32-provided HAL libraries. We will NOT try to become our own thing. We will rely on STM32CubeMX and STM32 examples where it makes sense. We will *teach* how to do what we are doing and what we have done, by providing explanations, example code, tools, and demonstration videos. We will NOT turn away those who want to learn and isolate ourselves to the "experts only." We will embrace others. We will be respectful. We will be mentors ourselves. We will *teach those we mentor to become mentors too!* We will teach to fish by *first demonstrating **how** to fish!* This means sometimes *demonstrating how to fish* and then *handing over the fish* to someone to get them motivated and help them see how it's done! (If you aren't willing to periodically hand over a fish to someone seeking help, and to *frequently* *demonstrate **how** to fish* instead of just telling someone to go fish on their own, then get the hell out--you're not welcome here). We will use direct-register-manipulation where it makes sense. We will comment like crazy, because *we know that **every line of code is a teaching opportunity!*** We will include in our comments explanations where it makes sense, and reference document names, page and section numbers, and direct links to those documents so that those using these resources and studying our code can figure out how the hell we did it and where this stuff comes from (ex: register names, settings, bits and bitmasks, magic numbers, etc)! We will NOT overly complicate stuff and add too many complicated layers of abstraction just to show how smart we are and how much we know! We will NOT try to become our own stand-alone thing like Arduino is to AVR and Atmel ARM32. Rather, we will seek to become the stepping stones necessary to give an interested hobbyist the firm footing they need to cross the wide, rapids-filled river until they can begin to do things on their own by:
 1. Using our easy-to-use tools and libraries
 2. Learning how to use FREE (no-cost, but also open source if possible) IDEs like Atollic TruSTUDIO and System Workbench for STM32 (SW4STM32), as well as how to configure and use a toolchain from the command-line, how to upload, and how to use free and open source debuggers, as well as paid ones.
 2. Using the tools and example code provided by STM (ex: HAL and LL libraries, STM32CubeMX, STM32CubeF2/3/4/etc example code, etc)
 3. Using direct register manipulation by referencing the Reference Manuals, Application Notes, and other documents provided by STM or ARM
 4. Using other resources--either free or commercial, as they see fit. 

Once we have done these things, we can know we are successful. 

## Contributing

Start by reading the above. Then, as I start developing a coding style and preferences, follow my lead, improve or make suggestions where you see fit, and let's make the transition into the world of STM32 and from the position of an Arduino hobbyist to a professional embedded software developer a little bit easier.

Sincerely,

Gabriel Staples  
www.ElectricRCAircraftGuy.com

\**Note: my employer in no way is involved, nor do they endorse this code or project. This is a personal project only.*
 
