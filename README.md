# Security Research

## Music Notes -> Stolen by Telekinesis

I’ve discovered a security vulnerability in the musicnotes.com website. The vulnerability can be remediated by disabling screenshot capabilities in the browser. A musician is required to pay approximately 5 dollars for a single sheet of music. However, the first page of the song is shown as a free preview. Most piano songs can be transcribed onto a single sheet of paper. A well trained musicians can simply screenshot and print the first page and deduce the rest of the song. And the majority of mainstream songs are only a page long. This leads to a loss of compensation to the musicnotes.com website, as any user can circumvent payment using their mind. 

Now, we must operatialize this theory. The goal is to turn this into a 1-click vulnerability. The songs are identified with an 8 digit number. For example, the song "Silent Night" is a simple song, whith the id `MN0051411`. [View Silent Night](https://www.musicnotes.com/sheetmusic/mtd.asp?ppn=MN0051411)
