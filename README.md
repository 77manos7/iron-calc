# Iron Calc — Power Cost Dashboard

Single-page **appliance electricity cost calculator**: watts or direct kWh, monthly totals in €, and Greek-style fixed charges (pagia / dimos / ERT).

**Live:** [77manos7.github.io/iron-calc](https://77manos7.github.io/iron-calc/)

## What it does

- Add appliances by power (W) + hours, or paste monthly kWh
- Set rate €/kWh and fixed monthly costs
- See total kWh, variable cost, fixed cost, and grand total
- Runs entirely in the browser — no backend

## Stack

Vanilla HTML + CSS + JavaScript (`index.html` only). Served via GitHub Pages from `main` `/`.

## Local

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## License

Personal demo. Use freely with attribution if you republish.
