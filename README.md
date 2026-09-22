# modapi

a currently work-in-progress program for our moderation API for OmniBlocks. This will provide stateless (as in, it's not connected to any backends, it's just for on-the-spot moderation, the caller provides all info) moderation of context such as text or images.

### the plan

- [ ] start with just a simple static wordlist filter
- [ ] add LLM-based moderation. Now, while AI is a spicy topic, I don't think it's a bad idea to use it for moderation (it's not like we're making a chatbot that feeds user's delusions and tells people to eat rocks instead of kick rocks). The way we would do this is by calling our LLM wrapper API at boxy.omniblocks.org/llm which is hosted by the same program that hosts the [Boxy GitHub app](https://github.com/OmniBlocks/Boxy-gh) (our GitHub AI assistant). Then we can select some cheap model preferably made for moderation.
- [ ] add image moderation. We could probably do this with things such as sightengine but this is yet to be decided or discussed.
- [ ] stop being broke so we can host it 24/7 like boxy which never goes down

### license

OmniBlocks™ and Boxy™ are trademarks of the OmniBlocks Team. The art design for the Boxy mascot is ©2025-2026 The OmniBlocks Team. 
The rest of the code and assets are licensed under the AGPLv3 license unless otherwise noted. 

#### dual licensing

for commercial use,

nah jk lol we don't do that stuff go get sued by the SFC