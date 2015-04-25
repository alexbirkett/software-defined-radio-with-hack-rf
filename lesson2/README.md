#Lesson 2

## Question
Does the flowgraph behave differently if you remove the throttle block? (Connect the source directly to the sink.)

## Answer
The running flowgraph appears to use 100% of CPU on one of the cores


## Question
Does the FFT sink correctly indicate the frequency produced by the source? What if the source and sink have different sample rates configured?

## Answer
The FFT sink does appear to indicate the frequency produced by the source if the same sample rate is configured on both the source and FFT. If the FFT's sample rate is lower than the source the indicated frequency appears to drop, for example, if the the sample rate of the FFT is set to 15kHz, the indicated frequency is approximately 500Hz.

## Question
What happens if you configure the signal source with various frequencies between 0 and 16k?

## Answer
Frequencies between 0-15kHz are displayed as expected (between 0-15kHz on the FFT). A source frequency of 16kHz is displayed as -16kHz on the FFT.

## Question
What if you specify frequencies greater than 16k? Any idea why?

## Answer
17kHz is displayed as -15kHz, 18kHz as -14kHz etc. There are not enough samples to represent the frequency.

## Question
What if you specify negative frequencies? Mathematically, is there a difference between cos(x) and cos(-x)?

## Answer
If the source is configured to -18 kHz it's displayed on the FFT as 14kHz. cos(x) and cos(-x) appear to be mathematically similar.

## Question
Does the plot indicate the presence of any frequencies other than the one produced by the source? (Hint: Use Autoscale or increase dB/Div.) What is the apparent amplitude of the noise? Why is there any noise at all?

## Answer
Yes, there appears to be noise at -160db -200db. The noise exists because the sampling is discrete. The frequency shown on the FFT is an approximation.

## Question
Try multiple signal sources added together. Are there any other interesting operations you could try?
Try various waveforms (instead of cosine) in the signal source.

Adding two sources of the same frequency increases the amplitude.
