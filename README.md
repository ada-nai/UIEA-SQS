# UIEA-SQS
Smart Queueing System App - [Project Description](https://www.youtube.com/watch?v=a_MuDrHDavA&feature=emb_logo)


![Output Screenshot from the Retail scenario](https://github.com/ada-nai/UIEA-SQS/blob/master/Output%20Screenshot.png)

## Tasks done in the Project

- Propose a possible hardware solution, based on three scenarios
- Build out your application and test its performance on the DevCloud using multiple hardware types
- Compare the performance to see which hardware performed best
- Revise your proposal based on the test results

## Hardware Proposal

### The Scenarios

Three different scenarios have been provided that depict real-world problems based on different sectors where edge devices are typically deployed.

The three scenarios you'll be looking at are:
- [Scenario 1: Manufacturing Sector](https://github.com/ada-nai/UIEA-SQS/blob/master/Manufacturing%20Scenario.txt)
- [Scenario 2: Retail Sector](https://github.com/ada-nai/UIEA-SQS/blob/master/Retail%20Scenario.txt)
- [Scenario 3: Transportation Sector](https://github.com/ada-nai/UIEA-SQS/blob/master/Transportation%20Scenario.txt)

An initial hypothesis/proposal is made as to which hardware suits the given scenario in the best possible way.

## Testing the Hardware on the [Intel® DevCloud](https://devcloud.intel.com/edge/)
- Now that an initial hypothesis is made about what hardware might work for the client, it's time to test it and see how it performs!
- The notebooks present in the repo are used to build out the smart queuing application and test its performance on all four different hardware types (CPU, IGPU, VPU, and FPGA) using the DevCloud.

PS: You need Intel® DevCloud access to perform inferences and submit job requests.

## Extrapolating Performance Data and Updating the Proposal
- Once hardware testing has been completed on all four hardware, a final decision can be made based on the paramters calculated after inference and processing frames:
1. Model loading time
2. Total inference time
3. Frames Per Second processing for given hardware
- The proposal is updated if required
