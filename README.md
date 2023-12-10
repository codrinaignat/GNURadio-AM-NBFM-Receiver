# GNURadio-AM-NBFM-Receiver

This application was part of my dissertation thesis and it uses the RTL-SDR device, a cheap, popular and versatile SDR device, although in the .grc file I used OSMOCOM source, which allows multiple types of SDR devices to be used, such as: RTL2832U based devices, Great Scott's HackRF, AirSpy Wideband receiver, SDRPlay RSP devices, Ettus USRP, etc. 

Application features:
- select the type of receiver you want to use (AM/NBFM);
- volume adjust;
- center frequency set;
- device gain set;
- displayed frequency bandwidth selection;
- received spectrum display and the corresponding spectrogram;
- frequency step set for the center frequency;
- signal suppression set by the parameter squelch adjustment.

What you need in order to use this application: RTL-SDR device, GNU Radio software installed. 
If you want to find out more information about the RTL-SDR device, you can take a look here: https://usermanual.wiki/Document/The20Hobbyists20Guide20To20RTLSDR2020Carl20Laufer.399886352/view

Full documentation of the project in Romanian:

https://electronicaplicata.wordpress.com/2023/12/03/software-defined-radio-sdr-pentru-incepatori-aplicatii-si-explicatii/
