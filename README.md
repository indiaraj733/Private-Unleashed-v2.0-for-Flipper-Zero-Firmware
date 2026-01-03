# Private-Unleashed-v2.0-for-Flipper-Zero-Firmware

Private Unleashed v2.0 for Flipper Zero Firmware

  no password
  
  keeloq_mfcodes this one should be in the sub ghz folder and in the assets folder
  setting_user this one should be in the sub ghz folder and in the assets folder
  key.fz this should be on the front of the sd card
  this one should be downloaded at the end on Flipper Zero it is firmware.dfu
Rolling Code Exploitation

This assumes you are already running unleashed firmware 080+ for the new one unleashed firmware 084

I highly suggest you use the flipper build tool to flash to the updated firmware, however feel free to use qflipper if you find you're not savvy enough.

**** Additional Notes ***

Modulation: Most of Kia, Hyundai, Mitsubishi and Suzuki factory systems are using FM476 (in rare cases older models before 2014 are using AM650). Volkswagen, Skoda, Seat, Audi, Ford ASK, Subaru & FCA are only AM650, additional alarms in most cases are also AM650, some of aftermarket alarms like Scher-Khan could be FM238 or FM476. Barriers all are AM650 (there are few exceptions with FM476/custom FSK, in development). For PSA FM need to use custom presets (in development).

Usage of captured signal: it's better to save a signal first instead of instantly emulating it from the receiver info menu. Emulation from RX is also working with counter increment, but only the received command. In order to use all buttons (lock / unlock / trunk / panic / etc. – in case of vehicles; and additional objects – in case of multi-button garage remotes) and guarantee proper emulation - use signal from already saved! Always hold the emulation button (center or arrow) at least for 2 seconds (for some protocols need to hold even longer) to ensure all data passed over-the-air. Center button is always a received command, arrows are other commands. For example: if we received close / lock command then our center button is always close / lock, arrow up is open / unlock, arrow down is trunk.

How to copy FAAC SLH / BFT: this kind of remote requires seed and counter values ​​calculation. In order to create working clones need to read from each button of each remote at least 2 consecutive presses without gaps and send me screenshots from receiver info (where is all details shown: key, fix, hop, etc.). Then I can calculate all data for Sub-GHz Add Manually.

*** 1 December 2025 ***

Added support for old Audi models; Improved CC1101 drivers, HAL and Sub-GHz worker module - no more freezes / crashes with custom high-speed presets, faster PSA brute-force; New super-easy and fast update procedure via just 1 .tgz file in automatic mode (saves time and MCU write resource); Improved stability of private protocols work; Added updates from OFW and public Unleashed; *** COMING SOON Under current development ***

New Ford, Land Rover, Jaguar, Lincoln, Mercury FSK & Keyless-Go up to 2023 BMW and Mini Cooper Honda Mazda *** As of November 2025 Current Supported Models ***

✅ KIA MOTORS (UP TO 2025 MODELS) | Forte | Magentis | Sedona | | Rio | Mohave | Sorento | | Rio X-Line | Optima | Soul | | Carnival | Picanto | Sportage | | Cerato | Ceed | Stonic | | Cerato Coupe | Ceed JD | Venga | | Bongo |

✅ HYUNDAI (UP TO 2025 MODELS) | Accent | HB20 | i35 | Solaris | | Avante | H1 | i40 | Sonata | | Crete | i10 | iMax | Starex | | Elantra | i20 | iLoad | The suit | | Getz | i25 | iX20 | Tucson | | KRX 2025 | i30 | iX25 | Veloster | | Mistra | i35 | iX30 | Verna | | Sante Fe | iX35 | iX40 | | iX45 |

✅ SUBARU | B9 Tribeca | Legacy | XV | | Forester | Outback | | Impreza |

✅ Land Rover (UP TO 2016 MODELS)

✅ FIAT (UP TO 2012 MODELS) | Cronos | Double | | Ducato |

✅ LANCIA | Delta | Momo | | Ypsilon | other FCA |

✅ FORD (UP TO 2016 MODELS) | B-Max | Flex | Rank | Transit | | C-Max | F150–F450 | S-Max | Transit Connect / Custom | | Edge | Fusion | Taurus | Tourneo Connect / Custom | | Escape | Galaxy | Transit | Grand | | Escort | Kuga | Transit Custom | Fiesta | | Expedition | Mondeo | Explorer | Focus | | EconoLine | Mondeo MK4 | Mustang |

✅Lincoln (UP TO 2016 MODELS)

✅ MITSUBISHI | ASX | Pajero Sport | L200 | | Colt | Gallant | Pajero | | Grandis |

✅ Mercury (UP TO 2016 MODELS)

✅ SUZUKI (UP TO 2015 MODELS) | Grand Vitara | SX-4 | | Swift |

✅ PEUGEOT | 2008 — 2012–2016 | 3008 — 2009–2016 | Partner — 2012–2017 | | 2008 — 2013–2016 | 3008 — 2016+ | Picasso — 2007 | | 207 — 2006–2016 | 4008 | Quatre | | 208 — 2012–2016 | 407 — 2004–2011 | RCZ — 2009–2016 | | 307 — 2005–2016 | 408 — 2010–2016 | Triumph | | 308 — 2007–2016+ | 408-508 / 301 — 2014–2016 | Xsara | | 5008 — 2009–2016 | 508 — 2011–2016 | Elysée | | DS5 | Expert — 2007 | Jumpy — 2006–2016 | | Partner — 2009–2016 |

✅ THE CITROEN (UP TO 2018 MODELS) | 4A folding system | C4 Cactus — 2014–2016 | Jumpy — 2006–2016 | | Berlingo — 2013–2018 | C4 Coupe — 2004–2010 | Partner 2009–2016 | | C2 — 2005+ | C4 Grand Picasso — 2006–2016 | Picasso — 2007 | | C3 — 2006–2016 | C4 Grand Picasso — 2007–2013 | Quatre – 2015 | | C3XR — 2013– | C4L — 2013 | Triumph | | C4 — 2006–2016 | C5 — 2007–2018 | Xsara | | C8 — 2007–2016 | CTR3 — 2008 | Elysée — 2013 | | DS4 — 2010–2016 |

✅ Jaguar (UP TO 2016 MODELS)

✅ VOLKSWAGEN (UP TO 2024 MODELS) | Amarok | Golf 4, 5, 5+ | LT | Suran | | Beetle | Jetta | Lupo | Tiguan | | Bora | Multivan | Passat B5–CC | Touran | | Caddy | Polo | Scirocco | Transp
