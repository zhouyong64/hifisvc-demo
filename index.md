# <center> Audio Demos for "HiFi-SVC: Fast High Fidelity Cross-Domain Singing Voice Conversion" </center>

<center> Authors </center>  


## Abstract
This paper presents HiFi-SVC, a small cross-domain singing voice conversion model for generating high fidelity 22.05 kHz singing voices.

## Brief introduction
Best system

## Effects of Using Pitch Adjustment

| Reference sample | <audio src="CD_lj/ref/LJ002-0271.wav" controls preload></audio> |
| Source | w/o Pitch Adjustment | w/ Pitch Adjustment |
| :--- | :--- | :--- | :--- |
| <audio src="CD_lj/src/ADIZ_18.wav" controls preload></audio> | <audio src="pitch_adjust_samples/without/ADIZ_18_to_LJ002-0271.wav" controls preload></audio> | <audio src="pitch_adjust_samples/with/ADIZ_18_to_LJ002-0271.wav" controls preload></audio> |
| <audio src="CD_lj/src/MCUR_17.wav" controls preload></audio> | <audio src="pitch_adjust_samples/without/MCUR_17_to_LJ002-0271.wav" controls preload></audio> | <audio src="pitch_adjust_samples/with/MCUR_17_to_LJ002-0271.wav" controls preload></audio> |
| <audio src="CD_lj/src/MPOL.wav" controls preload></audio> | <audio src="pitch_adjust_samples/without/MPOL_20_to_LJ002-0271.wav" controls preload></audio> | <audio src="pitch_adjust_samples/with/MPOL_20_to_LJ002-0271.wav" controls preload></audio> |
| <audio src="CD_lj/src/NJAT.wav" controls preload></audio> | <audio src="pitch_adjust_samples/without/NJAT_16_to_LJ002-0271.wav" controls preload></audio> | <audio src="pitch_adjust_samples/with/NJAT_16_to_LJ002-0271.wav" controls preload></audio> |
| --- | --- | --- |

## Any-to-One Cross-domain (A2O-CD) singing voice conversion
### Target speech reference samples from LJ-Speech.

| Reference sample | <audio src="CD_lj/ref/LJ002-0271.wav" controls preload></audio> | <audio src="CD_lj/ref/LJ010-0295.wav" controls preload></audio> | <audio src="CD_lj/ref/LJ031-0224.wav" controls preload></audio> | <audio src="CD_lj/ref/LJ028-0335.wav" controls preload></audio> |
| Source | result1 | result2 | 
| :--- | :--- | :--- | :--- |
| 2: <audio src="CD_lj/src/ADIZ_18.wav" controls preload></audio> | <audio src="CD_lj/res1/ADIZ_18.wav" controls preload></audio> | <audio src="CD_lj/res2/ADIZ_18.wav" controls preload></audio> |
| 3: <audio src="CD_lj/src/JLEE_11.wav" controls preload></audio> | <audio src="CD_lj/res1/JLEE_11.wav" controls preload></audio> | <audio src="CD_lj/res2/JLEE_11.wav" controls preload></audio> |
| 4: <audio src="CD_lj/src/JTAN.wav" controls preload></audio> | <audio src="CD_lj/res1/JTAN.wav" controls preload></audio> | <audio src="CD_lj/res2/JTAN.wav" controls preload></audio> |
| 5: <audio src="CD_lj/src/KENN.wav" controls preload></audio> | <audio src="CD_lj/res1/KENN.wav" controls preload></audio> | <audio src="CD_lj/res2/KENN.wav" controls preload></audio> |
| 6: <audio src="CD_lj/src/MCUR_17.wav" controls preload></audio> | <audio src="CD_lj/res1/MCUR_17.wav" controls preload></audio> | <audio src="CD_lj/res2/MCUR_17.wav" controls preload></audio> |
| 7: <audio src="CD_lj/src/MPOL.wav" controls preload></audio> | <audio src="CD_lj/res1/MPOL.wav" controls preload></audio> | <audio src="CD_lj/res2/MPOL.wav" controls preload></audio> |
| 8: <audio src="CD_lj/src/MPUR.wav" controls preload></audio> | <audio src="CD_lj/res1/MPUR.wav" controls preload></audio> | <audio src="CD_lj/res2/MPUR.wav" controls preload></audio> |
| 9: <audio src="CD_lj/src/NJAT.wav" controls preload></audio> | <audio src="CD_lj/res1/NJAT.wav" controls preload></audio> | <audio src="CD_lj/res2/NJAT.wav" controls preload></audio> |
| 10: <audio src="CD_lj/src/PMAR.wav" controls preload></audio> | <audio src="CD_lj/res1/PMAR.wav" controls preload></audio> | <audio src="CD_lj/res2/PMAR.wav" controls preload></audio> |
| 11: <audio src="CD_lj/src/SAMF.wav" controls preload></audio> | <audio src="CD_lj/res1/SAMF.wav" controls preload></audio> | <audio src="CD_lj/res2/SAMF.wav" controls preload></audio> |
| 12: <audio src="CD_lj/src/VKOW.wav" controls preload></audio> | <audio src="CD_lj/res1/VKOW.wav" controls preload></audio> | <audio src="CD_lj/res2/VKOW.wav" controls preload></audio> |
| 13: <audio src="CD_lj/src/ZHIY.wav" controls preload></audio> | <audio src="CD_lj/res1/ZHIY.wav" controls preload></audio> | <audio src="CD_lj/res2/ZHIY.wav" controls preload></audio> |
| --- | --- | --- |

