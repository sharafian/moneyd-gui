# Moneyd GUI
> A GUI for Moneyd

- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [TODOs](#todos)
- [More Screenshots](#more-screenshots)

![Status Page](./screenshots/status.png)

## Usage

```sh
git clone git@github.com:sharafian/moneyd-gui.git
cd moneyd-gui
npm install
npm start
```

Make sure you start Moneyd with `--admin-api-port 7769`.

Then go to [localhost:7770](http://localhost:7770) in your browser.

## Environment Variables

| Variable | Default | Purpose |
|:--|:--|:--|
| `PORT` | 7770 | Port to host the GUI's webserver on |
| `ADMIN_API_PORT` | 7769 | Port for moneyd's admin API. Set with `--admin-api-port` in moneyd |

## TODOs

- [ ] spiffier transitions?
- [ ] better 404 page
- [ ] better 500 page (instruct to turn on moneyd with flag)
- [ ] health check for moneyd by using plugin btp?
- [ ] ping tool
- [x] network indicator
- [x] send tool
- [ ] receive tool
- [x] implement statistics
- [ ] align icons and labels properly
- [ ] highlight selected item in nav
- [ ] make exchange rates more of a grid
- [ ] some visualizations?
- [ ] links to tutorials
- [ ] web monetization health

# More Screenshots

![Sending Page](./screenshots/send.png)
