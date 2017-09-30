# fpga-sdr-rev-2.5

These are the Matlab files for the Revision 2.5 version of the FPGA SDR Simulink model.

Notes:
1.  The FPGA SDR design utilizes a Waveshare Xilinx 3s500e Development Board.  (For more information on the design, start here: http://k6jca.blogspot.com/2017/02/an-fpga-sdr-hf-transceiver-part-1.html)
2.  The Matlab version that I used:  R2009b, along with Simulink.  Note, I purchased the "Home" version of Matlab and Simulink.  Purchasing the current "Home" versions should also allows you to download previous versions, such as R2009b.  At least, I could download (for free) previous versions after I purchased my "Home" version several years ago.
3.  The Simulink Model file (Xcvr_SSB_AM_2p5.mdl) is THE design file.  All other files are ancillary files.
4.  You will also need the Xilinx ISE Design Suite for the Xilinx blockset required by the Simulink model as well as for the tools to create and load the .bit file onto the Xilinx 3s500e board.  I'm using the "Xilinx ISE Design Suite  12.2".
5.  Regarding the Xilinx ISE Design Suite:  Use the Xilinx "Project Navigator" to convert the .xise file into the final .bit file (the .xise files is created by clicking on the Xilinx "System Generator" block that is on the top levle of the Simulink model) .  And then use iMPACT (from the Xilinx ISE) to load the .bit file into either the eeprom on the Waveshare board or into the FPGA itself.

MOST IMPORTANT NOTES OF ALL:
1.  These files are free to all.
2.  I am not available to provide help (which is the hidden price of having the files be free to all).  Therefore, if you want to use these files, I recommend that you be already familiar with Matlab, Simulink, and the Xilinx tool set, and that you are comfortable with using them to create FPGA designs and files that can be downloaded into actual FPGA devices.  If you do not have this familiarity, learning how to properly set up and use the tools can be a major major issue.  So, before you spend money on anything, I would recommend that you first know what you are getting into, or that you have colleagues who are familiar with the tools and design process and who are willing to help you.
3.  Finally, I might have made a mistake in my designs, equations, schematics, models, etc. Do not assume that the design is bug free!  And also, this design and any associated information is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
