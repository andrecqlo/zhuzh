# Zhuzh

A zhuzh lifts the mood and breaks up the work: one short, slightly odd question, asked round the room. It works at a wrap-up, at the top of a stand-up, as an icebreaker, or any time a session needs air in it.

Open the page and it rolls to one of 200 questions at random, slot-machine style. Press **Another one**, tap the card, or hit space for a different one.

**Live:** https://andrecqlo.github.io/zhuzh/

## Running it locally

Open `index.html` in any browser. There is no build step and no dependencies — everything, including all 200 questions, lives in that one file.

## Adding or changing a question

Edit the `ZHUZHES` array in `index.html`. The array is in list order, so the question at index `n` shows as `#n+1`. Add to the end and the number badge takes care of itself.

## How to use the list

- Every question opens onto a story rather than a yes or no, and every one should make sense on first hearing. If a question needs explaining, it is the wrong question.
- Anyone can pass. A zhuzh that becomes an obligation stops being fun.
- Answer first if you are chairing. It sets the length and the silliness level.
