# Happy Birthday: A skill for our ASK Developer Training Course

Support code for ASK Developer Training Course for multiple locales. This is progressive code that starts from scratch and adds features on each module. The Learn more links below are suitable for teaching how to code Alexa skills (see the README file on each module for instructions on how to evolve the code departing from the previous module).

## Part 1 - Alexa-Hosted Skills (preset - Hello World)

1. Development and Production Lambda Stages (AHS branches)
2. Lambda Dependencies (package.json, requires in code)
3. Handler as processor of incoming requests. Handler structure
4. Request Types (LaunchRequest, IntentRequest, SessionEndedRequest)
5. Skill Builder (custom vs standard) and its functions
6. Reflector (catch all intent handler)
7. Out-of-domain utterances (*)

[Learn more](./01)

## Part 2 - Skill Internationalization (i18n) and Interceptors

1. Multiple models per locale
2. Key/value string resources for i18n
3. Enriching handlerInput with t function via interceptor
4. Attribute manager as key/value store
5. High level attribute types (session(short term), persistent(long term))
6. Changing locale on Build tab and on Test tab (test both locales)

[Learn more](./02)

## Part 3 - Slots, Slot Validation and Automatic Dialog Delegation

1. Slots explanation
2. Built in and custom slot types
3. Synonyms (minimal, we're not using synonyms, eg. January -> first month)
4. Required Slots & Prompts
5. Slot Validation
6. Auto-Delegate, Dialog Delegation Strategy
7. Utterance Profiler
8. Intent Confirmation
9. Basic Intent Chaining

[Learn more](./03)

## Part 4 - Persistence

1. Session attributes
2. Persistent attributes
3. Persistence adapters (S3 and DynamoDB) / detect if lambda is Alexa hosted
4. Copy session attributes to and from persistent attributes via interceptors
5. Async/await
6. Session counter (to say eg. "welcome back")

[Learn more](./04)

## Part 5 - Accessing ASK APIs

1. Service API (User Profile API - given name)
2. Settings API (timezone)
3. SSML (speechcons and audio files)
4. Array capable localisation interceptor
5. String replacement with plurals support

[Learn more](./05)

## Part 6 - Reminders API

1. Reminders API
2. AMAZON.SearchQuery
3. Intent Confirmation (again)

[Learn more](./06)

## Part 7 - Accessing External APIs

1. Fetch external API (async/await)
2. Progressive Response

[Learn more](./07)

## Part 8 - Alexa Presentation Language (I)

1. APL RenderDocument and APL Directive
2. APL Databinding and APL Authoring Tool
3. APL Styles, Layouts and ViewPorts
4. APL Transformers (Text to Hint)
5. Home Cards
6. Media storage in Alexa-hosted Skills

[Learn more](./08)

## Part 9 - Alexa Presentation Language (II)

1. APL Authoring Tool
2. APL Layouts & Sequences
3. APL Transformers (Text to Hint)
4. APL Touch Wrapper

[Learn more](./09)

## Part 10 - ASK Command Line Interface (CLI)

1. Configuring the ASK-CLI with personal AWS account support
2. Cloning an Alexa Hosted Skill
3. Editing a skill in code and deploying the skill

[Learn more](./10)

## License

This library is licensed under the Amazon Software License
