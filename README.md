# AlfredLightToggle
A keyword toggle to turn MacOS keyboard backlight or screen brightness on/off using in-built Alfred Automations.

## Usage
To toggle screen brightness on/off, use the default keyword `brightness`
To toggle keyboard backlight on/off, use the default keyword `backlight`

### Configuration
These keywords **can be changed** within the initial configuration on import into alfred.

### Screenshots

<img width="736" height="127" alt="Screenshot 2026-02-08 at 18 10 23@2x" src="https://github.com/user-attachments/assets/3fb3992a-0a93-4624-b12b-8f36bde16dca" />
<img width="726" height="130" alt="Screenshot 2026-02-08 at 18 10 40@2x" src="https://github.com/user-attachments/assets/01843861-928f-4a6c-a4b0-36586d77f646" />
<img width="648" height="532" alt="Screenshot 2026-02-08 at 18 10 11@2x" src="https://github.com/user-attachments/assets/843ab5b9-4d9b-44ca-88fb-ce96e72892c9" />

---

### Extra notes
Keyboard state and brightness state are stored as environment variables and should **not be changed**. The environment variables are important to keep as this information is read in the toggle logic.
