# Starting a Research Project

Start with a clear research question, a runnable minimal example, and a concise README. Extend the structure as the project grows.

## Naming and discovery

Use a short, descriptive name with lowercase words separated by hyphens. Existing published tool names may retain their established spelling. Write a one-sentence description and add topics that match the actual contents.

## What the README should explain

1. What problem does the project address, and what data does it support?
2. How is it installed, and what software and hardware are required?
3. How can a reader run the smallest example and recognize a successful result?
4. Where do data and model weights come from, and what access conditions apply?
5. How can results be reproduced, cited, and reused?

Copy the [README template](repository-readme-template.md), fill in real details, and remove sections that do not apply.

## Suggested structure

```text
project-name/
├── README.md
├── LICENSE                # Choose according to the project's ownership and use
├── environment.yml        # Or requirements.txt, renv.lock, etc.
├── src/                   # Reusable code
├── scripts/               # Analysis entry points
├── examples/              # Small public or synthetic examples
├── docs/                  # Methods, parameters, and output explanations
└── tests/                 # Meaningful checks of important behavior
```

## Before publishing

- Run the documented example in a clean environment and record expected output.
- Document data versions, dependencies, key parameters, and random seeds.
- Review `.gitignore` and avoid committing credentials, temporary files, large raw datasets, or machine-specific paths.
- Select the project's license according to ownership and intended reuse; data and model weights may have separate terms.
- Provide accurate citations and version identifiers. Add a DOI only when one exists.

The organization supplies default contribution, conduct, support, security, and issue/PR templates. A project can override these with its own files. Licenses and CODEOWNERS must be configured separately for each repository.
