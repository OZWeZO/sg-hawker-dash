# sg-hawker-dash 🍜🇸🇬

A **micro‑demo project** 
It lists 10 iconic **Singapore hawker dishes** and randomly recommends one for your next meal.

> _“Dash to the nearest hawker and makan!”_

---

## Features
- 🎲 Random dish picker (`python hawker.py --random`)
- 📋 Full list output (`python hawker.py --list`)
- 🕰️ Optimised for `Asia/Singapore` timezone formatting

---

## Quick Start

```bash
# clone
git clone https://github.com/your‑username/sg-hawker-dash.git
cd sg-hawker-dash

# (optional) create venv
python -m venv .venv && source .venv/bin/activate

# install deps
pip install -r requirements.txt   # only needs 'click'

# run
python hawker.py --random
