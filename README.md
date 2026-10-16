DM LAB is part of the Children psychology department at University of Miami.
We have different homemade and edited tools we use.

1) Location and Vocalization data processing, integration and reporting (https://github.com/dmlabcode/UL_Processor_2223)
   
2) whisper_vtc1_alignment.py aligns an existing Whisper transcript with an existing VTC/ALICE diarization of the same audio file. Script is inside the prior project and you may find it at https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/whisper_vtc1_alignment.py

3) denoiseV5 is a scriot used to kalman filter and interpolation of location data and audio data (LENA) https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/denoisev5.py

4) MLU_calculation.py is a script used to get mean length utterances for existing whisper vtc files. https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/MLU_calculation.py
