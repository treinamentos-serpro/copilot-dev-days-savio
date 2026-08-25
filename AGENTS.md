# AGENTS.md

## Mandatory development checklist

Before finishing any code change:

- [ ] Run linting/formatting checks if configured
- [ ] Run `dotnet build SocOps/SocOps.csproj`
- [ ] Run relevant tests, or `dotnet test` if the project has tests
- [ ] If behavior changed, run the app with `dotnet run --project SocOps/SocOps.csproj` and verify the UI still loads

## Project

This is a Blazor WebAssembly app, Soc Ops, for social bingo at in-person mixers.

Key docs:
- [README.md](README.md)
- [workshop/](workshop/)
- [docs/](docs/)

## Structure

- [SocOps/Components](SocOps/Components): UI
- [SocOps/Services](SocOps/Services): state and game logic
- [SocOps/Models](SocOps/Models): data models
- [SocOps/Data](SocOps/Data): prompt data
- [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css): shared utility styling

## Conventions

- .NET 10, Blazor WebAssembly
- Prefer small, focused edits aligned to existing component/service boundaries
- Keep public C# members in PascalCase
- Reuse utility classes in [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css) before adding custom CSS
- Check both UI and service layers when changing gameplay behavior
- Favor polished, intentional design; avoid generic, sparse styling

## Design guide

- Start with design tokens in [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css) (`:root` variables for color, spacing, borders, glow, and elevation) before creating component-specific styles.
- Preserve a cohesive visual direction per feature. Avoid mixing unrelated themes in the same flow.
- Prioritize strong typography hierarchy: clear display style for titles, readable body text for instructions, and consistent letter spacing for labels.
- Build atmospheric backgrounds using layered gradients/patterns instead of flat single-color canvases.
- Keep motion intentional and subtle by default. Prefer short transitions, restrained entry animations, and support `prefers-reduced-motion`.
- Ensure accessibility on every visual change: sufficient contrast, visible keyboard focus states, and tap targets that remain usable on mobile.
- Reuse and extend utility classes in [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css) instead of scattering one-off inline styles.
- Validate both desktop and mobile layouts whenever markup or spacing changes.

## Useful references

- [SocOps/Program.cs](SocOps/Program.cs)
- [SocOps/Services/BingoGameService.cs](SocOps/Services/BingoGameService.cs)
- [SocOps/Services/BingoLogicService.cs](SocOps/Services/BingoLogicService.cs)
- [SocOps/Components](SocOps/Components)
