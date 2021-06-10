# Troubleshooting
## FM Bugger Circuit
Is your circuit not working? Don't worry just few checks can make it ready.<br>
Try checking in the sequence <br>
*Capturing sound and removing noise -> Frequency Modulation -> Transmission* <br>
Because problem in any one of these can cause in breakdown of circuit

### Checking Capturing Sound and removing noise
Try checking all your connection in circuit whether all parts are connected properly or not. 
If connected and can't hear, then it might be problem of microphone.<br>
Try checking mic using circuit given below

![MicrophoneSpeakerCircuit](https://user-images.githubusercontent.com/85283364/121453029-15b3b480-c9be-11eb-9262-da5e0b845c4c.png)

If Microphone is working then it might be any other problem which will be noticed in later steps

If you find noise isn't properly removed, then problem might be in these capacitors.
Check whether connections are made proper and if possible test with other possible capacitor values.

### Checking Frequency Modulation 
As you have checked the microphone but still can't hear, then there may be problem in Frequency Modulation<br>
Try checking whether oscillator circuit/Tank ciruit working or not<br>
Try checking inductor as it should be made carefully

### Checking Transmission
Still not hearing dont worry. <br>
Check your antenna whether it is connected prpoerly or not.<br>
Try changing value of capacitor in tank circuit so that frequency may change and fall in required range (88-108).<br>
Be patient while finding correct frequency in the FM Radio (used as receiver) 
If possible try <br>
<img src="https://latex.codecogs.com/gif.latex?f&space;=&space;\frac{1}{2\pi&space;\sqrt{LC}}" title="f = \frac{1}{2\pi \sqrt{LC}}" /><br>
and find approximate value of frequency




## Security Access using RFID reader
Isn't your device not working? Don't panic! Get ready to figure it out.<br>
Try checking in the sequence <br>
*Scanning RFID -> Microcontroller -> Execution* <br>
Because problem in any one of these can cause Arduino to not to respond

### Scanning RFID
Isn't your card not reading? Try finding any loose connections. If no,
Try checking your tag and location of chip and coil in your tag. A cut can make it non-usable.  T_T <br>
If its fine, try checking reader whether it is responding or not. 
Check whether it too hot as toasting a chip may occur

### Micro Controller
Still your card isn't getting read?<br>
Try checking Pinouts and code once, may there be a mistake in it. 
Check your code thoroughly may be small mistake can make it fatal.

But your problem isn't it, but its saying access denied for wrong card. Don't worry.<br>
Try scanning your card once again. Try doing read operation and find UID of your card. Make sure that UID of your card and UID in the code are same. 
Try checking your code once more.

But your device is accessing for any card? <br>
Try checking your code, ther may be a mistake in conditions or loops.

### Execution
Everything is working fine but no change is observed.<br>
Try checking connections to servo/any security device, Check whether device is in working condition or not.
Try run an opening code without any need of access device. 
