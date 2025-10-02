# Mintlify documentation

## Working relationship

- You can push back on ideas-this can lead to better documentation. Cite sources and explain your reasoning when you do so
- ALWAYS ask for clarification rather than making assumptions
- NEVER lie, guess, or make up information

## Project context

- Format: MDX files with YAML frontmatter
- Config: docs.json for navigation, theme, settings
- Components: Mintlify components

## Content strategy

- Document just enough for user success - not too much, not too little
- Prioritize accuracy and usability of information
- Make content evergreen when possible
- Search for existing information before adding new content. Avoid duplication unless it is done for a strategic reason
- Check existing patterns for consistency
- Start by making the smallest reasonable changes

## Frontmatter requirements for pages

- title: Clear, descriptive page title
- description: Concise summary for SEO/navigation

## Writing standards

- Second-person voice ("you")
- Prerequisites at start of procedural content
- Test all code examples before publishing
- Match style and formatting of existing pages
- Include both basic and advanced use cases
- Language tags on all code blocks
- Alt text on all images
- Relative paths for internal links
- NEVER use `{" "}` JSX space syntax in MDX files - use regular spaces instead

## Tone and voice guidelines

### Brand personality
- **Welcoming & approachable**: Use warm, friendly language that makes users feel comfortable
- **Professional but relaxed**: Maintain credibility while being conversational and approachable
- **Helpful & supportive**: Position as a helpful guide and friendly companion, not just a manual
- **Confident but humble**: Share expertise without being condescending
- **Approachable but trustworthy**: Feel friendly and casual while maintaining reliability and professionalism

### Writing tone specifics
- **Conversational**: Write like you're talking to a colleague, not lecturing
- **Encouraging**: Use positive, supportive language that builds confidence
- **Clear & direct**: Get to the point quickly without unnecessary complexity
- **Empathetic**: Acknowledge when things might feel overwhelming or confusing
- **Personal**: Use "we" when referring to CurrentClient team, "you" for the user
- **Warm but professional**: Inject personality while staying helpful and credible
- **Relaxed confidence**: Sound knowledgeable but not stuffy or overly formal

### Language patterns to use
- "Really nice to have you here!" instead of "Welcome"
- "You're probably looking to..." instead of "This document covers..."
- "We've packed our help center..." instead of "This help center contains..."
- "So, let's dive in..." for smooth transitions
- "Ready to get started?" for engaging section headers
- "We consider these pages as an extension of our product" (shows care and investment)
- "Here's what we'll walk you through..." instead of formal introductions
- "We'll get you sorted!" instead of "We will assist you"
- "Pretty straightforward" instead of "Simple"
- "No worries" to reassure users
- "at whatever pace feels right for you" for user empowerment
- Use contractions naturally (you're, we'll, don't, can't, you'd)
- Keep exclamations moderate and genuine

### Avoid
- Corporate jargon or overly formal language
- Passive voice when active voice is clearer
- Assumptions about user knowledge level
- Intimidating technical terminology without explanation
- Cold, impersonal instructions
- Being overly playful or trying too hard to be fun
- Excessive exclamations or forced enthusiasm
- Overly casual language that undermines professionalism
- Slang that might not be universally understood
- Being too casual about serious compliance/security topics

### Structure preferences
- Lead with empathy and understanding
- Use friendly transitions between sections
- End sections with encouragement or next steps
- Include reassuring statements about support availability

## Git workflow

- NEVER use --no-verify when committing
- Ask how to handle uncommitted changes before starting
- Create a new branch when no clear branch exists for changes
- Commit frequently throughout development
- NEVER skip or disable pre-commit hooks

## Do not

- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification
