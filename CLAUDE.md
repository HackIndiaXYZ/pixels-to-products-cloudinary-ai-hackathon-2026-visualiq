# CLAUDE.md

## Project goal
VISUALIQ is an AI-powered product intelligence and visual commerce studio.
The project analyzes product images and generates useful product intelligence for a commerce workflow.
Prioritise a working, reliable demo over unnecessary extra features.

## Stack
- Frontend: web application
- AI: Gemini-powered image analysis
- Product image storage and delivery: Cloudinary
- Fallback image analysis: AWS Rekognition
- Backend/API functionality as implemented in the repository
- Git and GitHub for version control

## Repository rules
- Treat this repository as the source of truth.
- Inspect existing code before making changes.
- Keep changes focused on the requested task.
- Do not make broad architecture changes without asking first.
- Do not delete working project functionality.
- Do not modify unrelated files.

## Commands
Use the actual commands available in package.json before claiming that a command exists.
- Install dependencies: use the repository's package manager and package.json.
- Start the application: use the existing development command in package.json.
- Build the project: use the existing build command in package.json.
- Do not claim tests or builds passed unless the corresponding command was actually run.

## Code conventions
- Keep components and functions focused and readable.
- Reuse existing project utilities and components when appropriate.
- Follow the coding style already used in the repository.
- Avoid unnecessary dependencies.
- Keep user-facing error messages clear.

## Environment and secrets
- Environment variables may be required for AI and cloud services.
- Never read, print, expose, or commit real secrets from .env files.
- Use placeholder variable names in documentation.
- Never expose API keys, tokens, passwords, or credentials.

## Git workflow
- Check git status before changing files.
- Review git diff before committing.
- Keep commits focused and descriptive.
- Do not rewrite or delete unrelated Git history.

## Claude Code workflow
- Understand the existing project before editing files.
- Ask before making broad changes.
- Prefer small, verifiable changes.
- Explain what changed after completing a task.
