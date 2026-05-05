---
title: "Introducing Sinch Skills: Expert Sinch API knowledge, right inside your AI Coding Agent"
url: "https://sinch.com/blog/sinch-skills-brings-sinch-api-knowledge-into-your-ai-coding-agent/"
date: "Tue, 14 Apr 2026 19:10:41 +0000"
author: "The Sinch team"
feed_url: "https://sinch.com/blog/feed/"
---
<p>AI coding agents like Claude Code, Gemini CLI, and Cursor help you ship faster. But these agents are only as good as the context they have, and they often break when building with APIs. The agent isn’t the problem. It just needs the right knowledge. </p>



<p>That’s why we built <a href="https://sinch.com/ai/skills/" rel="noreferrer noopener" target="_blank"><strong>Sinch Skills</strong></a> – a robust set of structured knowledge files that give your AI coding agent expert-level context for every Sinch API. <a href="https://github.com/sinch/skills" rel="noreferrer noopener" target="_blank">Install</a> once, and your agent handles the rest. </p>



    <nav class="toc-block longform-spacings px-5 py-6 px-md-6 px-lg-7 py-md-7 bg-light fs-sm rounded-lg"><p class="h5 m-0" id="toc-title-7472">Table of contents</p><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">01</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#why-ai-generated-api-integrations-often-fail">Why AI-generated API integrations often fail</a></div></div><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">02</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#what-sinch-skills-are">What Sinch Skills are</a><a class="scrollme link-body-color" href="#progressive-disclosure-keeps-context-clean">Progressive disclosure keeps context clean</a></div></div><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">03</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#list-of-skills-covering-sinchs-portfolio-of-products">List of skills covering Sinch’s portfolio of products</a></div></div><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">04</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#from-developer-experience-to-agent-experience">From developer experience to agent experience</a></div></div><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">05</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#get-started-with-one-command">Get started with one command</a></div></div><div class="d-flex mt-3"><div class="w-auto fw-bold text-accent d-flex me-2">06</div><div class="d-flex flex-column"><a class="fw-bold scrollme link-body-color text-accent" href="#about-sinch">About Sinch</a></div></div></nav>


<h2 class="wp-block-heading"><strong><strong>Why AI-generated API integrations often fail</strong></strong></h2>



<p>Generic AI training data gets you close to production-ready code, but “close” isn’t good enough.</p>



<p>When developers use AI agents to build with APIs today, they may run into some predictable problems: </p>



<ul class="wp-block-list">
<li>Auth methods vary by API </li>



<li>Regional endpoint rules are not always documented in a way agents easily pick up</li>



<li>Agents often retry billable actions, without first verifying the action’s state, leading to unnecessary charges </li>



<li>Async flows — webhook setup, processing modes, campaign approval — require sequencing that agents have to guess at without guidance. </li>
</ul>



<h2 class="wp-block-heading">What Sinch Skills are</h2>



<p>Sinch Skills are <a href="https://developers.sinch.com/docs/ai-support/sinch-skills">structured files</a> your AI coding agent reads as context, helping developers avoid the common problems of AI-generated API integrations. </p>



<p>Each skill is a directory containing a <code>SKILL.md</code> file with everything the agent needs to work with a specific Sinch API, including:</p>



<ul class="wp-block-list">
<li>Auth setup</li>



<li>Getting-started code</li>



<li>Key concepts</li>



<li>Common patterns and “gotchas” </li>



<li>Links to the full API reference</li>
</ul>



<p>Skills follow the <a href="https://skills.sh/">Agent Skills</a> open standard, which means they work with any tool that supports <code>SKILL.md</code> files — Claude Code, Gemini CLI, Cursor, Codex, GitHub Copilot, Windsurf, and others.</p>



<h3 class="wp-block-heading"><strong>Progressive disclosure keeps context clea</strong>n</h3>



<p>Skills use progressive disclosure, so they don’t overwhelm your agent’s context window. </p>



<ol class="wp-block-list">
<li>Your agent starts by loading only the name and description of each skill. This tells it what knowledge is available. </li>



<li>When a task matches a skill, the agent reads the full <code>SKILL.md</code> and any referenced scripts or assets.</li>



<li>Your agent generates code guided by real Sinch expertise, not training data guesswork.</li>
</ol>



<p>It&#8217;s deep knowledge, delivered exactly when your agent needs it.</p>



<h2 class="wp-block-heading"><strong>List of skills covering Sinch’s portfolio of products</strong></h2>



<p>We&#8217;re launching with coverage across every major Sinch product area:</p>



