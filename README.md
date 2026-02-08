# AlfredLightToggle
A keyword toggle to turn MacOS keyboard backlight or screen brightness on/off using in-built Alfred Automations.

## Usage
To toggle screen brightness on/off, use the default keyword `brightness`
To toggle keyboard backlight on/off, use the default keyword `backlight`

### Configuration
These keywords **can be changed** within the initial configuration on import into alfred.

### Screenshots

<img width="1434" height="238" alt="Screenshot 2026-02-08 at 18 17 14@2x" src="https://github.com/user-attachments/assets/c8b3ba4f-e187-4652-bdec-dd8a3a5717ab" />
<img width="1430" height="252" alt="Screenshot 2026-02-08 at 18 17 32@2x" src="https://github.com/user-attachments/assets/7c251366-98b2-4471-9008-488936a2b7e7" />
<img width="648" height="532" alt="Screenshot 2026-02-08 at 18 10 11@2x" src="https://github.com/user-attachments/assets/843ab5b9-4d9b-44ca-88fb-ce96e72892c9" />

---


### Extra notes
Keyboard state and brightness state are stored as environment variables and should **not be changed**. The environment variables are important to keep as this information is read in the toggle logic.