## Any-to-Many Cross-domain (A2M-CD) singing voice conversion

| Source | References (VCTK) | result1 | result2 |
| :--- | :--- | :--- | :--- |
| 14: <audio src="CD_vctk/src/ADIZ_18_to_p258.wav" controls preload></audio> | <audio src="CD_vctk/ref/p258_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/ADIZ_18_to_p258_to_p258_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/ADIZ_18_to_p258_to_p258_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 15: <audio src="CD_vctk/src/JLEE_15_to_p304.wav" controls preload></audio> | <audio src="CD_vctk/ref/p304_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/JLEE_15_to_p304_to_p304_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/JLEE_15_to_p304_to_p304_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 16: <audio src="CD_vctk/src/JTAN_16_to_p282.wav" controls preload></audio> | <audio src="CD_vctk/ref/p282_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/JTAN_16_to_p282_to_p282_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/JTAN_16_to_p282_to_p282_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 17: <audio src="CD_vctk/src/KENN_04_to_p248.wav" controls preload></audio> | <audio src="CD_vctk/ref/p248_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/KENN_04_to_p248_to_p248_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/KENN_04_to_p248_to_p248_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 18: <audio src="CD_vctk/src/MCUR_17_to_p233.wav" controls preload></audio> | <audio src="CD_vctk/ref/p233_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/MCUR_17_to_p233_to_p233_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/MCUR_17_to_p233_to_p233_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 19: <audio src="CD_vctk/src/MPOL_11_to_p256.wav" controls preload></audio> | <audio src="CD_vctk/ref/p256_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/MPOL_11_to_p256_to_p256_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/MPOL_11_to_p256_to_p256_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 20: <audio src="CD_vctk/src/MPUR_03_to_p248.wav" controls preload></audio> | <audio src="CD_vctk/ref/p248_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/MPUR_03_to_p248_to_p248_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/MPUR_03_to_p248_to_p248_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 21: <audio src="CD_vctk/src/NJAT_07_to_p243.wav" controls preload></audio> | <audio src="CD_vctk/ref/p243_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/NJAT_07_to_p243_to_p243_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/NJAT_07_to_p243_to_p243_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 22: <audio src="CD_vctk/src/PMAR_11_to_p311.wav" controls preload></audio> | <audio src="CD_vctk/ref/p311_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/PMAR_11_to_p311_to_p311_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/PMAR_11_to_p311_to_p311_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 23: <audio src="CD_vctk/src/SAMF_18_to_p335.wav" controls preload></audio> | <audio src="CD_vctk/ref/p335_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/SAMF_18_to_p335_to_p335_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/SAMF_18_to_p335_to_p335_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 24: <audio src="CD_vctk/src/VKOW_19_to_p259.wav" controls preload></audio> | <audio src="CD_vctk/ref/p259_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/VKOW_19_to_p259_to_p259_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/VKOW_19_to_p259_to_p259_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |
| 25: <audio src="CD_vctk/src/ZHIY_06_to_p307.wav" controls preload></audio> | <audio src="CD_vctk/ref/p307_ref.wav" controls preload></audio> | <audio src="CD_vctk/res1/ZHIY_06_to_p307_to_p307_ref.wav" controls preload></audio> | <audio src="CD_vctk/res2/ZHIY_06_to_p307_to_p307_ref.wav" controls preload></audio> |
| --- | --- | --- | --- |

