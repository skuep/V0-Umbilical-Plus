# Note that this Repo is the 'Plus' Version of the original V0-Umbilical
The original version was created by GitHub user timmit99 and can be found in the parent folder in this repository.

The 'Plus' version of the V0-Umbilical features an integrated ADXL345 Accelerometer that can be used for Input Shaper Tuning.
The Molex MicroFit connector was changed from a 14-pin to 20-pin version to acommodate the additional wires for the ADXL345.

In the following, the changes to the original README from timmit99 is given. Please read the README in the original project first.

### Frame PCB BOM
| Part      | Quantity | Notes | LCSC Part Number | Link |
| ----------- | :-: | ----------- | ----------- |----------- |
| 20 Pin Socket   |  1 | MOLEX 430452012 | C485575   | https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_MOLEX-430452012_C485575.html |
| SMD Thermistor  |  1 | 100K 0805 Thermistor | C143680   | https://lcsc.com/product-detail/NTC-Thermistors_Vishay-Intertech-NTCS0805E3104FXT_C143680.html |
| 2 pin JST XH    |  5 | 2.5mm pitch | C158012   | https://lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America-B2B-XH-A-LF-SN_C158012.html |
| 3 pin JST XH    |  2 | 2.5mm pitch | C144394   | https://lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America-B3B-XH-A-LF-SN_C144394.html |
| 4 pin JST XH    |  3 | 2.5mm pitch | C144395   | https://lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America-B4B-XH-A-LF-SN_C144395.html |
| 6 pin JST XH    |  1 | 2.5mm pitch | C144397   | https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America_B6B-XH-A-LF-SN_JST-Sales-America-B6B-XH-A-LF-SN_C144397.html |
| Screw Terminal  |  1 | 5.08mm pitch | C8465     | https://lcsc.com/product-detail/Screw-terminal_Ningbo-Kangnex-Elec-WJ500V-5-08-2P_C8465.html |


### Optional Parts
| Part      | Quantity | Notes | LCSC Part Number | Link |
| ----------- | :-: | ----------- | ----------- |----------- |
| 0805 10uF Capacitor  |  3 | Use if using BARE neopixel IC's. Strips have these already. | C17024     | https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21A106KPFNNNE_C17024.html |
----

### Toolhead PCB BOM
| Part      | Quantity | Notes | LCSC Part Number | Link |
| ----------- | :-: | ----------- | ----------- |----------- |
| 20 Pin Socket (Right Angle)   | 1 |  Molex 430452000  | C485576   | https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_MOLEX-430452000_C485576.html |
| 2 pin JST XH    | 6 |  B2B-XH  | C158012   | https://lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America-B2B-XH-A-LF-SN_C158012.html |
| 4 pin JST XH    | 1 |  B4B-XH  | C144395   | https://lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_JST-Sales-America-B4B-XH-A-LF-SN_C144395.html |
| LP2985-33DBVR   | 1 | 3.3V LDO | C95414    | https://www.lcsc.com/product-detail/Linear-Voltage-Regulators-LDO_Texas-Instruments-LP2985-33DBVR_C95414.html |
| ADXL345BCCZ     | 1 | Accelerometer | C9667     | https://www.lcsc.com/product-detail/Motion-Sensors-Accelerometers_Analog-Devices-ADXL345BCCZ-RL7_C9667.html |
| 10 Ohm Resistor | 2 | 0603 size |  C22859  | https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAF100JT5E_C22859.html |
| 10 kOhm Resistor| 1 | 0603 size |   C25804 | https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAF1002T5E_C25804.html |
| 4.7uF Capacitor | 2 | 0603 size |  C19666  | https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10A475KO8NNNC_C19666.html |
| 10nF Capacitor  | 2 | 0603 size |  C57112  | https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_10nF-103-10-50V_C57112.html/?href=jlc-SMT |
---

Corresponding CPL and BOM files are included in the repository. Using these files you can easily get yourself a ready-made assembled PCB from JLCPCB so you don't have to have the skills to solder the fine-pitch and 0603 packages.

## Umbilical cable

The Umbilical cable is a 220-240mm dual ended 20P (2x10) microfit cable. The connectors are wired 1:1 so pin 1 connects to pin 1 and so forth for all 20 pins.

### Cable BOM
| Part      | Quantity | Notes | LCSC Part Number | Link |
| ----------- | :-: | ----------- | ----------- |----------- |
| 20 Pin Plug     | 2  | Molex 430252000 | C485324   | https://lcsc.com/product-detail/Connectors-Housings_MOLEX-430252000_C485324.html |
| Crimps 20 AWG   | 12 | Molex 430300001/430300007 | C259786   | https://lcsc.com/product-detail/Line-Pressing-Terminals_MOLEX-430300001_C259786.html |
| Crimps 26 AWG   | 28 | Molex 430300004/430300010 | C259765   | https://lcsc.com/product-detail/Line-Pressing-Terminals_MOLEX-430300004_C259765.html |
| 20AWG Wire      | 12 | 220mm Sections  |    | PTFE/Silicone/Hefulon for motion rated, PVC *could* work since it isn't constraind to a cable chain |
| 26AWG Wire      | 28 |   |    |  |

MicroFit connectors support two different ranges of conductor thickness using different wire crimp ferrules. I recommend that you realize the stepper motor and heater wires with 20AWG wire (0.5mm²) and the remaining wires in 26AWG wire (0.14mm²) to save on weight and accelerated mass.
