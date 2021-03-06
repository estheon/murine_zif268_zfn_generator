The majority of scientific literature on zinc finger nucleases utilize the mouse version of the Zif268 (EGR-1) protein as a scaffold. Since it is widely assumed that the zinc finger nuclease used is murine Zif268, most articles omit the engineered Zif268 protein sequence in its entirety, and instead only list out the modules used.  
   
This algorithm aims to *put together* the modules into the murine Zif268 protein to output the full Zif268 protein sequence. The raw Zif268 sequence is listed here as found in GenBank:
>sp|P08046|EGR1_MOUSE Early growth response protein 1 OS=Mus musculus OX=10090 GN=Egr1 PE=1 SV=2
MAAAKAEMQLMSPLQISDPFGSFPHSPTMDNYPKLEEMMLLSNGAPQFLGAAGTPEGSGGNSSSSTSSGGGGGGGSNSGSSAFNPQGEPSEQPYEHLTTESFSDIALNNEKAMVETSYPSQTTRLPPITYTGRFSLEPAPNSGNTLWPEPLFSLVSGLVSMTNPPTSSSSAPSPAASSSSSASQSPPLSCAVPSNDSSPIYSAAPTFPTPNTDIFPEPQSQAFPGSAGTALQYPPPAYPATKGGFQVPMIPDYLFPQQQGDLSLGTPDQKPFQGLENRTQQPSLTPLSTIKAFATQSGSQDLKALNTTYQSQLIKPSRMRKYPNRPSKTPPHERPYACPVESCDRRFSRSDELTRHIRIHTGQKPFQCRICMRNFSRSDHLTTHIRTHTGEKPFACDICGRKFARSDERKRHTKIHLRQKDKKADKSVVASPAASSLSSYPSPVATSYPSPATTSFPSPVPTSYSSPGSSTYPSPAHSGFPSPSVATTFASVPPAFPTQVSSFPSAGVSSSFSTSTGLSDMTATFSPRTIEIC   
   
`murineZif268.docx` shows where the modules are located within the sequence.   
`zfn_generator.ipynb` contains the algorithm that outputs the full protein sequence.
