# AI BUSINESS CASE STUDY: SUNO - GENERATIVE AI FOR TEXT TO MUSIC
CU-VIRT-AI-PT-06-2024-U-LOLC: Module 1 Challenge: AI Business Case Study

testing sync 6:01 PM

## Overview and Origin
* Name of company: Suno, Inc.

* When was the company incorporated?
Suno is a private startup company, founded in 2022.  According to pitchbook.com, the company raised $125 million through a Series B funding round that closed on May 21, 2024.  

* Who are the founders of the company?
Martin Camacho (Co-Founder & Chief Architect)
Georg Kucsko (Co-Founder)
Keenan Freyberg (Co-Founder)
Michael Shulman (Co-Founder and Chief Executive Officer)

* How did the idea for the company (or project) come about?
All four founders worked together as Machine Learning experts at a company called Kensho Technologies which is the AI and Innovation Hub for S&P Global, itself a public S&P 500 company (SPGI) in the financial services (information and analytics) industry.  They worked jointly on transcription software for public companies’ earnings calls.  This resulted in the founders becoming inspired to explore AI audio, specifically because ““audio in general is so far behind images and text. There’s so much that we learn from the text community and how these models work and how they scale.”  Several of the founders are amateur musicians, leading them to decide that their roadmap would ultimately lead them to a music-based product.
Suno’s first product, Bark, was a generative audio AI model that converts text-to-speech software.  Customer discovery on the software, which was officially built for research purposes, resulted in the Company pivoting the business towards music generation.  From AskRPA.com, “Suno embarked on a journey to decode the complexities of audio, particularly music, leveraging techniques similar to large language models like ChatGPT” by developing an in-house Generative AI software, the first version of which was released initially called Chirp and has since been rebranded to Suno – a proprietary software that is not open source and for which the training data has not been disclosed.

* How is the company funded? How much funding have they received?
Suno is a private company that started conventionally with unspecified funding from a handful of angel and seed investors, resulting in $1.4M in raised capital.  Subsequently, the company raised more formally from venture capital firms and has disclosed the total raised to be $125M, translating to a valuation of $500M and representing the largest Music AI startup investment to this point.

