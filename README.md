# PCI7200-variousFrontends
Hardware and software of DIY analog frontends for PCI-7200 DAQ card, meant to be useful with long-term distros on any PC with available 32-bit PCI slot(s)

First, I'll need to complete the whole unit (my own will be based on Dell Optiplex 7050 motherboard with few spare parts), then test it with PCI-7200 DAQ cards and long-term distro (likely Debian stable) with Comedilib and GTKview.
Then, I'll try designing simple digital, multipurpose backend PCBs, first binary, then balanced **ternary** – the latter is rare among DAQs but quite achievable, which seems to have potential.
If both work, I'm *finally* gonna start designing analog frontends hardware and software (host + firmaware), with each of frontend classes named after favorite fictional girls:
 * Ϫⲉⲓⲇ (Jade): various ADC frontends; 
 * Ⲙⲁϧⲉⲗⲓⲁⲛ (Machlian): various DAC frontends;
 * Ⲗⲓⲥⲁ (Lisa): power-electronics and electrotechnics oriented frontend;
 * Ⲣⲓⲁⲥ (Rias): chirp-based spectrum analyzer frontend;

Don't be surprised with „waifu” naming scheme, if I'm eccentric enough to try adotping old DAQ cards to DIY-ish DAQ system with **vast** analog capabilites (the last part being TRULY hard).

OH, IF IT'S NOT ALREADY CLEAR: this is modular setup, requiring awareness from any potential user in order **to not harm themselves**. I assume you already are one, and MIT license doesn't protect you from any property/owner/user damage. Also, I hope documentation of everything here will be clear enough.
