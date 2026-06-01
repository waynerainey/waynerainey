# I build the tools, not just talk about them

A talent acquisition consultant with thirty years in recruiting, HR, and people operations, on both sides of the hiring table, including Siemens, Roche, and Abbott. I run [The Career Cantina](https://thecareercantina.com), a coaching and content practice that sits upstream of tactics, at the intersection of AI, work, and human judgment.

Most career advice tells you how hiring systems are supposed to work. I am interested in how they actually work: semantic search, embedding-based matching, reranking, the machinery that decides whether you surface at all. Understanding that is where agency begins. So I build working diagnostics that let you watch the machinery read you, instead of taking my word for it.

The tools below are the argument.

---

## Tools

Live diagnostics, each built on a Career Cantina framework. Front ends are open source. The serverless functions keep every API key server-side, never in the bundle and never in git.

| Tool | What it shows you | Live | Source |
|------|-------------------|------|--------|
| **Semantic Heat Map** | How an AI hiring system reads your LinkedIn profile against a target role, phrase by phrase, HOT to COLD | [Open](https://thecareercantina.com/semantic-heat-map) | [Repo](https://github.com/waynerainey/semantic-heat-map) |
| **Career Triangulation** | Where your career signal actually points, and the strategic positioning that follows from it | [Open](https://career-triangulation.netlify.app) | [Repo](https://github.com/waynerainey/career-triangulation) |
| **Are You a Ghost?** | What a recruiter's search finds when they look for you across six sources, and the findability tier you land in | [Open](https://are-you-a-ghost.netlify.app) | [Repo](https://github.com/waynerainey/are-you-a-ghost) |
| **DCR Tool** | The full diagnostic of how a hiring system finds, files, and ranks you. The analytical engine behind the heat map | [Open](https://dcr-tool.netlify.app) | [Repo](https://github.com/waynerainey/dcr-tool) |

Stack across the set: React and single-file front ends, Node and Express services wrapped as Netlify serverless functions, the Anthropic API, multi-format document parsing, and full JSON-LD structured data so the tools are themselves discoverable by the systems they analyze.

All of it is open source. The source is published to show the work and to mark me as its origin. The frameworks these tools implement keep their names and stay attributed to me, and the names are the point. Methods travel freely. Provenance does not.

---

## Frameworks

The intellectual spine. A few of the load-bearing ones:

- **DCR›O** (Discovery › Categorization › Ranking › Output). The pipeline a candidate moves through inside an AI-mediated system. Discovery is binary, can you be found at all. Ranking is ordinal, where you land once you are in. Different problems, different solutions.
- **Semantic Amplification**. A five-part framework for making a profile legible to AI-driven discovery, from algorithm mechanics to job-posting deconstruction.
- **Career Middle Child**. How mid-career professionals get squeezed by hiring systems: too experienced for entry-level thresholds, too specialized for broad keyword matching. The invisible middle of the talent market.
- **Career Insurance**. Discoverability infrastructure built and maintained proactively, while employed, instead of assembled in crisis during a job search.
- **Trust-as-Currency**. How credibility gets encoded into systems that cannot verify it directly, and how to build and signal it as a career asset.
- **RISEE 2.0** (Research, Implementation, Simulation, Engagement, Education). A career development methodology that keeps the human story intact in an automated hiring landscape.

Full framework set and the deeper professional architecture: [github.com/waynerainey/wayne-rainey](https://github.com/waynerainey/wayne-rainey). Citable framework pages: [thecareercantina.com/frameworks](https://thecareercantina.com/frameworks/) (Summer 2026).

---

## Writing

- **Article library**, fifty-plus pieces organized as a curriculum, not a blog: [thecareercantinalog.netlify.app](https://thecareercantinalog.netlify.app)
- **Medium**, the long-form work: [medium.com/@wrainey929](https://medium.com/@wrainey929)
- **Podcast**, every article rebuilt as audio: [The Career Cantina on Spotify](https://creators.spotify.com/pod/profile/wrainey/)

Published weekly since November 2024.

---

## Elsewhere

- **Site:** [thecareercantina.com](https://thecareercantina.com)
- **LinkedIn:** [linkedin.com/in/wrainey](https://www.linkedin.com/in/wrainey)
- **Book a conversation:** [calendly.com/wayne-thecareercantina](https://calendly.com/wayne-thecareercantina/1-1-career-coaching)
- **Roles:** Founder, The Career Cantina. Co-founder, JobNet 2.0. Organizer, baHRC (Bay Area Human Resources Council). Member, Wharton AI Studio.