## Business Activities
* What specific problem is the company or project trying to solve?
From the Suno website, the company is described as “a generative artificial intelligence music creation program designed to generate realistic songs that combine vocals and instrumentation, or are purely instrumental.”  Suno is ostensibly Midjourney for audio, enabling anyone to create music of any genre for personal and commercial use.  Technically, the company is focused on the advanced technical problem of developing music and lyrics through AI, 
* Who is the company's intended customer? Is there any information about the market size of this set of customers?
Suno’s customers can be addressed as three core segments; 1. “Civilian” consumers interested in making music for personal reasons, 2. Users with small businesses and/or more serious musicians - some of whom are interested in using the software for youtube or even to commercialize it (using a more expensive plan that allows for increased use of the software), 3. Musicians and 4. Entertainment professionals making music for commercial purposes (commercials, film, tv, et. Al).  Anecdotally, rareconnections.io indicates that generative AI in the music industry is expected to reach an aggregate valuation of $2.6B by 2032, building from an estimated market value of $229M in 2022.

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
Suno’s market advantages include offering higher bitrates and lossless audio support for better quality, allowing for longer songs than competitors.  Additionally, the creator experience (UX) is regarded to be more intuitive in the creation of music, instrumentals and lyrics.

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing - ;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
The Suno software – Chrip and Suno – is entirely proprietary and has not been released to the public domain.  As noted previously, the training data used to develop the system has also not been disclosed.  Techradar reports that “Suno works in a similar way to large language models (LLMs) like ChatGPT. Lots of training data (which in Suno's case, includes recordings of speech) help it construct original songs and lyrics based on your prompts. With text, LLMs typically work by predicting what words are most likely to come next in a given sequence, but this is far more challenging for music.  This is why Suno also uses so-called diffusion models (which [power the likes of Midjourney](https://www.techradar.com/computing/artificial-intelligence/midjourney-just-changed-the-generative-image-game-and-showed-me-how-comics-film-and-tv-might-never-be-the-same)) alongside transformer models. In an interview with [Lightspeed Venture Partners](https://youtu.be/ArynrUmFacM?feature=shared&t=881) Suno's CEO and Co-Founder, Mikey Shulman, said: "Not all audio is done with transformers, there's a lot of audio that's done with diffusion – and these two methods have pros and cons".  Suno relies on the underlying proprietary text-to-speech platform Bark.  With this, Suno’s music creation is built with advanced neural networks which translate keywords provided by the user and then breaks these keywords into elements which the AI system then uses to compare to known, tagged sounds and music that it has previously processed and categorized.
[Analysis from the Reddit AI Form: “…text to music models typically feature a transformer based language/music model sandwiched in-between a compression model such as descript audio codec, facebooks 'encodec' etc, and a text encoder such as googles T5. Compression models are typically gan based or diffusion based. suno/udio have likely trained their own compression models as publicly available versions of these models are mono.

compression models take music and 'compress' them into discrete tokens that the language/music transformer model can handle, than decompress the generated tokens by the language/music transformer model back into normal music. text encoders take text and generate embeddings that the model uses to predict its 'music' tokens with.

during training, music is combined with text embeddings (usually a description, tags, bpm etc) and fed through the model. Every time this happens the models weights are updated slightly based on the 'loss', which measures the deviation from the target data.

In terms of how the datasets prepared, its possible they are manually tagging/creating descriptions for all the music in their dataset. Its also possible they're using auto-taggers/embedding extractors to create them. Human made descriptions will generally be more descriptive and accurate but on the scale of the datasets required to generate models like these it can difficult to do. 

most companies up to this point have only used licensed datasets from libraries such as shutterstock or pond5. I think it's pretty clear they are using copyrighted material though in their dataset…”]


## Landscape

* What field is the company in?
The core product, Suno, is positioned for several tiers of the music and entertainment industries.
 
* What have been the major trends and innovations of this field over the last 5-10 years?
Major trends and innovations within the music industry over the recent past include tools to make the creation of music more accessible as well as more cheaply and efficiently.  These include samplers, music software such as Avid ProTools and mass-market software that is increasingly user-friendly.  Additionally, immersive audio such as 360 Degree Spatial Sound, allow for more depth of sound.  Streaming services have also improved, allowing for higher quality/bit rate audio to be distributed and discovered with enhanced facility and allowing creators to access distribution without the use of high-cost tools or the beauracracy and economics of record companies.  AI and related software (e.g. calibration of equipment) have been used earlier in more technical areas of music production, towards the end of the value stream, such as mastering of music and balancing levels.  In production, AI workflows have more commonly been used to enable the production process itself.
As is the case with many other industries, the common trend in music is the democratization of the creation of music – and a corresponding ability to distribute and monetize these products.  Distribution avenues include use in user-generated content platforms such as TikTok and YouTube as well as film and television studios being able to save money by generating music for their programs more cost effectively.  
Over 36.8% of music producers surveyed in rareconnections.ai report already having adopted AI music tools in their work.  21% of creators received two or more copyright violation complaints.  These developments build upon previous innovations such as the Music Genome Project.


* What are the other major companies in this field?
Udio is the primary competitor within the AI space, though other companies in this field include record companies and independent music creators.  The following is a  list of the direct competitors in AI: Orchestrate, Aiva, Mubert AI, Splash Pro, Boomy, Soundraw, Veed.io, Lalal AI, Voice AI

## Results
* What has been the business impact of this company so far?
The company is still in startup phase, having launched its third version of the software.  It is largely responsible for driving the awareness and the conversation addressing AI-generated music as an inevitable next step for the music industry – a disrupting force for many elements thereof.

https://rareconnections.io/ai-music-statistics/
* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
Number of users, Number of songs created, Total minutes/hours of content generated, Total streamed hours.  Suno reports having had 12M unique users.

* How is your company performing relative to competitors in the same field?
As Suno is still in the startup phase, the principal metric is the investment raised to this point which far outpaces any direct competition in its field.  In turn, it is consistently within the top two software products within the consideration set and mindshare of users/consumers.

## Recommendations
* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
1. Improved UX to further decrease barriers to use by non-technical users
2. Determining how to manage licenses and rights; While the company has not disclosed training data, Suno already faces accusations that some of the music that they produce sound very much like existing copywritten works which exposes them to copyright infringement and liability.  This is something that ChatGPT continually faces and will continue to be an issue: Who owns and can control the training data – is it fair use to train AI software on existing copywritten works?  Should the creators of the training data be compensated?  It will be very important to resolve these matters or Suno will likely be facing legal action such as Napster experienced.   (Napster was an early music streaming service that ultimately folded.  But Napster proved the streaming model and companies that came after it were able to work with publishing companies to ensure that royalties were tracked and paid.)
3. Continued fine-tuning of the output, better understanding nuances of user requests and expectations in order to improve the quality of the songs it produces.
4. Provide tools to more easily edit and add on to songs so that the user can keep what they want and edit/change what they don’t, similar to Midjourney’s editing tools.
5. As a moon shot, I would personally be interested in a companion product that does video to music whereby the AI could interpret and tokenize moving images in order to add custom music onto a home movie, youtube video/vlog or other creation in order to broaden capabilities and options of creators to further refine their products.

* Why do you think that offering this product or service would benefit the company?
In the aggregate, adding the above elements to Suno would allow for increased engagement and new users through a decreased learning curve, expanded opportunities by proactively addressing potential legal threats to the business, encouraging greater adoption and use by allowing users more control and applications through the use of the platform.

* What technologies would this additional product or service utilize?
Principally, the required technology would be a video processing AI that could parse out and tokenize video content.  While these are not yet in wide adoption, there are several AI Algorithms for Video Summarization which may be developing the appropriate tools as a lead-in to being able to create music; “These algorithms can identify and track specific objects or individuals in a video, allowing the summarization system to highlight their presence and importance. This is particularly useful in videos that involve multiple subjects or complex visual narratives.”  From this point, the next step would be to tagging and tokenize the various elements and then run them to text-to-video algorithms to generate the  corresponding video.  Elements of these include Automatic Scene Detection and Segmentation, Object Recognition and Tracking, Speech-to-Text Conversion for Generating Captions and Sentiment Analysis or Capturing Emotional Content.

* Why are these technologies appropriate for your solution?
AI music generation has been revealed to be significantly more difficult that text-to-image given the higher number of variables and necessity to create a sufficiently acceptable product (the music itself); being able to construct a process flow from video may be more efficiently achieved by running multiple algorithms based on existing, proven technologies.

 
# LIST OF SOURCES:
1. https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/navigating-the-generative-ai-disruption-in-software
2. [suno.com](https://suno-ai.org/)
3. https://pitchbook.com/profiles/company/512734-06#funding
4. https://askrpa.com/suno-ai/
5. https://kensho.com/about
6. https://github.com/suno-ai/bark
7. https://www.techradar.com/computing/artificial-intelligence/what-is-suno-ai
8. https://www.tomsguide.com/ai/suno-vs-udio-7-prompts-to-find-the-best-ai-music-generator
9. https://newmusicworld.org/technology-in-modern-music-production/
10. https://rareconnections.io/ai-music-statistics/
11. [https://arxiv.org/pdf/2306.05284.pdf ](https://arxiv.org/pdf/2306.05284.pdf?source=https://vi-control.net/community)
12. https://www.siliconrepublic.com/start-ups/suno-ai-music-startup-funding-lightspeed-generate-songs
13. https://www.rollingstone.com/music/music-features/suno-ai-chatgpt-for-music-1234982307/
14. https://hivo.co/blog/generating-video-summaries-with-ai-technology
