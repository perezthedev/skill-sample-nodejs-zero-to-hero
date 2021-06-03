# Zero to Hero: A comprehensive course to building an Alexa Skill

Support code for "Zero to Hero: A comprehensive course to building an Alexa Skill", an ASK training course in multiple languages. This is progressive code that starts from scratch and adds features on each module. The Learn more links below are suitable for learning (and teaching) how to code Alexa skills (see the README file on each module for video links and instructions on how to evolve the code departing from the previous module).

# Zero to Hero, Part 1: Alexa Skills Kit Overview

Development and Production Lambda Stages (AHS branches)
Lambda Dependencies (package.json, requires in code)
Handler as processor of incoming requests. Handler structure
Request Types (LaunchRequest, IntentRequest, SessionEndedRequest)
Skill Builder (custom vs standard) and its functions
Reflector (catch all intent handler)
Out-of-domain utterances (*)

# Zero to Hero, Part 2: Skill Internationalization (i18n), Interceptors & Error Handling

Multiple models per locale
Key/value string resources for i18n
Enriching handlerInput with t function via interceptor
Attribute manager as key/value store
High level attribute types (session(short term), persistent(long term))
Changing locale on Build tab and on Test tab (test both locales)

# Zero to Hero, Part 3: Slots, Slot Validation & Automatic Dialog Delegation

Slots explanation
Built in and custom slot types
Synonyms (minimal, we're not using synonyms, eg. January -> first month)
Required Slots & Prompts
Slot Validation
Auto-Delegate, Dialog Delegation Strategy
Utterance Profiler
Intent Confirmation
Basic Intent Chaining

# Zero to Hero, Part 4: Persistence

Session attributes
Persistent attributes
Persistence adapters (S3 and DynamoDB) / detect if lambda is Alexa hosted
Copy session attributes to and from persistent attributes via interceptors
Async/await
Session counter (to say eg. "welcome back")

# Zero to Hero, Part 5: Accessing ASK APIs

Service API (User Profile API - given name)
Settings API (timezone)
SSML (speechcons and audio files)
Array capable localisation interceptor
String replacement with plurals support
Learn more

# Zero to Hero, Part 6: Reminders API

Reminders API
AMAZON.SearchQuery
Intent Confirmation (again)

# Zero to Hero, Part 7: Accessing External APIs

Fetch external API (async/await)
Progressive Response

# Zero to Hero, Part 8: Alexa Presentation Language (APL), Part 1

APL RenderDocument and APL Directive
APL Databinding and APL Authoring Tool
APL Styles, Layouts and ViewPorts
APL Transformers (Text to Hint)
Home Cards
Media storage in Alexa-hosted Skills
Learn more

# Zero to Hero, Part 9: Alexa Presentation Language (APL), Part 2

APL Authoring Tool
APL Layouts & Sequences
APL Transformers (Text to Hint)
APL Touch Wrapper

# Zero to Hero, Part 10: The ASK Command Line Interface (CLI)

Configuring the ASK-CLI with personal AWS account support
Cloning an Alexa Hosted Skill
Editing a skill in code and deploying the skill

# Zero to Hero, Part 11: Publishing

Distribution tab in developer console
Skill metadata for publication
Submitting a skill for certification
