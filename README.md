# Ultrasonic_Cleaner_Transducer

* **Determining the resonance frequency of transducer**

I drove the transducer with a signal generator (sg). Visualized output of sg and current of transducer with the help of an oscilloscope. 
By varying sg output frequncy i obsorved the transducer current . The frequency which resulted in maximum current is the resonance frequency of transducer.

* **Determining model parameters of transducer** 

I used Butterworth-Van Dyke equivalent circuit. Did an ac circuit analysis and formulated the transducer current. With the help of scipy.optimize.differential algorithm i managed to find optimum parameter values of equivalent circuit. 