## Any-to-Many In-domain (A2M-ID) singing voice conversion
### Female source singer

| Source sample from ADIZ (NUS-48E) | <audio src="ID_CL/src/ADIZ_18.wav" controls preload></audio> |
| reference | result1 | result2 | 
| :--- | :--- | :--- |
| 26: <audio src="ID_CL/ref/ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_ADIZ_18.wav" controls preload></audio> |
| 27: <audio src="ID_CL/ref/JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_JLEE_11.wav" controls preload></audio> |
| 28: <audio src="ID_CL/ref/JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_JTAN_07.wav" controls preload></audio> |
| 29: <audio src="ID_CL/ref/KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_KENN_10.wav" controls preload></audio> |
| 30: <audio src="ID_CL/ref/MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_MCUR_17.wav" controls preload></audio> |
| 31: <audio src="ID_CL/ref/MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_MPOL_20.wav" controls preload></audio> |
| 32: <audio src="ID_CL/ref/MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_MPUR_02.wav" controls preload></audio> |
| 33: <audio src="ID_CL/ref/NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_NJAT_16.wav" controls preload></audio> |
| 34: <audio src="ID_CL/ref/PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_PMAR_15.wav" controls preload></audio> |
| 35: <audio src="ID_CL/ref/SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_SAMF_13.wav" controls preload></audio> |
| 36: <audio src="ID_CL/ref/VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_VKOW_11.wav" controls preload></audio> |
| 37: <audio src="ID_CL/ref/ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res1/ADIZ_18_to_ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res2/ADIZ_18_to_ZHIY_03.wav" controls preload></audio> |
| --- | --- | --- |

### Male source singer

| Source sample from VKOW (NUS-48E) | <audio src="ID_CL/src/VKOW_20.wav" controls preload></audio> |
| reference | result1 | result2 | 
| :--- | :--- | :--- |
| 38: <audio src="ID_CL/ref/ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_ADIZ_18.wav" controls preload></audio> |
| 39: <audio src="ID_CL/ref/JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_JLEE_11.wav" controls preload></audio> |
| 40: <audio src="ID_CL/ref/JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_JTAN_07.wav" controls preload></audio> |
| 41: <audio src="ID_CL/ref/KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_KENN_10.wav" controls preload></audio> |
| 42: <audio src="ID_CL/ref/MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_MCUR_17.wav" controls preload></audio> |
| 43: <audio src="ID_CL/ref/MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_MPOL_20.wav" controls preload></audio> |
| 44: <audio src="ID_CL/ref/MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_MPUR_02.wav" controls preload></audio> |
| 45: <audio src="ID_CL/ref/NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_NJAT_16.wav" controls preload></audio> |
| 46: <audio src="ID_CL/ref/PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_PMAR_15.wav" controls preload></audio> |
| 47: <audio src="ID_CL/ref/SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_SAMF_13.wav" controls preload></audio> |
| 48: <audio src="ID_CL/ref/VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_VKOW_11.wav" controls preload></audio> |
| 49: <audio src="ID_CL/ref/ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res1/VKOW_20_to_ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res2/VKOW_20_to_ZHIY_03.wav" controls preload></audio> |
| --- | --- | --- |

## Cross-lingual (CL) singing voice conversion
### Female source singer

| Chinese Source sample | <audio src="ID_CL/src/JL95.wav" controls preload></audio> |
| reference | result1 | result2 |
| :--- | :--- | :--- |
| 50: <audio src="ID_CL/ref/ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_ADIZ_18.wav" controls preload></audio> |
| 51: <audio src="ID_CL/ref/JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_JLEE_11.wav" controls preload></audio> |
| 52: <audio src="ID_CL/ref/JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_JTAN_07.wav" controls preload></audio> |
| 53: <audio src="ID_CL/ref/KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_KENN_10.wav" controls preload></audio> |
| 54: <audio src="ID_CL/ref/MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_MCUR_17.wav" controls preload></audio> |
| 55: <audio src="ID_CL/ref/MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_MPOL_20.wav" controls preload></audio> |
| 56: <audio src="ID_CL/ref/MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_MPUR_02.wav" controls preload></audio> |
| 57: <audio src="ID_CL/ref/NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_NJAT_16.wav" controls preload></audio> |
| 58: <audio src="ID_CL/ref/PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_PMAR_15.wav" controls preload></audio> |
| 59: <audio src="ID_CL/ref/SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_SAMF_13.wav" controls preload></audio> |
| 60: <audio src="ID_CL/ref/VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_VKOW_11.wav" controls preload></audio> |
| 61: <audio src="ID_CL/ref/ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res1/JL95_to_ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res2/JL95_to_ZHIY_03.wav" controls preload></audio> |
| --- | --- | --- |

### Male source singer

| Chinese Source sample | <audio src="ID_CL/src/JL94.wav" controls preload></audio> |
| reference | result1 | result2 |
| :--- | :--- | :--- |
| 62: <audio src="ID_CL/ref/ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_ADIZ_18.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_ADIZ_18.wav" controls preload></audio> |
| 63: <audio src="ID_CL/ref/JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_JLEE_11.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_JLEE_11.wav" controls preload></audio> |
| 64: <audio src="ID_CL/ref/JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_JTAN_07.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_JTAN_07.wav" controls preload></audio> |
| 65: <audio src="ID_CL/ref/KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_KENN_10.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_KENN_10.wav" controls preload></audio> |
| 66: <audio src="ID_CL/ref/MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_MCUR_17.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_MCUR_17.wav" controls preload></audio> |
| 67: <audio src="ID_CL/ref/MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_MPOL_20.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_MPOL_20.wav" controls preload></audio> |
| 68: <audio src="ID_CL/ref/MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_MPUR_02.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_MPUR_02.wav" controls preload></audio> |
| 69: <audio src="ID_CL/ref/NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_NJAT_16.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_NJAT_16.wav" controls preload></audio> |
| 70: <audio src="ID_CL/ref/PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_PAMR_15.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_PMAR_15.wav" controls preload></audio> |
| 71: <audio src="ID_CL/ref/SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_SAMF_13.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_SAMF_13.wav" controls preload></audio> |
| 72: <audio src="ID_CL/ref/VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_VKOW_11.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_VKOW_11.wav" controls preload></audio> |
| 73: <audio src="ID_CL/ref/ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res1/JL94_to_ZHIY_03.wav" controls preload></audio> | <audio src="ID_CL/res2/JL94_to_ZHIY_03.wav" controls preload></audio> |
| --- | --- | --- |

