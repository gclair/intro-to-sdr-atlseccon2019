# AtlSecCon2019 - Introduction to Software Defined Radio

The items contained here are references to hardware and software referred to directly in the talk given at AtlSecCon2019.
Also included are other links to more comprehensive lists from i

## Basics

Wiki -> <https://en.wikipedia.org/wiki/Software-defined_radio>

## John Nevil Maskelyne

New Scientist - <https://www.newscientist.com/article/mg21228440-700-dot-dash-diss-the-gentleman-hackers-1903-lulz/>

Tom Scott YouTube Video - <https://youtu.be/sP2qqMegNKA>

Squirrel Take - <https://twitter.com/attritionorg/status/1119482041333055488>

## History

SpeakEasy - <https://en.wikipedia.org/wiki/Software-defined_radio#History>

## Radio Hardware

Not a comprehensive list by any means. Including only what I consider the 'beginner' more Canadian budget friendly links.

General overview and capabilities -> <https://www.rtl-sdr.com/roundup-software-defined-radios/>

### Receive Only

* RTL-SDR -> <https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/>
* NooElec -> <https://www.nooelec.com/store/sdr/sdr-bundles.html>
* SDRPlay -> <https://www.sdrplay.com/distis.php>
* AirSpy -> <https://airspy.com/>

### Receive and Transmit

HD - Half Duplex (Send OR Receive at a time)

FD - Full Duplex (Send AND Receive at the same time)

* HackRF (HD)  ->  <https://greatscottgadgets.com/hackrf/one/>
* LimeSDR (FD) -> <https://myriadrf.org/projects/limesdr/>
* ADALM Pluto (FD) -> <https://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html#eb-overview> ( Also available on DigiKey)

### Trandsmit only (Crazy awesome hacks)

* Raspberry Pi vers 2 and up (see Software Section)
* Osmo-Fl2k - USB 3.0 to VGA devices - <https://osmocom.org/projects/osmo-fl2k/wiki>

## Antennas

* Waifu Antenna - <https://twitter.com/IfNotPike/status/1044363908721532928>
* Antennas of all kinds -> <http://www.wa5vjb.com/>
* DIY Planar Disk Antenna -> <http://www.wa5vjb.com/references/PlanarDiskAntennas.pdf>
* Antenna Theory (Great Beginner Reference) -> <http://www.antenna-theory.com/>

## Software

### SDR Receiver

* GQRX -> <http://gqrx.dk/>
* SDR# (Windows) -> <https://airspy.com/download/>
* SDRAngel (Windows/Linux) -> <https://github.com/f4exb/sdrangel>
  
### Development

* GnuRadio - Install with PyBombs <https://github.com/gnuradio/pybombs/blob/master/README.md>
* PothosWare - <https://github.com/pothosware/PothosCore/wiki/GettingStarted#id5>
* LuaRadio - <http://luaradio.io/docs/installation.html#installing-from-source>
* ScratchRadio -> <https://www.rtl-sdr.com/sdr-programming-for-kids-limesdr-mini-with-scratch-on-a-raspberry-pi-3/>

### Applications/Development stories

* RPITX (Raspberry Pi Transmitter) -> <https://github.com/F5OEO/rpitx>
* SDRTrunk - Listen to Trunking radio-> <https://github.com/DSheirer/sdrtrunk> ; See Frequencies for Canada Below
* SDRSharp Plugins - <https://www.rtl-sdr.com/sdrsharp-plugins/>
* Airplane Tracking (dump1090) -> <https://github.com/antirez/dump1090> and <https://www.ab9il.net/software-defined-radio/dump1090-linux.html>
* Reversing Insulin Pump RF - <https://blog.usejournal.com/insulin-pumps-decapped-chips-and-software-defined-radios-1be50f121d05>
* RTL_433 -> <https://github.com/merbanan/rtl_433>
* RTL_433 -> <https://www.rtl-sdr.com/tag/rtl_433/>
* RTL_433 Can be used to sniff Temp Sensors, Vehicle Keyfobs, TPMS, certain remote controls and various other sensors. Can be extended with your own modules.

### Reversing

* Universal Radio Hacker (URH) - <https://github.com/jopohl/urh>

## Radio Astronomy

* Getting started with Amateur RadioAstronomy -> <https://www.rtl-sdr.com/wp-content/uploads/2016/05/Amateur-Radioastronomy.pdf>

### Websites

* RTL-SDR.Com -> <https://www.rtl-sdr.com/>
* RadioForEveryone -> <http://www.radioforeveryone.com/>
* Canadian Spectrum Allocation -> <https://www.ic.gc.ca/eic/site/smt-gst.nsf/vwapj/2014_Canadian_Radio_Spectrum_Chart.pdf/$file/2014_Canadian_Radio_Spectrum_Chart.pdf>
* Canadian Services Frequencies -> <https://www.radioreference.com/apps/db/?coid=2>
* FCC ID Lookup -> <http://fcc.io/>

### People to follow

* Twitter - ifNotPike <https://twitter.com/ifNotPike>; GitHub - <https://github.com/notpike/>
* Twitter - F5OEOEvariste <https://twitter.com/F5OEOEvariste>; Github - <https://github.com/F5OEO>
* Twitter - F4DAV <https://twitter.com/F4DAV>
* Twitter - CSete (gqrx creator) - <https://twitter.com/csete>
