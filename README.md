# ado.github.io
<!DOCTYPE html>
<html lang="en-uk">
<!-- My third html page-->
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width"/>
<title>Current and Voltage Transformers for metering </title>
<img src="https://www.gfuvegroup.com/images/ct-&-pt/FU-60II/FU-60II(1)-big_1A_5A_OUTPUT_BUSBAR_TYPE_LV_CURRENT_TRANSFORMER.png"  width="200" height="200" id="TC"/>
<img src="https://www.ete.co.uk/wp-content/uploads/2016/10/WV-5.jpg" width="200" height="200"  alt="TT image" id="TT"/>
<link href="https://fonts.googleapis.com/css2?family=Gelasio:ital@1&family=Lisu+Bosa:ital@1&family=Old+Standard+TT:ital@1&display=swap" rel="stylesheet">
<link href="mystyle/mystyle.css" rel="stylesheet" />
</head>
<body>
<h1><strong>CT and VT for metering</strong></h1>
<h2><strong><div style="text-align:center">A. CURRENT TRANSFORMER:</div></strong></h2>
<p><strong><spam style="color:dark blue">Introduction</spam></strong></p>
<p>A current transformer is a device used to scale down large values of current (for example 100A) to smaller values of 1A or 5A, that can be easily manipulated for the purpose of system protections or metering.</p>
<p>In system protections, the current transformer plays a vital role as it measures current levels under fault conditions and channel these values to the relay for processing. Thus, the CT transformer serves as the eyes of the relay. Depending on the fault current levels, the relay then command the circuit breaker to trip, isolating the faulty portion of the installation from the rest.</p>
<p>In metering systems, the current transformer also plays an important role as it scales down currents of larger magnitudes to smaller magnitude of either 1A or 5A, and then channels this current value to the energy meter for measurements.The energy meter performs an energy calculation base on the current and voltage values it receives within a particular time frame.</p> 
<p>With the above analysis, we can conclude that there exist basically two classes of current transformers which are;
<ul>
<li>Measurement current transformer.</li>
<li>Protection current transformer.</li>
</ul></p>
<p> The above listed classes of current transformers often poses some confusions as they both literally plays the same principal role (scaling down larger values of currents to smaller values). Perhaps a measurement currrent transformer rated 100/5A will send out a 5A current through it secondary terminal when 100A current passes across its primary, likewise a protection current transformer. The only difference here depends on the loads connected at the receiving ends of the current transformers.The manner in which a relay responses to a signal from a current trasformer is completely different from that of an energy meter. Below we'll discuss some of the reasons why these transformers shouldn't be used for any purpose other from that which they're made for.</p>
<ol>
<li><strong><spam style="color:blue">Protection Current Transformers</spam></strong></li>
<p>
The purpose of a protection class current transformer is to measure current during fault condition, and gives input to the relay. Based on the current input, the relay then decides for the actuation of trip signal to a Circuit Breaker to isolate the healthy section of power system from the faulty section. This simply means that, the main requirement for a protection class CT is that it should measure the current accurately even when the primary current is of the order of 10 or 20 times of the rated current. This fact will be more evident if you look at the accuracy class of protection class CT. It is generally 5P20 or 5P30. This means that the CT will maintain its accuracy within ±5% when the current through it is 20 or 30 times its rated current. </p>
<p>
Another important design feature of a protection class CT is that its core does not get saturated even under the condition of a fault. This necessitates for the higher value of <strong>Knee Point Voltage</strong>. Therefore, such CTs can measure fault current accurately without getting its core saturated.</p>
<p>
Considering the above unique features, if the protection class CT is connected to a meter then under normal condition, the measurement of meter will not be accurate as desired for a revenue meter. Furthermore, under the condition of fault, the secondary current of the current transformer will be very high, around 20 to 30 times its rated current. This results in a flow of high value of current through the meter. Since meters are not designed for such a high value of current (10 to 20 times of rated current), this will damage the meter.
</p>
<li><strong><spam style="color:blue">Measurement Current Transformers</spam></strong></li>
<p>
A metering current transformer (CT) is characterized by its ability to measure current accurately (as per its accuracy class) when the primary current is in the range of 20% to 120% of the rated current. Since the secondary of metering CT is connected to various types of meters, an Instrument Safety Factor (the ratio of saturation currrent to the rated current of the CT) is also designated for metering CT. The main purpose of designating ISF is to protect meters connected in the secondary of metering CT during fault condition. Consider a measurement current transformer with an ISF of 2. This means that, if the CT primary current is more than 2 times the rated current, the CT core will saturate to limit the current through the meter connected to its secondary terminals. Any futher increase in primary current doesn't affect the secondary current. Thus, the meter is protected from high value of current under fault condition. 
</p>
<p>
Let us now assume that this metering CT secondary is connected to protection relay. Under fault condition, the CT core will saturate and hence limit its secondary current. Under such condition, the relay may not operate as the current channeled to it by the CT might still be lower than the threshold value. Thus, the power system stability will be compromised.
</p>
<p>
From the above discussion, it is clear that protection class CT should be used for protection purposes and metering CT should be used for metering purposes.</p>
</ol>
<p><strong><spam style="color:blue"><div style="text-align:center">Criteria for the selection of current transformers for measurement</div></spam></strong></p>
<p>In the selection of measurement CTs, the following criteria should be respected;</p>
<ol>
<li>Determine the load line current of the system and then use it to determins the primary current of the CT.The load current must be greater than 5A.</li>
<li>The primary nominal rating of the CT should be the closest value to 125% of the nominal current of the load. This is to enable the current transformer measure a current range of 20% to 120% of load nominal current.</li>
<li>The burden VA of the CT should be the closest value to 125% of the burden of the total load. An error burden of 0.5VA (burden of the energy meter) must be added to the overall burden of the load before selection of CTs.</li>
<li>CTs with double terminals labeled 1S1, 1S2 used for measurements and 2S1, 2S2, used for protections, are only applicable for medium voltage systems.</li>
<li>Current Transformers with single terminals are used for low voltage systems.</li>
<li>5A CT should be used for systems with distances of not more than 10m, while for distances above 10m, 1A CTs should be used. This is done in order to reduce the losses due to the resistance (which strongly depends on the length of the copper cables) of the copper cables leaving the secondary terminals of the CT to the energy meter.</li>
</ol>
<p><strong><spam style="color:blue">Sizing of current transformers for energy meters</spam></strong></p>
<p>The signal plate of an a.c generator has the following characteristics:</p>
<ul>
<li>Norminal voltage:400V</li>
<li>Operating frequency:50Hz</li>
<li>Installed power:648kVA</li>
<li>Power factor:0.8</li>
<li>Ambient temperature:40°C</li>
<li>Method of coupling:Y/Δ</li>
</ul>
<p> To select suitable CTs for the metering system of this generator, we proceed as follows:</p>
<ol>
<li>Firstly, we need to determine the maximum current that the generator can generate under normal working conditons. Here, we can use the installed capacity of the generator, or we could use the nominal power of the generator and include a safety factor of 125%. Below, we're using the installed capacity of the generator.</li>
<p><strong> I= S/(√3U)</strong></p>
<p>=(638×10^3)/(√3×400)</p>
<p><strong>I=921A</strong></p>
<li>Secondly, we determine the primary current of our current transformer. This is done by looking at the current transformer ratings and selecting the most closest one so as to improve measurement accuracy. So, we're going to use a current transformer with primary current of <strong>1000A.</strong></li>
<li>Now, we determine the secondary current of our current transformmer. To do that, first we need to know the distance that will exist between our energy meter and the CTs by proceeding as follows:</li>
<ul>
<li>Determine a suitable position to install the CTs (they could be installed on the power cable leaving the alternator directly in the generator's carbinate or in a separate carbinate housing the power cables.</li>
<li>We the position of the CT determined, identify a suitable position for the mounting of the energy meter and its accessories.</li>
<li>Measure the distance between the point where the CTs will be mounted and the point where the energy meter will be mounted and note down the value obtained.</li>
<li>If the measured distance above is greater than <strong>10m</strong>, then our secondary current should be 1A. And if the reverse is true, then our secondary current should be 5A.</li>
</ul>
<li>Assuming the measured distance is less than <strong>10m</strong>, then the selected current transformers for our generator are rated <strong>1000/5A.</strong></li>
<li>Again, we determing the burden (VA) and accuracy class (Cl) of our CTs while taking into consideration a meter burden of 0.5VA and burden of cables. Most low voltage measurement CTs have burdens ranging from 1,5VA right up to 15VA, and accuracy class ranging from 0,2 right up to 1. The burden and the class varries depending on the primary current of the CT, the material from which the core of the CT is made, the insulation of the CT, and perhaps the size of the CT. Here, we're going to choose a <strong>burden of 15VA and a class of 0,5</strong> for our CT.</li>
<li> Finally, the suitable CTs for our generator's metering system are rated <strong>1000/5A, 15VA-cl:0,5.</strong></li>
</ol>
<h3><strong><div style="text-align:center">B. VOLTAGE TRANSFORMER</div></strong></h3>
<p><strong><spam style="color:dark blue">Introduction</spam></strong></p>
<p>Potential transformers are designed to scale down larger values of voltage to smaller values that can be easily measured by meters or manipulated by relays. A potential transformer is a voltage step down, current step up transformer. Thus, under normal operation, the voltage accros the secondary terminals of the transformer is small while the current is very small leading to a small VA of range 50 – to – 200. Under fault conditions for example short circuit of secondary terminals, the current is extremly high due to a negligible voltage. For this reason, the output terminals of a potential transformer should never be shortcircuited. Whether protection or measurement potential transformer, they  both scale down voltage levels.</p>
<ol>
<li><strong><spam style="color:blue">Measurement Voltage transformer</spam></strong></li>
<p>A potential transformer for measurement is used to step-down voltages of higher magnetudes ( e.g 11kV) to smaller magnetudes (e.g 100V- to- 110V) for measurement by the energy meter. There are usually designed with accuracy classes of 0.2,0.5 with a burden of 30 and above.</p>
<p>
Similarily to a current transformer for measurement, potential transformer for measurement also have cores that easily get saturated under fault conditions. Thus if for any reason a measurement potential transformer is used for protection, under fault conditions, the core of the transformer will be saturated leading to a distorted output voltage with which the relay for protection might not operate as a result jeopardising the stability of the power system.</p>
<li><strong><spam style="color:blue">Protection Voltage transformer</spam></strong></li>
<p>Potential protection transformers on the otherhand have cores that do not easily get saturated even under fault conditions. There are often rated in the form P50 or 3P50 which means that a potential protection transformer is capable of maintaining an accuracy of ±1% or ±3%, when the voltage accross its primary winding is 50 times its rated value. Energy meters (e.g Itron SL7000) are designed to handle voltages of up to 480V between phases. Thus if this transformer is used for measurement, with such accuracy (1,3), the readings of the energy meter will not be accurate and under fault conditions, the meter will be damaged due to high voltage that it wasn’t designed to handle.</p>
</ol>
<p>For good results, <strong>protection voltage transformer</strong> should be used only for protection purposes while  <strong>measurement voltage transformer</strong> should be used only for measurement purposes.</p>
<p><strong>NB</strong></p>
<p>
Most potential transformers for meduim voltages have double secondary windings, one for protection and the other for measurement. Thus, during installation, care should be taken to ensure that the terminals are respected to avoid damages on meters or relay unreliability.</p>
<p><strong><spam style="color:blue"><div style="text-align:center">Sizing of voltage transformers for energy meters</div></spam></strong></p>
<p><strong><spam style="color:blue">Criteria for the selection of voltage transformers for measurement</spam></strong></p>
<p>In the selection of measurement VTs, the following criteria should be respected;</p>
<ol>
<li>Determine the load line voltage of the system and then use it to determins the primary voltage of the VT. The load voltage must be greater than 110V between phases.</li>
<li>The primary nominal rating of the VT should be the closest value to 125% of the nominal voltage of the load. This is to enable the voltage transformer measure a voltage range of 5% to 120% of load nominal voltage.</li>
<li>The burden VA and accuracy class of the VT should be the closest value to 120% of the burden of the total load. An error burden of <10VA per phase at Un (burden of the energy meter) must be added to the overall burden of the load before selection of VTs.</li>
<li> The type of connection to be applied (star or delta).</li>
<li> Where the VTs are to be installed(outdoor or indoor).</li>
<li>The operating frequency of the system. The operating frequency of the VT should be same at that of the system.</li>
</ol>
<p>Let's select VTs for our example above:</p>
<p> Since three phase energy meters operates on low voltages of up to 480V, we could just connect our energy meter directly to the generator's current carrying conductors and then use a surge protector, and fuses or a circuit breaker for its protection. On the contrary, we can still use LV measurement voltage metransformer and a circuit breaker for our meter.</p>
<h4><strong><div style="text-align:center">C. Some tips relating to metering system’s problem mitigations</div></strong></h4>
<p>In the course of eliminating metering system’s problems, the following useful points can be helpful:</p>
<ol>
<li><strong><spam style="color:blue">Current transformers</spam></strong></li>
<p>Control and inspect the current circuit of the metering system as follows:</p>
<ul>
<li>Conduct a visual inspection test on the CTs and ensure that they’re no burnt terminals,or loose contacts.</li>
<li>Verify and ensure that the CTs are properly installed and the directions of the terminals labeled P1, P2, S1 and S2 are respected.</li>
<li>Conduct a continuity test on the CTs secondary windings (this will give the value of the secondary winding resistance of each CT).</li>
<li>Conduct a continuity test on the cables linking the CTs with the energy meter.</li>
<li>Verify and ensure that the terminal labeled S2 of each CT is properly grounded.</li>
<li>Conduct a transformation ratio test on each CT using a Digital Transformer Ratiometer (DTR) while taking into account the following important parameters:</li>
<ol>
<li>The transformation ratio obtained which shouldn’t be different from the physical ratio of the CT by ±1%.</li>
<li>The deviation in % shouldn’t be greater than the accuracy class of the CT. A transformation ratio test with a 0.00% deviation is just perfect.</li>
<li>The excitation current which passes through the primary (H) winding of the CT under test with a negligible load current shouldn’t be greater 100mA.</li>
</ol>
<li>Check the distance between the meter and CTs to ensure it correspond to the distance required for secondary current of the CTs. That is, 5A for distance below 10m and 1A for distance above 10m.</li>
<li>Verify and ensure that the meter and other units connected to the CTs are in series with each other and not in parallel. This is done in order to avoid current division which will greatly distort the meter readings.</li>
<li>Verify and ensure that the nominal current of the load to which the CTs are installed is at less than 125% of primary rating of the CTs while taking into account a burden of 0.5VA of meter(incase of Itron SL7000 meter).</li>
<li>Check the CTs accuracy classes to ensure that the CTs installed are metering class (0.2, 0.5, 1) CTs and not protection class CTs. </li>
<li>For combined measurement and protection CTs, check to ensure that the terminals are properly cabled. Most often, the terminals labeled 1S1, 1S2 are used for metering while 2S1, 2S2 are for protection.</li>
<li>Check the C.S.A of the copper cables linking the CTs with the energy meter to ensure that they correspond to the cable size(6mm^2) required for the connection of current circuits of energy meters.</li>
</ul>
<li><strong><spam style="color:blue">Voltage transformers</spam></strong></li>
<p>Control and inspect the voltage circuit of the metering system as follows:</p>
<ul>
<li>Conduct a visual inspection test on the VTs and ensure that they’re no burnt terminals,or loose contacts.</li>
<li>Verify and ensure that the VTs are properly installed and the directions of the terminals labeled P1, P2, S1 and S2 are respected.</li>
<li>Conduct a continuity test on the VTs secondary windings (this will give the value of the secondary winding resistance of each VT).</li>
<li>Conduct a continuity test on the cables linking the VTs with the protective fuses or circuit breaker protecting the voltage circuit of the meter.</li>
<li>Verify and ensure that the terminals labeled P2 and S2 of each VT are properly grounded.</li>
<li>Conduct a turns ratio test on each VT using a Digital Transformer Ratiometer (DTR) while taking into account the following important parameters:</li>
<ol>
<li>The turn ratio obtained which shouldn’t be different from the physical ratio of the VT by ±1%.</li>
<li>The deviation in % shouldn’t be greater than the accuracy class of the VT. A turn ratio test with a 0.00% deviation is just perfect.</li>
<li>The excitation current which passes through the primary winding terminals (P1 and P2) of the VT under test with a negligible load current shouldn’t be greater 100mA.</li>
</ol>
<li>Measure the insulation resistance of each VT using an appropriate measuring instrument (e.g Megohmmeter C.A 6545) between the following terminals:</li>
<ol>
<li>The primary terminal (P1) and the secondary terminal (S1).</li>
<li>The primary terminal (P1) and the ground terminal.</li>
<li>The secondary terminal (S1) and the ground terminal.</li>
</ol>
<p><strong>NB: 1kV=1MΩ</strong></p>
<li>Control and inspect the protective device of the voltage circuit. In case of protective fuses, measure the continuity of the fuses using a multimeter. While for a protective circuit breaker, close the breaker and test its continuity using a multimeter.Also, verfy the rating of the fuses or circuit breaker.</li>
<li>Control and inspect the copper cables leaving the protective device to the meter to ensure they are no cuts on any of the cables.</li>
</ul>
<li><strong><spam style="color:blue">Energy meter (Itron SL7000)</spam></strong></li>
<p>Control and inspect the voltage and current circuits of the metering system as follows:</p>
<ul>
<li>Conduct a visual inspection test on the meter and ensure that they’re no burnt terminals,or loose contacts.</li>
<li>Verify if the manner in which the meter terminals are connected to the voltage and current circuits correspond to the single-line daigram found behind the terminal plastic cover.</li>
<li>Verify and analyse the behavour of the following annunciator icon indicators found on the LCD display:</li>
<ol>
<li>The lithium battery icon which blinks when the measured battery voltage is lower than the programmed threshold, when the battery is not properly connected, when the cumulative power failure duration exceeds three years or when the battery operating duration exceed ten years. If any of the above points apart from poor connection is true, then you have to replace the battery and reconfigure its capacity threshold and expiry date in the meter using the approved software.</li>
<li>The alarm icon which blinks when the meter has detected an active alarm condition. Use the <strong>ACE PILOT</strong> software to analyse the alarm status and then erase it if possible.</li>
<li>The excess demand icon which indicates when the calculated demand value is higher than the programmed threshold. Modify the threshold value of the meter or reduce the loads on the meter.</li>
<li> The phase sequence icons (123), where each of the three icons represent a connected phase.</li>
<ul>
<li>If a phase is missing, the associated icon is not lit.</li>
<li> If voltage sags or swells occur on a phase, the associated icon will blink.</li>
</ul>
<p>Control the cable of the missing phase and ensure that its continuity is good.</p>
<li>The quadrant with four individual arrow icons indicating the direction and type of the
energy currently measured by the meter.</li>
<ul>
<li>Active and Reactive.</li>
<li>Import and Export.</li>
</ul>
<p>If the incoming supply phase-sequence is incorrect (e.g. 1,3,2) these
icons flash. Control and inspect the phase-sequence of the meter.</p>
<li> Verify the nine digits error code of the energy meter knowing that under normal operation, the nine digits are all zeros. If any of the digit changes from zero to a different digit or letter, use the <strong>ACE PILOT</strong> software to analyse the error status and then erase its corresponding alarm if possible.</li> 
</ol>
<li>Finally, perform an error test on the energy meter using a <strong>moving test meter MT680s (compteur etalon)</strong> while taking into account the error of the MT680s meter (0.1%), energy meter (0.5% for SL7000 meters), that of the CTs and PTs if used, cables and other miscellaneous. Thus in overall, an error test of not more than 1.5% is accepted. If the result of the error test yields above 1.5%, then the energy meter has an internal problem and should be replaced provided the instrumentation circuitries (CTs and PTs) are still in good shape.</li>
<p>In conclusion, metering system's components should be sized and installed by well trained technicians. Inspections and diagnosis of the metering components should be carried out regularly by qualified technicians.</p>
</ul>
</ol>
<p><strong><spam style="color:purple">By Desmond Zeh</spam></strong></p>
<h5>Hello guys!</h5>
<button>Change User</button>
<script src="myscript/mymain.js"></script>
</body>
</html>
