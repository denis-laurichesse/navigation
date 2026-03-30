1) Get the source from the RTKLIB github repository (rtklib_2.4.3_b34_ppp branch)
2) Compile app rnx2rtkp (and its dependencies)
3) Uncompress *.gz files
4) Run the test:
rnx2rtkp -c -o out.pos -k opts.conf -ti 1.0 "TLSE*15M_01S_MO.rnx" GBM0MGXRAP_20260600000_01D_05M_ORB.SP3 GBM0MGXRAP_20260600000_01D_30S_CLK.CLK BRDM00DLR_S_20260600000_01D_MN.rnx

The reference position for the station is: [4627851.574,119640.425,4372993.792]
