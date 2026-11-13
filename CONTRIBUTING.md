# Contributing

## Rules

- One script per pull request.
- Include the exported Flip command JSON and a short README entry.
- No `sudo`, no password prompts, no network callbacks, no telemetry.
- No destructive defaults. Deleting files, changing network settings, or modifying system security requires an explicit warning and confirmation in the script.
- Do not include personal data, API keys, cookies, or absolute paths to your home directory.
- Explain what the script changes and how to undo it.

## Review

A maintainer will inspect the script, test it in a disposable macOS account where possible, and either merge it or request changes.
