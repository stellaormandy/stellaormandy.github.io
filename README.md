# stella ormandy's portfolio (open source template)

## to upload online using github pages

1. on github, click **+ → New repository**. name it  `YOURUSERNAME.github.io` (your GitHub username), set to **Public**,  click **Create repository**.
2. on the new repo page, click **uploading an existing file**. Drag in `index.html`, `README.md`, your `resume.pdf`, and the `images` folder. Click **Commit changes**.
3. go to **Settings → Pages**. Under "Build and deployment", set source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. wait a minute, visit `https://YOURUSERNAME.github.io`.

## adding photos

save each photo into the `images` folder using the exact names (lowercase, .jpg): edit as needed. until a photo is added, that card shows a coloured placeholder. keep photos under ~500 KB

| project name | file name |
|---|---|
| Photo of you (About section) | `me.jpg` |
| Environment-Mapping Robot | `mapping-robot.jpg` |
| Caffeine Meter | `caffeine-meter.jpg` |
| Keurig Smart Water Detection | `keurig.jpg` |
| WiFi Ultrasonic Sensor | `wifi-sensor.jpg` |
| Arduino Claw | `arduino-claw.jpg` |
| Carbon Fibre Nylon Testing | `cf-nylon.jpg` |
| Manufacturing Processes at UBC | `manufacturing.jpg` |
| Solar-Powered Automated Planter | `planter.jpg` |
| Carbon Fibre in Aerospace | `cf-aerospace.jpg` |
| Modular Nature Desk | `nature-desk.jpg` |


resume goes in the main folder as `resume.pdf`.

## editing projects

open `index.html`, scroll to section marked **EDIT YOUR CONTENT HERE**, each project is one `{ ... }` block. Copy a block to add a project, delete one to remove it. `category` must be `robotics`, `manufacturing` or `design` (edit as neeeded), and `featured: true` makes a card double-width. 

on GitHub,can edit `index.html` in the browser (from pencil icon), commit, and the site should update within a minute or two.
