## Installation

### Option 1: Install via BRAT (Recommended for testing)

You can easily install this plugin using the BRAT (Beta Reviewers Auto-update Tester)
plugin:

1. Install and enable BRAT in Obsidian.
2. Open the BRAT settings panel.
3. Add this repository using the GitHub URL:

   ```bash
   ArctykDev/obsidian-calendar-events
   ```

4. BRAT will automatically download and update the plugin whenever new versions are released.

### Option 2: Manual installation

1. Download the latest release from the Releases page.
2. Extract the archive into your vault’s plugin folder:

   ```bash
   .obsidian/plugins/obsidian-calendar-events/
   ```

3. Ensure the folder contains the following files:

   ```bash
   main.js
   manifest.json
   styles.css (if applicable)
   ```

4. Reload Obsidian and enable SharePoint Calendar Events from the community plugins list.

### Option 3 — Manual (Developer)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/obsidian-calendar-events.git
   ```
2. Navigate to the plugin directory:

   ```bash
    cd obsidian-calendar-events
   ```

3. Install dependencies:

   ```bash
    npm install
   ```

4. Build the plugin:

   ```bash
    npm run build
   ```

5. Copy the following files to your vault’s plugin folder:

   ```bash
   <vault>/.obsidian/plugins/obsidian-calendar-events/
   ```

6. Include:

   ```bash
    main.js
    manifest.json
    styles.css (if present)
   ```

7. Restart Obsidian and enable Obsidian Calendar Events in the Community Plugins settings.
