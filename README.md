# PMOS Low Drop out Regulator (LDO) using Two Stage CMOS Op Amp

- TSMC 180 nm technology is used and designed in LTspice. 
- Overall LDO regulator has an output regulated voltage of 2V and begins dropping out at 2.47V input voltage, the range of the dropout region is between 1.69V and 2.47V input voltage at a max load current of 400uA

<br />
<br />


## Two Stage CMOS Op Amp
- Two-Stage CMOS Op-Amp has DC Gain 78.8 dB, 3dB frequency 7.11 KHz, Unit gain bandwidth 66.21 MHz, Phase Margin 65.15 degree.
<br />

### AC Analysis
![image](https://user-images.githubusercontent.com/84563214/179395402-7b06262c-817c-4faa-a4a2-150df5db99ee.png)
![InkedScreenshot 2022-07-17 171827_1](https://user-images.githubusercontent.com/84563214/179396780-be8bfb06-c866-45db-9ead-337487b08830.jpg)
![InkedScreenshot 2022-07-17 171300_1](https://user-images.githubusercontent.com/84563214/179396653-03e87112-3a05-4d52-8d55-353b4874f85c.jpg)
![Screenshot 2022-07-17 170249_1](https://user-images.githubusercontent.com/84563214/179396329-63cd9ebe-215f-4f86-9c6e-7dc7b02b4dac.jpg)

<br />

### DC and Transient Analysis
![Screenshot 2022-07-17 174040](https://user-images.githubusercontent.com/84563214/179397671-e88c4306-a3b1-4523-881a-805ef0e1420f.jpg)
![image](https://user-images.githubusercontent.com/84563214/179397535-34c192e1-8936-41e5-a295-a6370e5fb8fa.png)

<br />

### Two Stage CMOS Op Amp Symbol
![image](https://user-images.githubusercontent.com/84563214/179400123-b9ad1acf-2304-42fe-b70d-b4ea71220a6d.png) 

<br />

### Testbench
![image](https://user-images.githubusercontent.com/84563214/179399936-203508ce-0631-47ac-b49c-493595519560.png)

<br />

