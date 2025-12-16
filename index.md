---
layout: default
title: Concert History | Advanced Tableau Interactivity
---

# Personal Data Project: Advanced Drill-Down Map

This project solved a common data visualization challenge by creating a dynamic, two-level map interaction. I used custom Set Actions and calculated fields to allow users to drill-down from the high-level City summary to specific Venue details seamlessly.

<div class='tableauPlaceholder' id='viz1765865891819' style='position: relative'><noscript><a href='#'><img alt='2025 CONCERT HISTORY ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2025ConcertDashboard&#47;2025ConcertDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2025ConcertDashboard&#47;2025ConcertDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2025ConcertDashboard&#47;2025ConcertDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1765865891819');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else { vizElement.style.width='100%';vizElement.style.height='1377px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Technical Deep Dive & Skills Showcase

### Advanced Interactivity
* Implemented a custom **Set Action** to drive the map's Drill-Down Logic.
* Used the dynamic **IF/ELSE field** (`[Smart Location]`) to swap between geographic levels based on the active set.
* Developed a **dynamic tooltip** to display either City Summaries or Venue Details based on the explosion level.

### Design and Efficiency
* Applied a high-contrast **Dark Mode** theme with custom accents.
* Used a **Highlight Action** to stabilize text opacity on the BANs, preventing KPI numbers from dimming upon map selection.

<p>View the live Tableau Public workbook <a href="https://public.tableau.com/views/2025ConcertDashboard/2025ConcertDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">here</a>.</p>