<figure class="wp-block-table"><table><tbody><tr><th class="has-text-align-left">Category</th><th class="has-text-align-left">Skills</th></tr><tr><td class="has-text-align-left">Core</td><td class="has-text-align-left">Authentication — OAuth2, API keys, SDK init across every API</td></tr><tr><td class="has-text-align-left">Messaging</td><td class="has-text-align-left">Conversation API, Provisioning API — 11 channels including WhatsApp, SMS, RCS, MMS, Viber </td></tr><tr><td class="has-text-align-left">Voice</td><td class="has-text-align-left">Voice API — callouts, IVR, TTS, conferencing, SVAML call control </td></tr><tr><td class="has-text-align-left">Video &amp; SIP</td><td class="has-text-align-left">In-App Calling, Elastic SIP Trunking</td></tr><tr><td class="has-text-align-left">Email</td><td class="has-text-align-left">Mailgun, Mailgun Inspect, Mailgun Optimize, Mailgun Validate</td></tr><tr><td class="has-text-align-left">Numbers</td><td class="has-text-align-left">Numbers API, Number Order API, Imported Numbers, 10DLC Registration</td></tr><tr><td class="has-text-align-left">Verification</td><td class="has-text-align-left">Verification API, Number Lookup API</td></tr><tr><td class="has-text-align-left">Other</td><td class="has-text-align-left">Fax API</td></tr></tbody></table></figure>



<p>Each skill goes beyond API examples. They include the real-world patterns, sequencing, and edge cases that make the difference between code that demos and code that ships. </p>



<p>A few examples of what that looks like in practice:</p>



<ul class="wp-block-list">
<li>The <strong>10DLC skill</strong> covers the full six-step registration workflow, including why vague campaign descriptions get rejected by TCR and why you should always use <code>FULL</code> registration type for production.</li>



<li>The <strong>Verification skill</strong> leads with the auth pattern developers get wrong most often: Application Key and Secret, not project OAuth2.</li>



<li>The <strong>Voice skill</strong> covers that <code>cli</code> is required for TTS callouts to connect, that instruction order in SVAML matters, and that ACE callbacks are not sent for in-app destinations.</li>
</ul>



<p>We&#8217;ve packaged <a href="https://developers.sinch.com/docs/ai-support/sinch-skills" rel="noreferrer noopener" target="_blank">years of our team&#8217;s knowledge</a> for your agent.</p>



<h2 class="wp-block-heading">From developer experience to agent experience</h2>



<p>Great developer experience used to be clear docs, good SDKs, and fast onboarding. Those things are still important. But now, a developer’s job is often to direct an agent that does the implementation. </p>



<p>That shift changes what “good developer experience” means. It’s not enough to have documentation a human can read. The knowledge must be in a form an agent can also use — structured, opinionated and scoped precisely. </p>



<p>Sinch Skills is <a href="https://community.sinch.com/t5/Developer-Blog/We-just-shipped-Sinch-Skills-here-s-why-we-built-it-and-what-s/ba-p/19471" rel="noreferrer noopener" target="_blank">our answer</a> to that. We want your agent to behave like a Sinch expert developer: knowing the right patterns, catching the common mistakes and generating code you can trust. </p>



<h2 class="wp-block-heading"><strong>Get started with one command</strong></h2>



<p><code>npx skills add sinch/skills</code></p>



<p>This command adds all the skills to your agent’s environment. You can also install skills individually or set them up from the <a href="https://github.com/sinch/sinch-plugins" rel="noreferrer noopener" target="_blank">Sinch Plugins repository</a> if you prefer.  </p>



<p>Skills are free and open source under Apache-2.0. You need a Sinch account to use the APIs the skills describe — sign up at <a href="https://dashboard.sinch.com/">dashboard.sinch.com</a>.</p>



<p>Browse the full Sinch skills library at <a href="https://mcas-proxyweb.mcas.ms/certificate-checker?login=false&amp;originalUrl=https%3A%2F%2Fgithub.com.mcas.ms%2Fsinch%2Fskills%3FMcasTsid%3D20892&amp;McasCSRF=1ad6079b84547b8f81ad4b2c68676a9182b43ffa3ec15d54f031892a727594e5" rel="noreferrer noopener" target="_blank">github.com/sinch/skills</a>. Check it out and let us know what you think! If you find it useful, give it a ⭐on GitHub to help us grow the community. </p>



<p><em>This is the beginning. We’ll be continuously updating skills as APIs evolve and expanding coverage based on what developers actually build. If you have feedback or want to contribute, the repo is open — pull requests welcome.</em> </p>



<h2 class="wp-block-heading"><strong>About Sinch</strong></h2>



<p><em>Sinch drives seamless conversations that create lasting connections between businesses and their customers. More than 150,000 businesses, including the world’s leading tech companies, rely on Sinch’s most reliable network for messaging, voice, verification and email. Visit </em><a href="https://sinch.com/" rel="noreferrer noopener" target="_blank"><em>sinch.com</em></a><em> to learn more about Sinch and our products and services.</em></p>
<p>The post <a href="https://sinch.com/blog/sinch-skills-brings-sinch-api-knowledge-into-your-ai-coding-agent/">Introducing Sinch Skills: Expert Sinch API knowledge, right inside your AI Coding Agent</a> appeared first on <a href="https://sinch.com">Sinch</a>.</p>
