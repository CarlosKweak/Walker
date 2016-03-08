# Bakery

## The story

One year and a half ago I became an iOS developer, I was happy, I knew how to do iOS apps, but static ones. I saw the animations behind Paper, or the transitions behind Mail, and I was impressed, I wanted to do that. After trying and trying, I did some great animations, I learnt FramerJS, which, in my opinion, has some beauty in it's springs, and I felt in love with it. Trying to learn more and more, I saw an article that talked about the animations in UIKit, and I started to investigate about spring, I saw that, putting a timing on it didn't make sense, and that's the reason why I want to bring the perfect animation to iOS development, the, in my opinion best platform to develop on.

## Code

To do animations the code used will be similar to this:

```
animate { firstView, secondView in
  firstView.alpha = 0
  secondView.alpha = 1
}.then {
  print('First animation done')
}.animate { cardView in
  cardView.alpha = 1
}
```

If you want to pass different parameters into the animation:

```
animate(0.25) { firstView, secondView in
  firstView.alpha = 0
  secondView.alpha = 1
}.animate(0.35) { cardView in
  cardView.alpha = 1
}
```

## Upcoming features

- [ ] Spring animations with rect and transforms.
- [ ] Bounce spring animation.
- [ ] More types of animations.

## Done by

Ramon Gilabert. With love.
