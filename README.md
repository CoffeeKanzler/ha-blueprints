# ha-blueprints

## Importing blueprints into Home Assistant

### Option 1: Import from file (local)
1. Copy the blueprint YAML file (e.g. `blueprints/automation/co2-notification-auto-clear.yaml`) into your Home Assistant config directory under:
   `config/blueprints/automation/`.
2. In Home Assistant, go to **Settings → Automations & Scenes → Blueprints**.
3. Click **Import Blueprint** and use **Pick file** to select the copied YAML file.

### Option 2: Import from URL
1. In Home Assistant, go to **Settings → Automations & Scenes → Blueprints**.
2. Click **Import Blueprint**.
3. Paste the raw file URL and click **Preview** then **Import Blueprint**.

### Creating an automation from the blueprint
1. Open **Settings → Automations & Scenes → Blueprints**.
2. Find the blueprint and click **Create Automation**.
3. Configure the inputs and save the automation.
