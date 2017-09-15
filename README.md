# pedal_pi
An upload of the effects code for the awesome electrosmash pedal-pi board (https://www.electrosmash.com/pedal-pi) to make headless installation easier...
You'll need BCM2835 installed (http://www.airspayce.com/mikem/bcm2835/).
To compile each effect, run gcc -o example -l rt example.c -l bcm2835.
