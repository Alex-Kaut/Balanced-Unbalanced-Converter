# Balanced audio to unbalanced converter
This project was inspired by the "BEHRINGER POWERPLAY P2" we needed a bunch of similar devices, so I started developing a circuit and a board. We needed: devices with balanced input and unbalanced output to headphones with unipolar power +12 or +18 volts

# Original chematics 
## Converter 
![BalancedToUnbalancedConverter](https://github.com/Alex-Kaut/Balanced-Unbalanced-Converter/assets/86695572/170c79aa-a399-4a18-a091-4005080ecf56)

This is converter schematic from Behringer P1 - it is using bipolar power, unnamed capasitors must be 22pF or similar. Diodes play a protective role. More information can be found on the forum at this link, it is advisable to register to have full access to all materials https://www.talkbass.com/threads/modded-behringer-powerplay-iem-build-report-diy.1246541/page-2

## Headphones AMP 

![StereoHeadphoneAmplifier](https://github.com/Alex-Kaut/Balanced-Unbalanced-Converter/assets/86695572/0fcb0dab-63ab-41bb-a73a-92990de7aa17)

This is an inverting headphone amplifier, it's enough to rock the headphones. The converter circuit is also inverting, so the output will be the original signal

