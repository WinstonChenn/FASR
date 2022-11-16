# Mask-Sanitizer
Implementation of a mask sanitizer using Arduino

This top level version is ready to upload onto the given
  PCB with rare errors that can likely be resolved 
  by changing the thermal runaway condition slightly.
  
The most common error occurs when the last temperature 
  recorded is different from the next temperature recorded
  by 7 or more degrees. If we change this to 15 we will 
  likely have no errors. 
