### Prerequisite
Before performing this experiment, student must have knowledge about
1.   Working of a typical diode and LED
2.   Light spectrum
3.   Effect of various factors that affect the light output of an LED, e.g. temperature, wavelength, etc.

#### * What is a pulse rate?
Pulse is the rate at which human heart beats. Pulse is also commonly called Heart Rate, which is the number of times the heart beats each minute (bpm). As the heart pumps blood through human body, one can feel a pulse in the blood vessels close to the skin's surface, such as wrist, neck, or upper arm. Counting pulse rate is a simple way to find out how fast the heart is beating. However, the rhythm and strength of the heartbeat can also be noted, as well as whether the blood vessel feels hard or soft. Changes in human heart rate or rhythm, a weak pulse, or a hard blood vessel may be caused by heart disease or another problem. One can check the pulse, the first thing in the morning, just after waking up but before geting out of bed. This is called a resting pulse. The pulse rate can be measured by counting the beats in a set period of time (at least 15 to 20 seconds) and multiplying that number to get the number of beats per minute. Our pulse changes from minute to minute. It will be faster when one exercises, have a fever, or is under stress. It will be slower at resting condition.

### Importance of Pulse Measurement:

#### * Pulse is checked to:
* See how well the heart is working. In an emergency situation, the pulse rate can help to check whether the heart is pumping enough blood or not.
* Find the cause of symptoms, such as an irregular or rapid heartbeat (palpitations), dizziness, fainting, chest pain, or shortness of breath.
* Check for blood flow after an injury or when a blood vessel is blocked.
* Check on medicines or diseases that cause a slow heart rate. The doctors may ask to check the pulse every day for heart patients or persons undergoing medical tratments with certain medicines that can slower the heart rate.
* Check general health and fitness level. Checking the pulse rate at rest, during exercise, or immediately after vigorous exercise can give important information about overall fitness level.
 

### Measurement:

There are two approaches to developing a probe for pulse measurement. The first is transmittance, the second is reflectance. The difference is in the way the elements within the probe are positioned. A transmittance probe has a LED on one side and a photodiode (light detector) on the other. The tissue to be imaged (commonly a finger or an ear) is inserted between the two.

<center><img src="Images/image1.jpg" title="" /></center>

A reflectance probe has the LED and the photodiode on the same side. It must be placed over a point with underlying bone. Light is emitted by the LED, passes through tissue and blood vessels, reflects off bone, passes through the tissues again, and is then detected.
A significant amount of light will reflect off the skin in the reflectance setup, and, unlike in the transmittance setup, this light will be detected. Thus, reflectance probes have a high offset and a lower signal-to-noise ratio than the transmittance probes. Reflectance setups also require a significantly greater amount of light. Thus, either more LEDs or more photodiodes need to be used.
Transmittance probes are commonly placed on a finger or ear and are very convenient to attach and remove. Reflectance probes can be placed on the forehead or the sternum. Their advantage is that, regardless of the patient's size (infants to very large adults); the attachment site is always similar. Both, the transmittance and the reflectance probes are used clinically, though the transmittance probe is more common due to the simplicity of signal analysis and convenience of attachment.


### Photoplethysmograph:

The device used to measure the amount of blood in part of the body using light is commonly known as photo-plethysmograph. It measures the variation in amount of light passing through your finger caused by the pulsatile nature of blood flow. A light source is placed on one side of the finger, and a light sensitive transducer like LDR(Cadmium Sulfide (CdS) cell) or a photo diode or a phototransistor, on the other side. By monitoring variations in the output of the transducer an indication of blood flow in the finger is obtained. A simple block diagram of one such system is shown here.
<center><img src="Images/image2.jpg" title="" /></center>

A typical Pulse Oximeter uses the basic principle of a pair of small LEDs operating at two different wavelengths; one red LED with a wavelength of 660nm, the other, an infrared LED with a wavelength of 910nm. The LEDs are designed to be placed opposite a photodiode that detects the light from the LEDs. As the amount of blood in the capillaries depends on the actual blood pressure, which varies around the heart the heart pulse cycle, the heart rate can also be measured. The two wavelengths are chosen for the reason that deoxygenated haemoglobin has a higher absorption at around 660nm and at 910m oxygenated haemoglobin has the higher absorption. The oxygenated haemoglobin allows red light to transmit through and absorbs more infrared light while the deoxygenated haemoglobin allows infrared to transmit through and absorbs more red light. Usually a finger is placed between the source (LEDs) and the receiver (photodiode) acting as a translucent site with good blood flow. The photodiode produces current linearly proportional to the intensity of light striking it. A photodiode cannot distinguish between red and infrared light, but to accommodate this, the microprocessor system alternately turns each LED on and off. The pulse oximeter repeatedly samples the photodiode output while the red LED is on, while the infrared LED is on and while both are off. By sampling with both LED's off, the pulse oximeter is able to subtract any ambient light that is present.
 

### Design Considerations:

#### 1. Motion Artifacts:

The motion artifact is a major problem that is observed due to the patient's muscle movement. This induces false pulses that are similar to actual pulses. The false pulses when processed can produce incorrect results. This problem is particularly significant in patients that do not remain still during monitoring, and mainly in active infants. To reduce these artifacts digital signal processing is performed and the pulse average values over several seconds are taken, before they are displayed.

#### 2. Optical interference:

All pulse monitors are affected by bright external light sources. In order to achieve accurate measurements, potential sources of optical interference must be controlled. Optical interference occurs when bright light from an external source (ambient light) reaches the photodiode directly - without passing through the finger. Proper care is to be taken to avoid this.

#### 3. Effect of temperature:

Temperature affects the peak wavelength, spectral line-width, and output power of LEDs. In an LED based white light source, this can result in change in the color coordinates, color temperature, color rendering index, luminous efficiency. Efficiency of the source will change as the season (hot summer, cold winter) or even time of the day changes (warm day cold night). It is experimentally proved that the effect of shifts in wavelength of the LEDs on pulse monitor accuracy is negligible as the temperature increases from 0&deg;C to 50&deg;C.

#### 4. Effect of distance between source and sensor:

The distance between the LED and photodiode is one of the major design considerations when designing a reflectance pulse meter sensor. The ratio of AC to DC signal acquired by the photodiodes increases almost linearly with the distance between the LEDs and photodiodes. Greater separation between the optical elements means more tissue is able to absorb and reflect light. However, as the separation between the elements increases, the LED power required to produce a good signal increases almost exponentially. Thus, the ideal separation between the optical elements involves balancing signal quality and power consumption. However it is important not to place the photodiode too close to the LEDs. If the photodiode is placed too close to the LEDs, the photodiode will be saturated as a result of the large DC component obtained by the multiple scattering of the incident photons by the blood free layers of the skin.

### Advantages:
* Fast operation
* Easy to use
* Accurate readings
* Non-invasive method of measurement
* Reliable

### Limitations:

This instrument is used to measure number of pulses per minute. It cannot check for amount of blood flow i.e. sufficient or insufficient. Also it cannot give the account of haemoglobin present in blood.
