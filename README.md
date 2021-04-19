# [![Yeagerist Music Streamer Bot](https://telegra.ph/file/7591ba3f76f4172cae227.jpg)](https://t.me/YeageristMusic_bot)

<!--start: description-->

**Yeagerist Music Streamer Bot** Yeagerist Music Streamer Bot  is a Bot That Can Play Music Via Voice Chat In Your Group 😌!

Features,

• Soundcloud Url Supported
• YouTube Url Supported
• Play Directly Via Telegram Audio Files
• Download Songs Via Deezer
• Download Songs Via Saavn
• Search Youtube Videos Inline
• No Time Duration Limits

Supports More Websites With More Features! 😋



<!--start: docs-->

_This README is also available in [🇧🇷 Brazilian Portuguese](./README.pt-br.md)_

## ⭐ How it works

- GitHub Actions is used as an uptime monitor
  - Every 5 minutes, a workflow visits your website to make sure it's up
  - Response time is recorded every 6 hours and committed to git
  - Graphs of response time are generated every day
- GitHub Issues are used for incident reports
  - An issue is opened if an endpoint is down
  - People from your team are assigned to the issue
  - Incidents reports are posted as issue comments
  - Issues are locked so non-members cannot comment on them
  - Issues are closed automatically when your site comes back up
  - Slack notifications are sent on updates
- GitHub Pages are used for the status website
  - A simple, beautiful, and accessible PWA is generated
  - Built with Svelte and Sapper
  - Fetches data from this repository using the GitHub API

_Upptime is not affiliated to or endorsed by GitHub._

[![Screenshot of status website](https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-status.png)](https://upptime.js.org)



## 👩‍💻 [Documentation](https://upptime.js.org)

1. [How it works](https://upptime.js.org/docs)
1. [Getting started](https://upptime.js.org/docs/get-started)
1. [Configuration](https://upptime.js.org/docs/configuration)
1. [Triggers](https://upptime.js.org/docs/triggers)
1. [Notifications](https://upptime.js.org/docs/notifications)
1. [Badges](https://upptime.js.org/docs/badges)
1. [Packages](https://upptime.js.org/docs/packages)
1. [Contributing](https://upptime.js.org/docs/contributing)
1. [Frequently Asked Questions](https://upptime.js.org/docs/faq)

### Concepts

#### Issues as incidents

When the GitHub Actions workflow detects that one of your URLs is down, it automatically opens a GitHub issue ([example issue #15](https://github.com/koj-co/upptime/issues/15)). You can add incident reports to this issue by adding comments. When your site comes back up, the issue will be closed automatically as well.

<table>
  <tr>
    <td>
      <img alt="Screenshot of GitHub issue" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-issue.png">
    </td>
    <td>
      <img alt="Screenshot of incident page" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-incident.png">
    </td>
  </tr>
</table>

#### Commits for response time

Four times per day, another workflow runs and records the response time of your websites. This data is commited to GitHub, so it's available in the commit history of each file ([example commit history](https://github.com/koj-co/upptime/commits/master/history/wikipedia.yml)). Then, the GitHub API is used to graph the response time history of each endpoint and to track when a site went down.

<table>
  <tr>
    <td>
      <img alt="Screenshot of GitHub commits" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-history.png">
    </td>
    <td>
      <img alt="Screenshot of live status" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-live-status.png">
    </td>
  </tr>
</table>
<!--end: docs-->

## 📄 License

- Code: [MIT](./LICENSE) © [Koj](https://koj.co)
- Data in the `./history` directory: [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)

<!--start: logo-->
<p align="center">
  <a href="https://koj.co">
    <img width="44" alt="Koj" src="https://kojcdn.com/v1598284251/website-v2/koj-github-footer_m089ze.svg">
  </a>
</p>
<p align="center">
  <sub>An open source project by <a href="https://koj.co">Koj</a>. <br> <a href="https://koj.co">Furnish your home in style, for as low as CHF175/month →</a></sub>
</p>
<!--end: logo-->
