# MythiCon Tracking System

Welcome to the **MythiCon Tracking System** (MyTS), the world's premier service for tracking, understanding, and managing the mystical creatures that roam far and wide in the enchanted forests of Computaria. From the elusive `Bugfoot` to the towering `Giraffle`, track them all with MyTS!

## Getting Started

To get started with MyTS, clone this repository and run the installation script. This should set up everything you need, including the latest dragon firewalls and unicorn authentication modules.

```bash
git clone https://github.com/magicalcreatures/mythicon
cd mythicon
./install.sh
```

Ensure you have the latest version of `wizard-node` installed, which is a more magical version of `node.js` designed specifically for entities in enchanted realms.

## Features

**MythiCon Tracking System** offers:

- **Real-time Location Tracking**: Know the exact location of every registered creature, from the `Desktop Trolls` under your desk to the `Cloud Giants` in the sky.
- **Mood Detection**: Find out how a creature is feeling, be it grumpy, joyful, or mysteriously sparkly.
- **Invisibility Support**: Track even the most invisible creatures, thanks to our patented `SeeMeNot` technology.

## How It Works

1. **Register a Creature**: Use the `/register` endpoint to add a new creature to your tracking list.
   ```bash
   curl -X POST http://localhost:3000/register -H 'Content-Type: application/json' -d '{ "name": "Pixie", "type": "Airborne", "character": "Sneaky"}'
   ```

2. **Track a Creature**: Use the `/track` endpoint to get the latest location and mood of the creature.
   ```bash
   curl http://localhost:3000/track?name=Pixie
   ```

3. **Feed a Creature**: Keep them happy and they won’t play tricks on you (hopefully).
   ```bash
   curl -X POST http://localhost:3000/feed -H 'Content-Type: application/json' -d '{ "name": "Pixie", "food": "Starlight Mints"}'
   ```

## User Data Example

Here's what you might see when you track a `Giraffle`, a creature known for its abnormally long neck and ability to eat leaves off cloud trees.

```json
{
  "name": "Gerry",
  "type": "Giraffle",
  "location": "Above the Rainbows",
  "mood": "Head in the clouds",
  "lastFed": "Cloud Berries",
  "visibility": "Partly Cloudy",
  "notes": "Often seen stretching its neck out of cloud cover. Loves listening to tall tales and cloud music."
}
```

## Caution

- **Do not feed chocolate to centaurs**—it makes them hyper.
- **Never tell a dragon it has bad breath**—it's considered highly offensive and might result in a scorched earth scenario.
- **Pixies can be mischievous**—double-check all data they give you, they've been known to fabricate JSON responses for fun.

## Contribute

Feel free to fork this repository, and submit a pull request with your enhancements. We especially welcome improvements to our `unicorn authentication modules` because, as everyone knows, unicorns are the worst at keeping secrets.

For major changes, please open an issue first to discuss what you would like to change. Ensure to update tests as appropriate.

## License

[MYTHICAL](https://opensource.org/licenses/MYTHICAL) - Feel free to use, enhance, or distribute
