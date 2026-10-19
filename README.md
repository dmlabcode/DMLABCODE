DM LAB is part of the Children psychology department at University of Miami.
We have different homemade and edited tools we use.

1) Location and Vocalization data processing, integration and reporting (https://github.com/dmlabcode/UL_Processor_2223 through 2026)
   
2) Transcription and diarization alignment: whisper_vtc1_alignment.py aligns an existing Whisper transcript with an existing VTC/ALICE diarization of the same audio file. Script is inside the prior project and you may find it at https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/whisper_vtc1_alignment.py

3) Kalman filter and interpolation of location and audio data (LENA): denoiseV5 is a scriot used to https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/denoisev5.py. This is a new and debugged version of the Supplement prepare_classroom_motion_vocal_dataset.py code used.

4) Mean length utterances for existing whisper vtc files: MLU_calculation.py. https://github.com/dmlabcode/UL_Processor_2223/blob/master/UL_Processor_V2020/MLU_calculation.py
