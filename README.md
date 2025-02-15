
# Eliza Mantle DevRel

Accessible from X:
https://x.com/AgentK154
telegram:
t.me/@MantleDevrelBot

## About

Inspired by by the idea to automate more jobs, creating an AI devrel is a great use for an AI agent. The devrel that I created tweets around every hour on the topics of his domain of knowledge, and can answer questions on telegram. 

The Agent uses a knowledge base scraped from Mantle docs. 

From this job description I created a persona, biography, and other character attributes for the Eliza Agent.

https://careers.near.org/companies/mantle-network-2/jobs/39849802-senior-devrel-engineer

I created the twitter profile for the Agent and a telegram bot. 

Prior to starting this hackathon I did not know much about Eliza framework, so I spent a lot of time learning about it and trying to run the github client, but ran into errors. I contributed to the community by posting a GitHub issue that detailed the steps so that it can be fixed for future users. https://github.com/elizaOS/eliza/issues/3513

### Ideas for future improvements:

fine tune the model to make it more personalized

1. Give the agent actions to be able to search discussions on x, telegram channels, subreddits, and news articles, to aggregate information, summarize and post comments on the latest updates.
2. Increase the knowledge base to include more blogs, articles, code examples, relevant libraries and other relevant texts. 
3. Make the Dev Rel a 24/7 streamer, where they can summarize latest web3 developments. This would be a valuable source of information where they can comment and educate on latest protocols and Dapps in the ecosystem.


## Where to talk to Devrel:

Accessible from X:
https://x.com/AgentK154

telegram:
t.me/@MantleDevrelBot

# websites scraped 
Used APIFY to scrape data
https://docs.mantle.xyz/


# used folder2knowledge on website data
node scripts/folder2knowledge.js ../mantleDevrelKnowledge


# how to run
pnpm install
pnpm build
pnpm start --character="characters/mantleHelper.character.json"

