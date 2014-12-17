PH-metre
========
- L'électrode pH est une batterie simple. 
- Sa tension est proportionnelle à la concentration d'ion hydrogène entourant l'électrode et proportionnelle au logarithme de la concentration d'ion hydrogène  

- caractéristiques d'une electrode ideal : 
	
		* 0 Volts avec pH neutre (=7.0)
		* >0 (Positive)  dans le cas d'un acide ( PH<7 )
		* <0 (negative)  dans le cas d'un base ( PH<7 )
		* gamme pH est 0 à 14, l'acide fort à la base forte.
		* variation -59.16 millivolts/pH à température ambiante ()
		"poteltiel d'Nernst"). Notez que ceci est une pente négative. 
		*à pleine échelle, sa gamme est  est ±0.414 volts à 25 degC
			-- evolution PH [-7 *****> 0 <******+7]
			-- potentiel V  [-7*0,05916**7*0,05916]

		*Le coefficient de température du potentiel Nerst est β = -0.001984 mV par °C. Cela fait la pente -54.2 mv/pH à 0 degrés Celsius et -74.04 millivolts par unité pH à 100 degrés Celsius.

		* Equation avec variation de température : 
		y(v) = a/ph + b  
		ore a 25°c , a = 0,414/7 et b = 0.414 donc 

		Y(v,Θ) = ( a - β*ΔΘ/7 )*PH + 0,414  

		* le electrodes PH présentent une resistance de résistance de 10 MO et 1000 MO => besoin de faible courant et besoin d'une très grande resistance en entrée (1 nanoAmp par 100 MOHMS égale 0.1 volts. C'est déjà équivalent à presque 2 unités pH). donc les AOP doivent avoir un courant Ibias faible . 

		*Me basant sur un montage a base d'un TL081, J'ai remplacé le TL081 par un TL062 présentant un courant de polarisation de 30 pico ampere .document modele (simulation protéus)
	

Ressources: 

	* http://bernard.pironin.pagesperso-orange.fr/index.htm

	*http://marsal.univ-tln.fr/pHdos/pHdos9/Les_electrodes_de_pH-metrie.htm

	*http://www.ph-meter.info/pH-meter-construction

	*http://www.simplecircuitdiagram.com/2009/05/20/simple-ph-meter-circuit-a-low-cost-adapter-for-your-digital-voltmeter/



PH-metre
