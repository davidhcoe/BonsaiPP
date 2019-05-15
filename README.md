## Generating Access Keys

To generate Access Keys, log in to your dashboard at https://beta.bons.ai. Once there, click on the down arrow next to your user name in the upper right. Click **Account Settings**. 

On the Account Settings page, click the **Access Keys** tab. 

After the page loads, click on the **New Access Key** link. This will generate a new access key to be used with the [Bonsai command line tool](https://github.com/BonsaiAI/bonsai-cli).

## EnergyPlus Project
EnergyPlus is a demo project that shows how to optimize an HVAC system. 

To create your brain, log in to (https://beta.bons.ai) using your credentials. Click on **New Brain** and select the **EnergyPlus** project. Give your brain a name, an optional description, then click **Create BRAIN**.

After your brain is created, you will be re-directed to the brain's page showing the training graph and code assets. 

<!-- Open the Python command line where you installed the Bonsai CLI. Navigate to a directory where you want to work. Then run the command:

```
bonsai list
```

Locate the name of your EnergyPlus brain, ie, energy-pp-demo. 

Run the command 

```
bonsai pull -b <brain_name>
```

replacing <brain_name> with the name of your EnergyPlus brain.

If necessary, confirm the downloaded files.

Run the command

```
bonsai pull -b <brain_name>
```

The directory should contain the following files:

- bonsai_brain.bproj
- EMSWindowShadeControl.idf
- energyplus.ink
- energyplus_simulator.py
- requirements.txt
- variables.cfg

Run the command

```
pip install -r requirements.txt
```

This command ensures you have the correct Python requirements loaded for the simulator to run. It may take a few minutes to run depending on what you currently have in the environment.

After it completes, run the command

```
python energyplus_simulator.py --brain=<brain_name>
``` -->

To start working with EnergyPlus, you must download some additional assets and follow the README from https://github.com/BonsaiAI/bonsai-sdk/tree/master/samples/energyplus-sample. 
