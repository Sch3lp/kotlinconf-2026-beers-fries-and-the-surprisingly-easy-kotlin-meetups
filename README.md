# KotlinConf 2026: Beers, Fries, and the surprisingly easy Kotlin Meetups

This repository contains the slides **"Beers, Fries, and the surprisingly easy Kotlin Meetups"** presented at KotlinConf 2026.

## 📊 Slides

View the presentation slides online: 

## 📝 Abstract

Belgium has three languages, scattered developer communities, and a Kotlin user group (BEKUG) that went quiet after COVID.  
At KotlinConf in 2024 we connected by chance. That sent us home motivated and energised to revive things, but we quickly hit the classic wall: no speakers, no momentum.  
We decided to try OpenSpace: no CFP, no pressure, attendees build the agenda themselves on the day.

One person told us afterward:

> "I was skeptical, but it was really fun."

That was enough. 

Three meetups in, we're still learning: how to make the format feel inviting, how to balance talking with listening.  
But every session has organically produced community-driven conversation, and people keep coming back. 

You don't need a perfect lineup. You just need to keep showing up. 

Takeaways: what OpenSpace is, how to run it for a meetup, and why organizing is worth it even when it feels hard.

## Kodee config

- **variant**: Choose from available Kodee images
    - `greeting` - Kodee waving hello
    - `wink` - Kodee winking
    - `wave` - Kodee waving
    - `jumping` - Kodee jumping with joy
    - `sitting` - Kodee sitting down
    - `drinking` - Kodee with a drink
    - `heart` - Kodee with a heart
    - `in-love` - Kodee in love
    - `welcome` - Kodee welcoming
    - `winter` - Kodee in winter attire
    - `tiny` - Tiny Kodee

- **size**: Control Kodee's size
    - `small` - 200x200px (default)
    - `large` - 600x600px (500x500px for wave variant)
    - `medium` - TODO: Not yet implemented

- **position**: Control Kodee's placement
    - `corner` - Bottom right corner (default)
    - `featured` - Prominently displayed on slide
    - `custom` - Use with `x` and `y` coordinates

#### Custom Positioning

For precise control, use custom positioning:

```yaml
---
kodee:
  variant: greeting
  position: custom
  x: 100
  y: 200
  scale: 1.2
---
```

## 📄 License

See [LICENSE](LICENSE) file for details.
