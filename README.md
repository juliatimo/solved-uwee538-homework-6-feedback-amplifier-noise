Download Link: https://assignmentchef.com/product/solved-uwee538-homework-6-feedback-amplifier-noise
<br>
<em>R<sub>f</sub></em> = 10k and <em>R<sub>i</sub></em> = 1k. The opamp has a gain-bandwidth product (<em>f<sub>T</sub></em>) of 10MHz, input voltage noise density (<em>e<sub>n</sub></em>) of 10nV/Hz, and input current noise density of 1pA/Hz.

<ol>

 <li> Determine the <em>input-referred</em> noise voltage density (in V/Hz) of the amplifier, including contributions from all noise sources.</li>

 <li>Determine the equivalent noise bandwidth (<em>f<sub>ENB</sub></em>) and input-referred RMS noise voltage.</li>

 <li> Check your answers to a) and b) by simulating the circuit in Ltspice using the UniversalOpamp2. Be sure to set the noise voltage density ‘en’ and current noise density ‘in’ to the appropriate values. To verify the RMS noise voltage, you can ctrl-click on the plot title (or export the data to MATLAB/Python).</li>

</ol>

<h1>Problem 2: Opamp noise characterization</h1>

<strong>Figure 2. Opamp noise testbench </strong>

Characterize the noise performance of the AD8691 and ADA4898 opamps. For the AD8691, use a single supply of 5V. For the ADA4898, use a split supply of +/-5V. Be sure to observe any test conditions provided in the datasheet(s) when running your tests.

<ol>

 <li> Using the unity-gain feedback configuration shown, verify the 3dB bandwidth of each amplifier. Use this to calculate their equivalent noise bandwidths.</li>

 <li> Setting <em>R<sub>s</sub></em> = 0, perform noise simulations to verify the input voltage noise density of each opamp at the frequencies specified in their datasheets.</li>

 <li> For the ADA4898 only, set <em>R<sub>s</sub></em> to a value large enough such that the opamp’s current noise density should be 10 times that of its voltage noise. Verify the current noise at the output of the amplifier using the relationship <em>e<sub>n,out</sub></em> = <em>i<sub>n</sub>R<sub>s</sub></em>. Be sure to use the term ‘noiseless’ after the resistor value to ensure its noise doesn’t affect the simulation results.</li>

 <li>Calculate the expected output RMS output noise in a 1MHz bandwidth for each amplifier and perform a noise simulation to verify. Note/explain any discrepancies.</li>

</ol>


