# Automatic Action Scripts Generation Based on Home Environment Knowledge and LLM in VirtualHome
## Set Up (VirtualHome)
1. [VirtualHome](https://github.com/xavierpuigf/virtualhome) Setup
2. Refer to VirtualHome's Github to confirm that it works properly.

## Set Up (VirtualHome AIST)
1. [VirtualHome_aist](https://github.com/aistairc/virtualhome_aist/) Setup
2. Refer to virtualhome_aist's Github to confirm that it works properly.
3. Note that the simulator is different from the original VirtualHome. The simulator can be downloaded [here](https://github.com/aistairc/virtualhome_unity_aist/releases/tag/Door_Modified_Build_2023_0404/).
※ Note that the original VirtualHome and VirtualHome AIST have different python execution environments.

## How to execute the our system (VirtualHome Original)
1. Download the original_vh_program folder and put it under (virtualhome/).
2. Run VirtualHome.exe. (virtualhome/simulation/unity_simulator/VirtualHome.exe)
3. Open the jupyter file(original_vh_program.ipynb) and run it from the top. Put any action description in the last cell and run it to generate the action script.
※ Note that the [OpenAI](https://openai.com/) API is required for execution.

## How to execute the our system (VirtualHome AIST)
1. Download the aist_vh_program folder and put it under (virtualhome_aist/).
2. Run VirtualHome.exe. (virtualhome_aist/simulation/unity_simulator/VirtualHome.exe)
3. Open the jupyter file(aist_vh_program.ipynb) and run it from the top. Put any action description in the last cell and run it to generate the action script.
※ Note that the [OpenAI](https://openai.com/) API is required for execution.

## Reproduction of evaluation experiments
### LCS score

### Corecteness

### Simlator(execution rate)
