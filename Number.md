# Algorithmite's Custom Number System

### Why Make a New Number System?

#### Chinese Inspiration

As stated in the Readme, I once heard that Chinese children have an easier time learning to count than those in English speaking countries. This isn't because they are inherently smarter but it is due to the numbers being simpler in Chinese than they are in English.

Specifically Chinese numbers are simpler in 2 ways:
1. Chinese numbers are shorter and easier to say.
2. Chinese Counting does not have the same irregular numbers as English. (We say 21 twenty one so why not 11 tenty one)

So eliminating these two issues should be fairly straightforward. Simply rename the characters 0 - 9 as single syllable words and ignore any irregularities in counting.

#### A Step Further

Why not take this a step further? If I were to create a number system that I would be happy using what would that look like?

As it stands this solves a couple of issues with our current number system but there are more opportunities to improve. I'd also like to make this number system :
1. Base Agnostic (At least able to express bases within the system easily)
  * Currently we refer to other bases by the base 10 counterpart (Base 10 or Decimal, Base 2 or Binary, Base 16 or Hexadecimal, etc.)
  * This can be accomplished by creating new number characters that are a function of the base being used or by creating pronunciations that allow for any base to be expressed. Both of these options will be explored more later.
  * For this system I will be actively supporting through Base 16. This is because that base is used heavily by computers but not many higher bases see much use.
2. Consistent
  * Currently the characters used are based on a varied history from multiple counting systems. This makes for meaningful characters that are not uniform. (1 and 7 look similar if drawn quickly, 6 and 9 are just rotated versions of the other, some characters are similar to english letters, etc.)
  * This can be accomplished by creating new characters based off of a function of some sort rather than from historical precedent.
3. Shows Symmetry
  * One of my favorite mathematical concepts is the idea of symmetry. Not only is a number equivalent to itself but also any subset of its prime factorization.
  * I'd like this system to showcase the number 2 especially as it is very useful in my chosen field of computer science and easily reflected in even and odd numbers in every even number based system.

In summary both the characters themselves as well as their pronunciation should follow a simple repeatable pattern. The result needs to be simple characters for any number base that are also easy to say out loud.

It's worth noting that while the characters are designed to be simple they are not designed for easy writing. This is because modern technology limits most written characters as it stands and more options open up if this is not considered.

### New Pronunciation

Knowing what we do about the pronunciation we can think of a few rules for every new character :
1. Each character must be unique
2. Each character must be a single syllable

It would also be nice to incorporate a few more things to make the system simpler :
1. Even and Odd Number Similarities
2. Easy to speak without mispronouncing characters
3. A logical progression while counting

With all of this in mind I propose the use of these simple rules to create our number progression :
1. Each character will consist of one consonant and one vowel
2. All Even characters will end with the vowel long o as in day
3. All Odd characters will end with the vowel long a as in throw
4. Each set of consecutive characters will start with the same consonant
5. Voiced and unvoiced consonants will follow each other in the sequence (i.e. k and g or t and d)

This leaves the task of choosing the consonants for the characters through base 16. These are the consonant pairs that work well for this.

z & s, k & g, t & d, p & f, 

That means that the characters for 0 - 15 are pronounced

0. zo
1. za
2. so
3. sa
4. ko
5. ka
6. go
7. ga
8. to
9. ta
10. do
11. da
12. po
13. pa
14. fo
15. fa

