# feliz-mes

A romantic surprise website built for a special date anniversary. It walks through four screens: a name-locked entry, a spinning roulette to pick an activity, a time selector, and a final reveal with the meetup details.

## How it works

1. The page unlocks when the recipient types the correct name.
2. A slot-machine roulette spins through six activity options: cine, pickleball, cena, minigolf, go karts, pintura.
3. She picks a time (5pm – 9pm).
4. A final screen shows the message and pickup details.

## Setup

No dependencies. Just open `index.html` in a browser.

To personalize, edit the following variables at the top of the `<script>` tag:

```js
const UNLOCK_NAME = 'sam'; // name to unlock the page (lowercase)
```

Place your gif at `assets/garu-pucca.gif` or update the `src` in the final page section.

## Stack

HTML, CSS, JavaScript — single file, no frameworks.
