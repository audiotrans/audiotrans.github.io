# Data Transmission using audible sound
Normally data is transmitted using electromagnetic waves but it is not the only way to transmit data wirelessly, Note: Its the best way till now. But in this project we will Transmit and Receive Text Data using Sound within the Audible range. 

![Set up for testing](https://raw.githubusercontent.com/audiotrans/audiotrans.github.io/main/audiotrans_set_up.jpg)

## How to set up for testing

#### Go to [audiotrans.github.io](https://audiotrans.github.io)

* Go to "Receive" and "Transmitter"  in two devices respectively.

* Make sure the MIC(Receiving device) and SPEAKER(Transmiting device) is close enough, and there is Minimum background Noise.

* In Transmitter, type the Message to be sent.

* In Receiver, type the Number of Characters of the Transmiting Message.

* Tap "Receive" right after tapping "Transmit", a 250 milliseconds delay is acceptable.

In this type of Transmission, both the transmitter and the receiver should be synchronised. Therefore it is known as Synchronous Data Transmitted.

## How it works (The Principle)

In the Transmiting end the "Message" is encoded into 7 bit binary form, eg: "S" -> 1010011. 
Then, it is Received in the Receiving end and is again decoded into Text form, eg 1010011 -> "S".

###### So How is it Transmitted?

Suppose we want to Transmit "S" whose Binary form is " 1010011".

If the Receiving end records a one second Beep it registers it as " 1 " and if a one second Silence it registers it as " 0 ".
Thus it takes 7 secs to transmit a single character ("S") or a 7 bit binary number.

Therefore, this system's data speed is " 1 bit/secs ".
To give you an idea how slow it is, the average normal Internet i.e. your phone's cellular network's data transmission speed (INTERNET SPEED) is about 2 crores(20 million) - 3 crores(30 million) bits per second.

---
This is slow but, this idea is used in large scale with Electromagnetic waves to provide you the LUXURY OF INTERNET.

Check out the Source Code above to know how we did it, moreover this is a Open-source project.

A project by _Smitesh Das_ & _Soumya Ranjan Das_ .
