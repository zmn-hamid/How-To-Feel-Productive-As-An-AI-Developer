---
name: article-translation
description: Translate long-form articles between languages while preserving voice, meaning, structure, and audience accessibility. Use when asked to translate an article or document, especially when source files and repository links should be maintained.
---

# Article Translation

Produce a faithful, readable translation of this repository’s article, *How To Feel Productive As An AI Developer*, into any requested target language. Treat translation as both a writing task and a careful file-maintenance task. This skill is tailored to this article and repository; the target language is not fixed.

## Project context

- The English source is `How To Feel Productive As An AI Developer.md`. Keep it unchanged.
- The article is a personal, candid essay for software developers about the psychological and practical effects of AI-assisted development. Its voice is conversational, opinionated, sometimes humorous, blunt, and deliberately informal. Preserve that voice rather than polishing it into academic prose.
- The article mixes personal experience, advice, criticism, technical concepts, code and file names, product/tool names, quotations, links, and references. Keep those details faithful and usable.
- The main translation deliverable is a separate Markdown file whose filename is the article title translated into the target language. Do not use a language-code suffix unless the user requests it or repository conventions require it.
- Update the Farsi-version line in `README.md` to point to the translation using a valid link. For translations into other languages, add a clearly labeled README link when appropriate; preserve existing entries.
- Put a short AI-translation disclaimer at the very top of every translated article, before its title. Translate the disclaimer into the target language. It must clearly say that AI produced the translation and it may not be perfect. Do not omit it unless the user explicitly asks to remove it.

## Workflow

1. **Identify the source and target.**
   - Use the source text or file the user specifies. If the request relies on repository context but does not name a file, inspect the project to identify the likely article and any existing translation.
   - Confirm the target language from the request. Ask a concise question if the source or target is materially ambiguous.
   - Keep the source document unchanged unless the user explicitly asks to replace or edit it.

2. **Assess voice and audience.**
   - Read the full article before translating.
   - Identify its tone, register, intended readers, point of view, rhetorical style, and use of humor, informality, technical detail, or sensitive language.
   - Preserve the author's attitude and emphasis. Do not make the writing more formal, polite, promotional, or neutral than the source without instruction.
   - If the user asks to see the process, give a brief, useful summary of the style approach and key terminology decisions. Do not provide hidden chain-of-thought; provide conclusions, not private reasoning.

3. **Plan terminology.**
   - Identify technical, uncommon, ambiguous, and recurring terms, names, idioms, and culturally specific references.
   - Choose target-language wording based on meaning and likely reader comprehension, not word-for-word similarity.
   - Prefer established, understandable terminology. If a literal technical equivalent is obscure or misleading, use a clear phrase; retain the original term in parentheses where useful.
   - Use one translation consistently for a concept unless the context requires a distinction. Preserve product names, identifiers, code, commands, filenames, URLs, and quoted labels when translating them would impair accuracy or usability.
   - Preserve the source's degree of certainty, criticism, humor, and emotional force. Do not silently omit or sanitize difficult material; adapt only when requested or necessary for a clear, responsible translation.

4. **Translate the complete article.**
   - Preserve headings, paragraph boundaries, lists, quotations, emphasis, links, code spans, and other meaningful Markdown structure.
   - Translate idioms by their intended meaning and effect, rather than mechanically. Keep examples, claims, and references faithful to the source.
   - Do not summarize, add new claims, or leave sections untranslated unless the user asks for that.
   - Use natural, idiomatic prose in the target language while retaining the author's distinct voice.

5. **Create or update files when appropriate.**
   - When working in a repository, create a separate translation file unless the user requests an in-place replacement. Follow existing project conventions where available.
   - If no convention exists, use a clear filename in the target language and a conventional Markdown extension. Avoid an unexplained language-code suffix when the user requests a target-language filename.
   - Preserve the original file. Add or update a README or index link only when one exists and the translation belongs there.
   - Always place a brief disclaimer at the very top of the translated article, before the title, in the target language. State that the translation was produced by AI and may not be perfect. Do not present it as human-certified.

6. **Review and verify.**
   - Compare the translation against the source section by section. Check for missing or duplicated material, mistranslated negation or qualifiers, inconsistent terminology, awkward literal phrasing, and altered claims or tone.
   - Verify that headings, lists, quotations, code, names, and links survived intact. Check any updated README link against the actual filename, including spaces and non-ASCII characters.
   - Inspect the final change/status to ensure only intended files were changed. Run relevant checks if the repository provides them.

7. **Report completion.**
   - State which file was created or changed and mention any link updates or verification performed.
   - Be concise. Do not claim a review, test, or verification that was not actually done.

## Constraints

- Preserve meaning and authorial voice over literal word matching.
- Prefer clarity without flattening the author's style or changing their stance.
- Never silently omit sections or modify the original article.
- Keep repository changes limited to the requested translation and directly related navigation or documentation.
