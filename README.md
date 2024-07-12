(ENG)  A boost converter is a DC-DC type switching converter that steps up the voltage while maintaining a constant power balance. This  high-efficiency boost converter circuit based on the popular TL494 IC, which has a minimum supply voltage of 7V and a maximum of 40V.Here i have used IF540N Mosfet as Switch.When the MOSFET is on, the inductor starts charging, the current through the inductor keeps on increasing, which gets stored in the form of a magnetic field.When the  MOSFET turns off, the magnetic field starts to collapse, and the current flows in the direction opposite of the charging current and it starts charging the capacitor.By continuously making the switch (MOSFET) on and off, I have created an output voltage that is greater than the input voltage. Now, i can control the output voltage by controlling the on and the off-time of the switch, and that is what we are doing in the main circuit. The 5V internal reference regulator output of TL494 IC's is the REF pin, which is pin-14 of the IC. The reference regulator is there to provide a stable supply for internal circuitry like the pulse-steering flip-flop, oscillator, dead-time control comparator, and PWM comparator.The frequency of the oscillator can be set by selecting timing components RT and CT. The regulator is also used to drive the error amplifiers which are responsible for controlling the output.The oscillator generates and provides a sawtooth wave to the dead time controller and the PWM comparators for various control signals and the oscillator frequency is equal to the output frequency only for single-ended applications. For push-pull applications, the output frequency is one-half of the oscillator frequency.This IC has two internal output transistors which are in open-collector and open-emitter configurations, by which it can source or sink a maximum current up to 200mA.This circuit can handle a maximum current of 19Amps,so when we want more Amps we need to change our inductor to biggest one .This TL494 Boost Converter circuit is made up of components that are very easily obtainable and this circuit can easily handle power more than 100Watts.If we are connecting a big load to the output of this boost converter circuit, a huge amount of current will flow through the PCB traces, and there's a chance that the traces will burn out. So, to prevent the PCB traces from burning out, we have increased the trace thickness as much as possible. Also, we have reinforced the PCB traces with a thick layer of solder to lower the trace resistance.When we want to  construct this circuit in handmade PCB , we must  reinforce the PCB traces with a thick layer of solder to lower the trace resistance and we need to attach a heatsink to the mosfet.To test the circuit I have used 12V power supply as input.I have attached a voltmeter and an ammeter to the output of the circuit which shows the output voltage and output current. From which we can easily calculate the output power for this circuit. 

(DEU)   Ein Aufwärtswandler ist ein Gleichstrom-Gleichstrom-Schaltwandler, der die Spannung erhöht und gleichzeitig ein konstantes Leistungsgleichgewicht aufrechterhält. Diese hocheffiziente Aufwärtswandlerschaltung basiert auf dem beliebten TL494-IC, der eine minimale Versorgungsspannung von 7 V und eine maximale Versorgungsspannung von 40 V hat. Da wir den IRF540N MOSFET als Schalter verwenden.Während der MOSFET eingeschaltet bleibt, beginnt die Spule sich aufzuladen, der Strom durch die Spule steigt ständig an, was in Form eines Magnetfeldes gespeichert wird.Wenn der MOSFET sich ausschaltet, beginnt das Magnetfeld zusammenzubrechen, und der Strom fließt in die entgegengesetzte Richtung des Ladevorgangsstroms und dies beginnt den Kondesator aufzuladen.Indem ich den Schalter (MOSFET) kontinuierlich ein- und ausschalten, habe ich  eine Ausgangsspannung erzeugt, die größer ist als die Eingangsspannung.Jetzt kann ich die Ausgangsspannung kontrollieren, indem ich die Ein- und Ausschaltzeit des Schalters steuere, und das ist es, was wir im Hauptkreis tun.Die Ausgabe des internen Referenzreglers mit 5V des TL494 ICs ist der REF-Pin, der Pin 14 des ICs. Der Referenzregler dient dazu, eine stabile Versorgung für die interne Schaltung wie den Pulslenk-Flip-Flop, den Oszillator, den Totzeitregelkomparator und den PWM-Komparator bereitzustellen.Die Frequenz des Oszillators kann durch Auswahl der Zeitkomponenten RT und CT eingestellt werden.Der Regler wird auch verwendet, um die Fehlerverstärker anzutreiben, die für die Steuerung des Ausgangs verantwortlich sind.Der Oszillator erzeugt und liefert eine Sägezahnwelle an den Totzeitregler und die PWM-Komparatoren für verschiedene Steuersignale, und die Oszillatorfrequenz entspricht nur für einseitige Anwendungen der Ausgangsfrequenz.Für Gegentaktschaltungen beträgt die Ausgangsfrequenz die Hälfte der Oszillatorfrequenz.Der IC verfügt über zwei interne Ausgangstransistoren, die in Open-Collector- und Open-Emitter-Konfigurationen sind, wodurch er maximal einen Strom von bis zu 200 mA liefern oder aufnehmen kann.Diese Schaltung kann einen maximalen Strom von 19 Ampere handhaben. Wenn wir eine große Last an den Ausgang dieses Boost-Konverter-Schaltkreises anschließen, wird eine enorme Menge an Strom durch die Leiterbahnen der Leiterplatte fließen, und es besteht die Gefahr, dass die Leiterbahnen durchbrennen.Um das Durchbrennen der Leiterbahnen zu verhindern, haben wir die Leiterbahndicke so weit wie möglich erhöht. Außerdem haben wir die Leiterbahnen der Leiterplatte mit einer dicken Schicht Lötzinn verstärkt, um den Leiterbahnwiderstand zu verringern.Wenn wir diesen Schaltkreis auf einer handgefertigten Leiterplatte herstellen möchten, müssen wir die Leiterbahnen der Leiterplatte mit einer dicken Schicht Lötzinn verstärken, um den Leiterbahnwiderstand zu verringern, und wir müssen einen Kühlkörper an den MOSFET anbringen. Wenn wir diesen Schaltkreis auf einer handgefertigten Leiterplatte herstellen möchten, müssen wir die Leiterbahnen der Leiterplatte mit einer dicken Schicht Lötzinn verstärken, um den Leiterbahnwiderstand zu verringern, und wir müssen einen Kühlkörper an den MOSFET anbringen.
