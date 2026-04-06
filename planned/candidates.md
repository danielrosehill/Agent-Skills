# Skill Candidates

Organized notes for planned skills. Each entry: proposed skill purpose + reference repo (if any).

## Scaffolds / Templates
- **Human-agent scaffold template** — skill to set up a basic human-agent workspace in a repo with a `planning/` folder (sessions, plans, specs). Aligns with the [agentskills/agentskills](https://github.com/agentskills/agentskills) standard.

## Website-Served Skills
Skills intended to be served publicly from Daniel's sites (likely via MCP/HTTP endpoints or embedded widgets).

### danielrosehill.com
- **Contact** — structured contact submission / response
- **Download resume** — serve latest AI-readable + PDF versions
- **Book meeting** — gcal availability + booking flow
- **AI-friendly footer badge** — (see repo ref below)

### dsrholdings.cloud
- **Contact / enquiry intake**
- **Service overview Q&A**
- **Meeting booking**

### carrotcakeai.com
- **Product / service Q&A**
- **Lead capture**
- **Demo booking**

## Android / Mobile
- **adb-keep-awake ops** — ADB skills incl. running MVT scans. Refs: [adb-keep-awake](https://github.com/danielrosehill/adb-keep-awake), [Claude-MVT-Workspace](https://github.com/danielrosehill/Claude-MVT-Workspace)

## Agent / Claude Workspace Infrastructure
- **Agent-Junction setup** — [Agent-Junction](https://github.com/danielrosehill/Agent-Junction)
- **Agent picker pattern** — pick agents for a project. [Claude-Agent-Picker-Pattern](https://github.com/danielrosehill/Claude-Agent-Picker-Pattern)
- **Claude Janitor** — workspace cleanup. [Claude-Janitor](https://github.com/danielrosehill/Claude-Janitor)
- **Claude scaffold** — scaffold any defined Claude workspace (e.g. job search strategist style). [Claude-Job-Search-Strategist](https://github.com/danielrosehill/Claude-Job-Search-Strategist)
- **Claudify-This** — [Claudify-This](https://github.com/danielrosehill/Claudify-This)
- **Declaude** — [Declaude](https://github.com/danielrosehill/Declaude)
- **CLAUDE.md chunker** — [Claude-MD-Chunk](https://github.com/danielrosehill/Claude-MD-Chunk)
- **ClaudeMD Turnstile / separate CLAUDEs writer** — [ClaudeMD-Turnstile](https://github.com/danielrosehill/ClaudeMD-Turnstile)
- **Private/public CLAUDE.md split** — [Private-And-Public-Claude-MD](https://github.com/danielrosehill/Private-And-Public-Claude-MD), [Split-Claude-MD-Pattern](https://github.com/danielrosehill/Split-Claude-MD-Pattern), [Split-Context-Setup](https://github.com/danielrosehill/Split-Context-Setup)
- **Linux desktop CLAUDE.md seeder** — [Linux-Desktop-ClaudeMD-Seeder](https://github.com/danielrosehill/Linux-Desktop-ClaudeMD-Seeder)
- **New-turn Claude hook** — [New-Turn-Claude-Hook](https://github.com/danielrosehill/New-Turn-Claude-Hook)
- **Slash commands bundle** — [Claude-Slash-Commands](https://github.com/danielrosehill/Claude-Slash-Commands)
- **Linux desktop slash commands plugin** — [Claude-Code-Linux-Desktop-Slash-Commands](https://github.com/danielrosehill/Claude-Code-Linux-Desktop-Slash-Commands)

## Repo Management
- **Repo creator / jumper / retrofitter** — [Claude-Repo-Creator](https://github.com/danielrosehill/Claude-Repo-Creator), [Claude-Repo-Jumper](https://github.com/danielrosehill/Claude-Repo-Jumper), [Claude-Repo-Retrofitter](https://github.com/danielrosehill/Claude-Repo-Retrofitter)
- **Make-Agent-Friendly** — refactor a repo. [Make-Agent-Friendly](https://github.com/danielrosehill/Make-Agent-Friendly)
- **Repo Fresh Starter** — start new repo from current. [Repo-Fresh-Starter](https://github.com/danielrosehill/Repo-Fresh-Starter)
- **Github repo pruner** — [Github-Repo-Pruner](https://github.com/danielrosehill/Github-Repo-Pruner)
- **Github star organiser** — [Github-Star-Organiser](https://github.com/danielrosehill/Github-Star-Organiser)
- **WIP index adder** — add repo to specific index (e.g. works-in-progress). [WIP-Index](https://github.com/danielrosehill/WIP-Index)
- **Resource list / subindex / master index creator** *(no ref)*
- **Is-Vibe-Coded badge adder** — [Is-Vibe-Coded](https://github.com/danielrosehill/Is-Vibe-Coded)
- **Vibe-Coded disclosure adder** — [Vibe-Coded-Disclosure](https://github.com/danielrosehill/Vibe-Coded-Disclosure)
- **AI-Friendly badge (website footer)** — [AI-Friendly-Badge](https://github.com/danielrosehill/AI-Friendly-Badge)
- **AI-Human attribution adder** — [AI-Human-Attribution-Adder](https://github.com/danielrosehill/AI-Human-Attribution-Adder)
- **LLM attribution badges** — [LLM-Attribution-Badges](https://github.com/danielrosehill/LLM-Attribution-Badges)
- **Repo refactor to standard layout** — code/docs/planning at one level *(no ref)*
- **What-Reqs-Scanner** — remove venvs / scan reqs. [What-Reqs-Scanner](https://github.com/danielrosehill/What-Reqs-Scanner)
- **uv setup/convert** — convert other envs to uv *(no ref)*
- **No-Wheel-Inventions** — safeguard against reinvention. [No-Wheel-Inventions](https://github.com/danielrosehill/No-Wheel-Inventions)
- **Debug a project** *(no ref)*
- **Capture list of feature requests** *(no ref)*
- **Apply list of edit instructions** *(no ref)*
- **Bug report / feature request filer** *(no ref)*

## Planning / Diary / Sessions
- **Diary planner executor** — [Claude-Diary-Planner-Template](https://github.com/danielrosehill/Claude-Diary-Planner-Template)
- **End-of-day worklog** — with MCP integrations. [End-Of-Day-Worklog](https://github.com/danielrosehill/End-Of-Day-Worklog)
- **Session log capture** — JSON saved to `/planning/sessions` *(no ref)*
- **Project plan capture** — save to `planning/plans` with unique id *(no ref)*
- **Resume project plan** — by name or unique id *(no ref)*
- **Decision evaluation framework (ad-hoc call)** — [Claude-Decision-Evaluation-Framework](https://github.com/danielrosehill/Claude-Decision-Evaluation-Framework)

## Writing / Text / Prompts
- **AI Text Rewriting Toolbox** — many skills. [AI-Text-Rewriting-Toolbox](https://github.com/danielrosehill/AI-Text-Rewriting-Toolbox)
- **Anonymisation Assistant** — redaction/text anonymisation. [Anonymisation-Assistant](https://github.com/danielrosehill/Anonymisation-Assistant)
- **Smart PII redaction** *(no ref)*
- **Claude Redaction & Obfuscation** — [Claude-Redaction-And-Obfuscation](https://github.com/danielrosehill/Claude-Redaction-And-Obfuscation)
- **Text transformation index apply** — [Text-Transformation-And-Cleanup-Index](https://github.com/danielrosehill/Text-Transformation-And-Cleanup-Index)
- **STT basic cleanup** — apply to any transcript. [STT-Basic-Cleanup-System-Prompt](https://github.com/danielrosehill/STT-Basic-Cleanup-System-Prompt)
- **Text → SSML with prosody** — [Text-To-SSML-Generator](https://github.com/danielrosehill/Text-To-SSML-Generator)
- **Tone of voice distiller** — [My-Tone-Of-Voice](https://github.com/danielrosehill/My-Tone-Of-Voice)
- **System prompt factory** — [System-Prompt-Factory](https://github.com/danielrosehill/System-Prompt-Factory)
- **Prompt → structured output format** *(no ref)*
- **JSON conformity validator** *(no ref)*
- **Prompt refactoring skills** *(no ref)*
- **Personalised → general prompt** *(no ref)*
- **Spec starter** — break long prompt/voice note into spec. [Claude-Spec-Starter](https://github.com/danielrosehill/Claude-Spec-Starter)
- **Taxonomy generators** — [Taxonomy-Generators](https://github.com/danielrosehill/Taxonomy-Generators)
- **Shakespearean / joke text** — [Shakespearean-Text-Generators](https://github.com/danielrosehill/Shakespearean-Text-Generators)
- **Business↔casual** *(covered by built-in writing-editing skills)*
- **Basic spellcheck** *(no ref)*
- **Short-para + web readability audit** *(no ref)*
- **Awesome-list refactor** — non-awesome → awesome format *(no ref)*

## Transcripts / Audio / Voice
- **Diarised transcript assistant** — STT → cleaned + diarisation + redaction. [Diarised-Transcript-Assistant](https://github.com/danielrosehill/Diarised-Transcript-Assistant)
- **ASR training data chunker** — [ASR-Training-Data-Chunker](https://github.com/danielrosehill/ASR-Training-Data-Chunker)
- **Mic eval updater** — [One-Shot-Transcription-Microphone-Eval](https://github.com/danielrosehill/One-Shot-Transcription-Microphone-Eval)
- **Voice analyzer** — emotional tone + spectrogram. [Voice-Analyzer](https://github.com/danielrosehill/Voice-Analyzer)
- **Voice blog creator** — [Voice-Blog-Creator](https://github.com/danielrosehill/Voice-Blog-Creator)
- **Voice spec-driven development** — [Voice-Spec-Driven-Development-Demo](https://github.com/danielrosehill/Voice-Spec-Driven-Development-Demo), [Voice-To-Prompt-Pipeline](https://github.com/danielrosehill/Voice-To-Prompt-Pipeline)

## Resume / Job Search / Career
- **AI-readable resume** — update JSON/readable from PDF/docx. [AI-Resume](https://github.com/danielrosehill/AI-Resume)
- **Salary research** — ISR vs ROW. [Claude-Salary-Research-Agent](https://github.com/danielrosehill/Claude-Salary-Research-Agent)
- **Company research** — remote-friendliness assessments *(no ref)*
- **Job search strategist scaffold** — [Claude-Job-Search-Strategist](https://github.com/danielrosehill/Claude-Job-Search-Strategist)

## Research / Intelligence
- **Business idea refinement** — [Business-Idea-Refinement-Agent](https://github.com/danielrosehill/Business-Idea-Refinement-Agent)
- **Bias/censorship eval** — [Bias-Censorship-Eval-Tests](https://github.com/danielrosehill/Bias-Censorship-Eval-Tests)
- **Claude Dork** — platform-specific search strings. [Claude-Dork](https://github.com/danielrosehill/Claude-Dork)
- **Gmail search string generator** — filtering *(partial ref: [Gmail-Search-Strings](https://github.com/danielrosehill/Gmail-Search-Strings))*
- **Evidence bundling** — [Claude-Evidence-Assistant](https://github.com/danielrosehill/Claude-Evidence-Assistant)
- **Georeaction researcher** — global geopol init. [Claude-Georeaction-Researcher](https://github.com/danielrosehill/Claude-Georeaction-Researcher)
- **Geopol forecaster** — [Geopol-Forecaster-POC](https://github.com/danielrosehill/Geopol-Forecaster-POC)
- **Media monitor** — media mentions for brand/org. [Claude-Media-Monitor](https://github.com/danielrosehill/Claude-Media-Monitor)
- **OSINT investigator** — seed workspace + tools. [Claude-OSINT-Investigator](https://github.com/danielrosehill/Claude-OSINT-Investigator)
- **Ecosystem mapper** — [Ecosystem-Mapper](https://github.com/danielrosehill/Ecosystem-Mapper)
- **Tech research team** — stack research (SaaS, on-prem), Typst report gen. [Claude-Tech-Research-Team](https://github.com/danielrosehill/Claude-Tech-Research-Team)
- **GH components summariser** — gather options from GH + recommend *(no ref)*
- **Stack research skill** *(no ref)*
- **Local online shopping recs** — with preference docs *(no ref)*
- **Israeli tech shopping** — [Israeli-Tech-Shopping-MCP](https://github.com/danielrosehill/Israeli-Tech-Shopping-MCP)
- **Computer upgrade evaluator** — vs known hardware baseline *(no ref)*
- **Retailer whitelist updater** — [Retailer-Recommendations](https://github.com/danielrosehill/Retailer-Recommendations)
- **You-Might-Like recs** — [You-Might-Like-Agent](https://github.com/danielrosehill/You-Might-Like-Agent)
- **Movie recs** — based on preferences *(no ref)*

## Israel / Hebrew / Regional
- **SITREP generator** — [Israel-SITREP-Generation-Prompts](https://github.com/danielrosehill/Israel-SITREP-Generation-Prompts), [SITREP-Examples](https://github.com/danielrosehill/SITREP-Examples)
- **Israel news RSS feeds adder** — [Israel-News-RSS-Feeds](https://github.com/danielrosehill/Israel-News-RSS-Feeds)
- **Israel first aid adder** — [Israel-First-Aid](https://github.com/danielrosehill/Israel-First-Aid)
- **English↔Hebrew translation** — [English-Hebrew-Translation](https://github.com/danielrosehill/English-Hebrew-Translation)
- **Hebrew tech vocab updater** — [Hebrew-Tech-Vocab](https://github.com/danielrosehill/Hebrew-Tech-Vocab)
- **Google Fonts Hebrew downloader** — [Google-Fonts-Hebrew-Downloader](https://github.com/danielrosehill/Google-Fonts-Hebrew-Downloader)
- **Nice Hebrew fonts (favourites) downloader** — [Nice-Hebrew-Fonts](https://github.com/danielrosehill/Nice-Hebrew-Fonts)
- **Miklat lookup** — [Miklat-MCP](https://github.com/danielrosehill/Miklat-MCP)

## Linux Desktop / System Management
- **Linux Desktop Manager bundle** — [Claude-Linux-Desktop-Manager](https://github.com/danielrosehill/Claude-Linux-Desktop-Manager)
- **Linux Server Manager bundle** — [Claude-Linux-Server-Manager](https://github.com/danielrosehill/Claude-Linux-Server-Manager)
- **Linux desktop plugin** — [linux-desktop-plugin](https://github.com/danielrosehill/linux-desktop-plugin)
- **Install common Linux tools** *(no ref)*
- **Hardware inventory** — local machine + networked hardware params *(no ref)*
- **Hardware probe agent** — [Hardware-Probe-Agent-Template](https://github.com/danielrosehill/Hardware-Probe-Agent-Template)
- **Keyboard shortcut creator (Linux)** — [Claude-Keyboard-Scanner](https://github.com/danielrosehill/Claude-Keyboard-Scanner)
- **Bash aliases updater** *(no ref)*
- **yadm updater** *(no ref)*
- **Ansible updater** *(no ref)*
- **Slow boot debug / boot script assessor** *(no ref)*
- **Desktop cleanup** *(no ref)*
- **Snapper snapshots** — [Better-Safe](https://github.com/danielrosehill/Better-Safe)
- **OS sync agent updater** — [Claude-OS-Sync-Agent](https://github.com/danielrosehill/Claude-OS-Sync-Agent)
- **xev / device vendor+product ID identifier** *(no ref)*
- **Local secrets MCP** — [Local-Secrets-MCP](https://github.com/danielrosehill/Local-Secrets-MCP)
- **Ollama management** — recommend + pull models for workload *(no ref)*
- **Local AI options finder** *(no ref)*

## Proxmox / Servers / NAS / Home Lab
- **Proxmox manager** — [Claude-Proxmox-Manager-Template](https://github.com/danielrosehill/Claude-Proxmox-Manager-Template)
- **SBC server mgmt** — [Claude-Server-Mgmt-Template-SBCs](https://github.com/danielrosehill/Claude-Server-Mgmt-Template-SBCs)
- **Synology manager** — [Claude-Synology-Manager](https://github.com/danielrosehill/Claude-Synology-Manager)
- **NFS/SMB share lister** — [NFS-SMB-Share-Lister](https://github.com/danielrosehill/NFS-SMB-Share-Lister)
- **NFS / rclone mount manager** — update service file in repo *(no ref)*
- **MetaMCP admin** — [MetaMCP-Admin-MCP](https://github.com/danielrosehill/MetaMCP-Admin-MCP)
- **MetaMCP config repair** + repo update *(no ref)*
- **Home Assistant pruner / debugger** *(no ref)*
- **Local VM deploy** — standardised pattern with target folder *(no ref)*

## Filesystem / Organisation
- **FS organiser** — [Claude-File-Organiser-Super-Slash](https://github.com/danielrosehill/Claude-File-Organiser-Super-Slash), [Claude-FS-Organiser](https://github.com/danielrosehill/Claude-FS-Organiser)
- **Filesystem org plugin** — [filesystem-org-plugin](https://github.com/danielrosehill/filesystem-org-plugin)
- **Gdrive organiser** — [Claude-Gdrive-Organiser](https://github.com/danielrosehill/Claude-Gdrive-Organiser)
- **Batch optical archivist** — remote → locally divided folders. [Batch-Optical-Archivist](https://github.com/danielrosehill/Batch-Optical-Archivist)
- **Smartphone media importer** — DCIM mapping pattern *(no ref)*
- **UX570 importer** — [UX570-Importer](https://github.com/danielrosehill/UX570-Importer)
- **WhatsApp export unpacker** — [WhatsApp-Export-Unpacker](https://github.com/danielrosehill/WhatsApp-Export-Unpacker)

## Media / Images / Video / Audio Editing
- **Image editing plugin** — [image-editing-plugin](https://github.com/danielrosehill/image-editing-plugin)
- **Image-to-image prompt picker** — [Image-To-Image-Prompts](https://github.com/danielrosehill/Image-To-Image-Prompts)
- **Quick RMBG** — [Quick-RMBG](https://github.com/danielrosehill/Quick-RMBG)
- **Nano Banana tech diagrams** — [Nano-Banana-Tech-Diagram-Maker](https://github.com/danielrosehill/Nano-Banana-Tech-Diagram-Maker)
- **Whiteboard cleanup** — via nano banana MCP *(skill exists as fal-whiteboard-cleaner)*
- **ffmpeg / file format conversion / audio tasks skills** *(no ref)*
- **Kdenlive skill** *(no ref)*
- **Facial recognition photo organiser** *(no ref)*

## Email / Communication
- **Templated email sender** — with MCP + HTML template, incl. billing docs *(no ref)*
- **Gmail search strings** — [Gmail-Search-Strings](https://github.com/danielrosehill/Gmail-Search-Strings)
- **Smart spam filter config** — [Claude-Spam-Warrior](https://github.com/danielrosehill/Claude-Spam-Warrior)

## Documents / Reports
- **Typst concat** — outputs → Typst doc w/ typesetting *(no ref)*
- **Document this** — problem resolution documenter. [Claude-Document-This](https://github.com/danielrosehill/Claude-Document-This)
- **Bug catcher** — capture & document bugs. [Claude-Bug-Catcher](https://github.com/danielrosehill/Claude-Bug-Catcher)
- **Blog manager plugin** — [Claude-Blog-Manager](https://github.com/danielrosehill/Claude-Blog-Manager)
- **Personal blog updater** *(no ref)*
- **Blog post creator from arbitrary path** — personal/tech *(no ref)*
- **Medium post downloader** — [Medium-Post-Downloader](https://github.com/danielrosehill/Medium-Post-Downloader)

## Personal KM / Ideas / Context
- **Ideation pipeline** — capture idea into index. [Ideation-Pipeline](https://github.com/danielrosehill/Ideation-Pipeline)
- **Tech ideas capture** — save to target by format. [Tech-Ideas](https://github.com/danielrosehill/Tech-Ideas)
- **My LLM context repo updater** — public/private. [My-LLM-Context-Repo-Public](https://github.com/danielrosehill/My-LLM-Context-Repo-Public)
- **My LLM KM idea repo (WIP/public)** — [My-LLM-KM-Idea](https://github.com/danielrosehill/My-LLM-KM-Idea)
- **My AI stack docs updater** — [My-AI-Stack](https://github.com/danielrosehill/My-AI-Stack)
- **LLM workspace scaffolder** — [LLM-Workspace-Scaffolder](https://github.com/danielrosehill/LLM-Workspace-Scaffolder)
- **Tool search doc** — [Tool-Searches](https://github.com/danielrosehill/Tool-Searches)
- **Home inventory assistant** — [Home-Inventory-AI-Assistants](https://github.com/danielrosehill/Home-Inventory-AI-Assistants)
- **I'm Not Okay / mental health triage** — [Im-Not-Okay](https://github.com/danielrosehill/Im-Not-Okay)
- **Therapy tracker** — prep + debrief docs. [Claude-Therapy-Tracker](https://github.com/danielrosehill/Claude-Therapy-Tracker)
- **Obsidian fix note** *(no ref)*

## ISO / Reference
- **Currency notation → ISO** — [Useful-ISO-Standards-Reference](https://github.com/danielrosehill/Useful-ISO-Standards-Reference)
- **Country notation → ISO** — same ref
- **Continent adder** *(no ref)*
- **SQL type + boolean conformity** *(no ref)*

## Cloud / Deployment
- **Wasabi / S3 bucket lister + cleanup** *(no ref)*
- **Private apk/deb pipeline installer** *(no ref)*
- **Agent-style deploy to local VM** *(covered partly by existing deployments:agent-deploy skill)*
- **To-clone-or-not-to-clone** — new machine setup script. [To-Clone-Or-Not-To-Clone](https://github.com/danielrosehill/To-Clone-Or-Not-To-Clone)
