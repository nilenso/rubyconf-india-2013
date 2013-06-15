# slides
 
!SLIDE

# Tao of Ruby

# .

## kitallis@nilenso.com
## steven@nilenso.com

!SLIDE

# who are we?

!NOTES

who are we... and why should you listen to us?

!SLIDE

# @kitallis

# @deobald

!NOTES

much of the tao te ching is about time.
kitty is at the beginning of his career, I am at the end of mine.
(I am going to die in a horrifying chemical explosion next year.)

!SLIDE

![](images/c42-dark.png)

!SLIDE

![](images/rubymonk-logo-dark.png)

!SLIDE

![](images/nilenso.png)

!SLIDE

# what is nilenso?

!NOTES

...a company which employs some of these principles.

!SLIDE

# TODO: pie chart

!SLIDE

# TODO: consulting + bootstrapping

!SLIDE

#### → what is the tao te ching?
#### → a warning.
#### → on naming.
#### → on returning.
#### → on usefulness.
#### → on humility.
#### → on effortlessness.
#### → on leadership and love.

!SLIDE

# what is the tao te ching?

!SLIDE

![](images/lao-tzu-riding-an-ox.jpg)

!NOTES

The myth of Lao Tzu's self-exile. (do not present as fact)

!SLIDE

# probably not.

!SLIDE

# probably an oral tradition.

!SLIDE

# taoist philosophy (not religion)

# .

## nature
## "the way"
## the perfect human

!NOTES

General Taoist philosophy; not just the Tao Te Ching.

Taoist religion is wildly different from Taoist philosophy, and contains a lot of 
magic potions, rituals, and other BS.

The concept of "The Perfect Man" as written about in Taoist literature rarely speaks 
to the process of becoming perfect, but rather the behaviours of those (the wise) 
who have supposedly attained perfection.

!SLIDE

# taoist writing

# .

## double entendre
## paradox
## humour
## poetic / musical quality

!SLIDE

# TODO (maybe): one example of each writing utility

!SLIDE

![](images/flipkart-translations.png)

!SLIDE

![](images/book-feng-english-v1.jpg)

!SLIDE

# mawangdui manuscripts

@@@ ruby
Time.utc(1973)
@@@

!NOTES

...close to the POSIX Epoch. :)

!SLIDE

![](images/mawangdui-lao-tsu.jpg)

!SLIDE

@@@ ruby
Time.utc(-168)
@@@

!SLIDE

![](images/book-nair.png)

!SLIDE

# a warning

!SLIDE

# poem #1

<br/>
<span class="highlight">
  The Tao that can be told is not the eternal Tao.<br/>
  The name that can be named is not the eternal name.<br/>
</span>
The nameless is the beginning of heaven and Earth.<br/>
The named is the mother of the ten thousand things.<br/>
Ever desireless, one can see the mystery.<br/>
Ever desiring, one sees the manifestations.<br/>
These two spring from the same source but differ in name; this appears as darkness.<br/>
Darkness within darkness.<br/>
The gate to all mystery.<br/>

!SLIDE

# only "tao" is permanent

!NOTES

the only permanent thing (or perhaps non-thing) is "tao"

!SLIDE

# whatever we tell you today is inherently flawed and impermanent

!SLIDE

# poem #32

<br/>
The Tao is forever undefined.<br/>
Small though it is in the unformed state, it cannot be grasped.<br/>
If kings and lords could harness it,<br/>
The ten thousand things would come together<br/>
And gentle rain fall.<br/>
Men would need no more instruction and all things would take their course.<br/>
<span class="highlight">
  Once the whole is divided, the parts need names.<br/>
  There are already enough names.<br/>
  One must know when to stop.<br/>
  Knowing when to stop averts trouble.<br/>
</span>
Tao in the world is like a river flowing home to the sea.<br/>

!SLIDE

# we (developers) love to talk.

!SLIDE

# we (developers) love to make analogies and comparisons.

!SLIDE

TODO: architecture
TODO: engineering
TODO: gardening
TODO: wizards

!SLIDE

# forgive us.

!SLIDE

# on naming.

!SLIDE

# poem #32

<br/>
The Tao is forever undefined.<br/>
Small though it is in the unformed state, it cannot be grasped.<br/>
If kings and lords could harness it,<br/>
The ten thousand things would come together<br/>
And gentle rain fall.<br/>
Men would need no more instruction and all things would take their course.<br/>
<span class="highlight">
  Once the whole is divided, the parts need names.<br/>
  There are already enough names.<br/>
  One must know when to stop.<br/>
  Knowing when to stop averts trouble.<br/>
</span>
Tao in the world is like a river flowing home to the sea.<br/>

!NOTES

- do we really need to name everything? (lambdas? FRP vs. state/callbacks)
- identifying / naming abstractions

<!-- Game.loop do |enemy| -->
<!--     #enemy.pick_up_gun -->
<!--     #enemy.shoot -->
<!--     enemy.on_pick_up_gun { |e| e.shoot } -->
<!--     enemy.on_shoot {|e| e.die } -->
<!-- end -->

!SLIDE

# poem #25

<br/>
Something mysteriously formed,<br/>
Born before heaven and Earth.<br/>
In the silence and the void,<br/>
Standing alone and unchanging,<br/>
Ever present and in motion.<br/>
Perhaps it is the mother of ten thousand things.<br/>
<span class="highlight">
  I do not know its name<br/>
  Call it Tao.<br/>
  For lack of a better word, I call it great.<br/>
</span>
...<br/>

!NOTES

- the difficulty of naming
- concepts without names

!SLIDE

# ( demo/voyeurb.rb )

!SLIDE

### BIBLIOGRAPHY

- http://www.geekfarm.org/cgi-bin/tao.pl
- http://en.wikipedia.org/wiki/Mawangdui_Silk_Texts

!SLIDE

![](images/nilenso.png)

### THANKS!

#### @kitallis / @deobald
