# PL2CW - Plain Language to CW

Converts arbitrary sources of "plain language" to morse code, for the purposes of receive practice.

## Context / Vision

There are many excellent morse code tutors available.  Fewer support plain language training (ie full sentences, including numbers and punctuation, with a clear communication intent). 

For example, the excellent LCWO (https://lcwo.net/plaintext) website offers a range of short proverbs, but has no length passages (say 2 mins long).  It's also not possible to progress to the next proverb without typing in an answer, which if practicing head copy or writing by hand is inconvenient.

https://mitxela.com/projects/morse_code_practice_tool will stream from news and wikipedia RSS feeds, and does not require an answer, but the range of inputs is restricted, and there's no timer feature, or pause feature - so it is not possible consume the feed continuously in, say, 2 min chunks, as the feed starts again at the beginning.

The Ham Morse iPhone app will stream news RSS feeds, does not need an answer, and does have pause feature, but has no scoring/validation feature.

All these tools require an internet connection.

I wanted a tool that would offer the following capabilities:

- No restrictions on source text - given any source of text, would convert it to CW
- A timer - would send CW for a specified length of time, and then stop
- Validation/marking of copied text
- No requirement for an internet connection

I also had no need for the other features of CW tutors - I don't need to learn the alphabet, I don't need Koch training, I don't need 5 letter groups, or most frequently used words, and I don't need any games or challenges. 

PL2CW is the tool I wish existed.  It follows the UNIX philosophy of doing one thing well, and is designed to be used in conjunction with any tool which can generate text on stdout - you can pipe fortunes, man pages, curl/jq etc through it.  It accepts stdin - you can type, and it will convert your text to CW for you, upon pressing enter, or you can pass it a file, and it will convert it.

## Current Functionality

None at all!

## Roadmap

- [ ] Make a beep

## Contributions

Suggested features and bug reports welcome.  Once out of prototype, bug fixes and enhancement welcome by pull request, if accompanied by unit tests.