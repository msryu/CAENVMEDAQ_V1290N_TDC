  -----------------------------------------------------------------------------
                   --- CAEN SpA - Computing Division ---
                                www.caen.it
  -----------------------------------------------------------------------------
  ### It is based on the CAEN VME DAQ code (V1190Readout-1.1-build20190709.tgz).
  ### Edited by Min Sang RYU (KNU) in Feb 2023 ###
  ### email: mryu93@gmail.com
  
  Program: V1290Readout

  -----------------------------------------------------------------------------
  Content
  -----------------------------------------------------------------------------

  README_ryu.txt    :  This file.
  README.txt        :  original file for ReadMe_ryu.txt
  ReleaseNotes.txt  :  Revision History and notes.
   src		:  Source files
   inc		:  Include files
   build        :  Windows Project files
   bin		:  Executable files, precompiled and custom-developed
                   template specific files (config.txt)

  System Requirements
  -----------------------------------------------------------------------------
  - Linux 32/64-bit
  - CAENVMELib library
  - V1190 | V1290 Digital TDC

  Installation
  -----------------------------------------------------------------------------
  Execute "make"
  
  Syntax - edited by ryu
  -----------------------------------------------------------------------------
  Usage: ./V1290Readout [config_file]
     ex: ./V1290Readout V1290Config.txt

  Output - added by ryu
  -----------------------------------------------------------------------------
  V1290_EventList.txt
  V1290_Histo_%d.txt (ch#)
  V1290_Raw_Data.txt
  V1290_plotdata.txt  
  rn%d_V1290_SavedHisto_ch%d_Ntrig%d.txt (rn#, ch#, evt#)  
  
  How to get support
  -----------------
  CAEN makes available the technical support of its specialists for requests
  concerning CAEN products. Use the support form available at the following link:
  https://www.caen.it/support-services/support-form



  

