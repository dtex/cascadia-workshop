# cascadia-workshop

## Goal
To enable JavaScript (aka ECMAScript) developers to explore the world of microcontrollers, sensors, switches, lights, and more using a programming language that is ideal for hardware and which they already know.

## Why is JS ideal for hardware?
* Modern hardware devices are becoming more and more connected. Whether it be watches, coffee cups, door bells, or whatever, they all interface with our phones, computers, or directly to the internet. JSON is the lingua franca for data interchange in this world of connected devices, and JSON is a clearly defined standard (ECMA-404). It is built upon JS object literals and "just works" in JavaScript.
* Hardware IO is asynchronous and JS has multiple, built-in mechanisms and patterns for doing things asynchronously. Callbacks, promises, and async await are all available options in the language. 
* Event emitters can easily be stood up in JavaScript and there is no better model for interacting with hardware.
  ```js
  button.on("press", () => { 
    light.on(); 
  });
  
  button.on("release", () => { 
    light.off();
  });
  ```
* Unicode
* Internationalization
* 1.9 million packages on npm alone

## Attendees should do this before the workshop
* Mac users should install XCode
* Windows users should:
  1. Download the Microsoft Visual Studio 2022 Community installer.
  2. Launch the installer. On the "Workloads" tab, select the "Desktop development for C++" option. On the "Individual Components" tab, select "Windows 10 SDK (10.0.19041.0)" (this should be preselected on Windows 10 systems but must be manually included on Windows 11 systems). Proceed with the installation as configured.
* @hipsterbrown Should we ask them to use xs-dev or to do any other pre-work? Internet and wi-fi quality are TBD

## Workshop goals (the first two hours)
* Moddable SDK install & setup
* ESP8266 SDK setup
* Project Management
* Blink on-board LED
* Blink an external LED
* Control an external LED with a button
* Control an external LED with temperature

## Post workshop goals (office hours)
* Interface with a 3rd party API via wi-fi and do something with your hardware

## BOM
* Moddable 3 (includes ePaper display)
* 3 x LED's
* 3 x 330 ohm resistors for LED's
* Prototyping board
* Button
* 10k ohm resistor for button
* TMP36
* 10 x M to M jumper wires

## BOM Nice to haves
* USB A <-> USB Mini (for programming, not just power) (or is it micro? I get 'em confused)
* USB battery to make projects portable
* A box to keep stuff in
