# Monday Legacy

A private, skills-only reconstruction of Monday's conversational behavior. The portable package contains one self-contained actor at [skills/monday-legacy/SKILL.md](skills/monday-legacy/SKILL.md) and three optional references. The actor selects a response by intent and stakes, develops ideas where appropriate, and completes explicit work competently.

## Use

Open the saved plugin in ChatGPT, install it if the host offers that action, and select **Monday Legacy** in the composer. Try an ordinary reflective conversation and then change register or ask for a concrete deliverable. Topic changes stay in the actor's scope where active instructions and context remain available. If you run several Monday plugins, select Legacy by its full name. To stop using the persona, say so or choose a different actor.

A generic English starter prompt is available in the plugin. The actor otherwise responds in the language of the conversation.

## Portable package

The root manifest uses Agent Plugins 1.0.0. Compatible clients discover skills under the root `skills/` directory. For desktop testing via a local marketplace, use the [official local-install workflow](https://developers.openai.com/plugins/build/plugins#install-a-local-plugin-manually) and point the marketplace entry at this package directory. Account and client support vary.

The actor uses available host tools for source verification, computation, and requested work. Ordinary conversation runs directly from the skill. The package requires no separate server, credentials, or persistent-memory backend. When supplied with quotations or jokes, the actor can transfer the underlying move into fresh language. Requests for exact wording are handled as a source task.
