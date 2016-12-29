# Add a meeting agenda page to your NationBuilder website
For most organizations, regular meetings are of vital importance. They provide an excellent way for team members to set goals, share ideas, and measure progress.

Here is a quick tutorial that provides a sleek and effective solution that allows you to schedule meetings, share agendas, and upload related documents to your NationBuilder site.

The best part? You can view both upcoming and past meeting agendas with this formula.

![Agendas Example](/agendas-example.png?raw=true)

## Relevant Files
**HTML:** pages_show_calendar_wide.html, agendas.html, agenda_upcoming.html, agenda_past.html, 

**SCSS:** _agendas.scss

**JS:** agendas.js

## How to Implement
**1.** Download these 6 files and upload them to your theme.*
**2.** In the theme.scss file, import the _agendas.scss partial.
```
// agenda styles
@import "agendas";
```
**3.** In the layout.html file, include the external agendas.js file just before the closing </body> tag.
```
<script type="text/javascript" src="agendas.js"></script>

</body>
</html>
```
**4.** Sign in to your NationBuilder dashboard and click + New page. Use “agenda” as the slug. The name doesn’t matter.

![Screenshot 1](/screenshot-1.png?raw=true)

**5.** Choose the “Calendar” page type.

![Screenshot 2](/screenshot-2.png?raw=true)

## Final Step
Nice work! You’re almost there. Now it’s time to add some meetings.

Click “New event” and fill in the required information. Once you’ve created it, you can add corresponding files to “Files.” Whichever file attachment gets uploaded last becomes the one that the “View Agenda” button links to.

You can add additional information, hyperlinks, etc. to Event settings > Intro.

By default, the page lists 4 meetings at a time. You can add past meetings to the page’s archive by changing their status to “Expired.”

## Contact Us
Need help with the implementation? Have questions? We’re here to help [max@chuckwalladesign.com](mailto:max@chuckwalladesign.com)
*This solution only works for NationBuilder’s public themes. Have a custom Bootstrap theme? Please don’t hesitate to [contact us](mailto:max@chuckwalladesign.com).
