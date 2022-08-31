## Bird Sanctuary

This oranisation is meant to keep the awesome Bluejay 8Bit ESC firmware alive and push it forward until the maintainer returns and takes back his project - or it might stay here for ever.

* [Bluejay](https://github.com/bird-sanctuary/bluejay)
* [Bluejay Documentation](https://github.com/bird-sanctuary/bluejay-documentation)
* [Join us on Discord](https://discord.gg/phAmtxnMMN)
* [ESC Configurator](https://esc-configurator.com)


## Takeover statement
Just for the sake of completeness, this is the statement we published on Discord when we "took over" the project:

Hey everyone,
as you might have noticed, @mathias has been absent for quite some time now. He is alive, but very unlikely to come back any time soon. We still want to move the project forward and thus created an organisation on github to move the project to (https://github.com/bird-sanctuary). The new owners are @saidinesh5 @damosvil @Burdalfis and myself - @mathias is obviously also added as an owner, although he has not accepted yet. We were hoping for a "clean" transfer of the project to the organisation, keeping issues, Wiki and PRs - should this not happen till the end of the month we decided to manually fork and copy the most important things (mainly the Wiki), in order to continue development.

This is the new place that all further development will be happening on and which https://esc-configurator.com will use as a source for Bluejay in the future.

> I want to make clear, that this is not a coup against @mathias - if he comes back, we will accept him as our overlord and the project will be handed to him as the lead dev.

Bluejay is currently being pushed as the "standard" for EFM8 based ESCs. We are looking into a "certification" system for ESCs running Bluejay (more on this at a later time).

Currently our road-map looks something like this:

* EDT - Extended Dshot telemetry, allows to send all kinds of telemetry back to the flight controller (ESC temp, debug flags)
* Support BB5 MCU - BB2 MCUs seem to be harder to get according to some manufacturers, the BB5 should be a drop in replacement, maybe even providing some extra functionality in the future (ESC manufacturer help is needed here)
* Improve code documentation - especially to give people an quick, high level overview of what the firmware does and how components interact with each other
*Migrate from Assembler to C via SDCC

There is no strict timeline as to when things are done. The team is still only a collective of interested individuals doing this work unpaid - in their spare time.

If you want to help, please join us in the development channel. We are also always looking for people to test new functionality, if you are interested in that, please join us in the testing channel.

To ESC/AIO manufacturers: **We need your help!** If you are planning on using BB5 MCUs, please contact me. We will also need samples in order to be able to quickly develop and reliably test.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
