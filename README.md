# Honeypot-PenTBox-
Manual And Automated Honeypot Configuration on Kali Linux

## Setting Up and Using a Honeypot with PenTBox

### Introduction
PenTBox is a versatile security toolkit designed to streamline penetration testing. It is programmed in Ruby and compatible with GNU/Linux, Windows, macOS, and any system where Ruby is installed. This guide will walk you through the steps to install and configure a honeypot using PenTBox.

### Fast Auto Honeypot Installation (Port 80)

1. **Download PenTBox:**
   - Open your terminal.
   - Clone the PenTBox repository by running:
     ```bash
     git clone https://github.com/technicaldada/pentbox
     ```

2. **Extract Files:**
   - Navigate to the PenTBox directory:
     ```bash
     cd pentbox
     ```
     
3. **Execute PenTBox:**
   - Start PenTBox by running:
     ```bash
     ./pentbox.rb
     ```
     
4. **Configure the Honeypot:**
   - Choose option `2` for "Network Tools".
   - Choose option `3` for "Honeypot".
   - Choose option `1` for "Fast Auto Configuration".

5. **Verify Connection:**
   - Ping your Kali Linux IP address from another machine to ensure they can communicate:
     ```bash
     ping <Kali_IP_Address>
     ```

6. **Access Honeypot:**
   - Open a web browser on another machine.
   - Enter the server's IP address (your Kali Linux IP address) in the address bar.

7. **Monitor Logs:**
   - Enjoy viewing the honeypot logs generated by PenTBox.
![3](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/0ac65391-5b5c-4e40-95ef-c37942c9c996)
![4](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/ebef26bf-a683-483c-8c13-2b8613bd5a25)
![5](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/681d9ec1-1feb-48f9-b3ab-da6785ece4f1)
![6](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/6bc13d72-10d9-4254-8b32-550cbbdf1e53)
![7](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/9c48e347-bf85-4d9c-bf48-01f110fc1adc)
![8](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/ae98a73f-5671-44a0-9d69-8288f38ee6c1)
![9](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/c8d178f8-5c6d-4602-9828-c7e5eec89710)
![10](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/2352f912-f906-442e-9ed0-61982a94c64e)



### Manual Honeypot Configuration (Port 23 Example)

1. **Run PenTBox:**
   - Execute PenTBox by running:
     ```bash
     ./pentbox.rb
     ```

2. **Configure the Honeypot:**
   - Choose option `2` for "Network Tools".
   - Choose option `3` for "Honeypot".
   - Choose option `2` for "Manual Configuration".
   - Fill in the configuration details as desired (e.g., port 23).

3. **Verify Connection:**
   - Attempt to make a Telnet connection to the honeypot from another machine.

4. **Monitor Logs:**
   - Check the logs on your Kali Linux machine to see the activity.

![1](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/c5f56f37-f845-4350-a388-53b40c1953bb)
![2](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/95f2f05d-3e46-4423-b8e9-777bff077cec)
![3](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/ebc0401b-450c-4d8d-aa27-915bb3fba05e)
![4](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/31b20aaf-cab5-48b3-b43f-06386069854a)
![5](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/05c0d9bd-cc4b-4314-bb55-6386789daf7d)
![6](https://github.com/celik-hayri/Honeypot-PenTBox-/assets/173578001/474acc57-7fb3-493a-bbc4-146221bc7640)




### Additional Information
For more detailed instructions and usage of PenTBox, visit the [PenTBox Documentation](https://www.kalilinux.in/2019/05/honeypot.html).
