# Resource catalog

Descriptions reviewed against upstream READMEs on October 30, 2026 Pacific. These are source reviews, not installation, security audits or runtime validation. All seven entries are optional and reference-only in this library.

## VengeanceUI

- Source: [Ashutoshx7/VengeanceUI](https://github.com/Ashutoshx7/VengeanceUI)
- Category: ui-components; kind: Component reference.
- Purpose: Copy-paste animated React/TypeScript UI components for landing pages, styled with Tailwind CSS and Framer Motion.
- Use and caveats: Landing-page inspiration; adapt selectively to the host app rather than installing the whole showcase.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `e772c14d0170d870e945c916eba7fab330eed012`.
- Adoption: reference-only; no installation or integration performed by this catalog.

## Motion

- Source: [motiondivision/motion](https://github.com/motiondivision/motion)
- Category: animation; kind: Runtime library reference.
- Purpose: Animation library for JavaScript, React and Vue, including gestures, springs, layout transitions and scroll-linked effects.
- Use and caveats: Consult version-matched documentation; adding a package or migrating imports is a separate integration decision.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `135269342568a3c3507accd14881c9bde2a7c090`.
- Adoption: reference-only; no installation or integration performed by this catalog.

## shadcn/ui

- Source: [shadcn-ui/ui](https://github.com/shadcn-ui/ui)
- Category: ui-components; kind: Component source and tooling reference.
- Purpose: Customizable, open-code components used to build a component library you own and maintain.
- Use and caveats: Review component source and dependencies before copying or running its CLI; copied code becomes project code.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `35657b37e0ef00aa7b477896d51a8fd0d5af8f49`.
- Adoption: reference-only; no installation or integration performed by this catalog.

## Context7

- Source: [upstash/context7](https://github.com/upstash/context7)
- Category: agent-tools; kind: Optional documentation integration.
- Purpose: Retrieves library documentation and examples for agents through an MCP server or CLI plus skills.
- Use and caveats: Requires deliberate client setup and possibly authentication. Cataloging it does not connect, install or authorize it.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `5d763258318ad99a8324faab59c6c6b2efd72350`.
- Adoption: reference-only; no installation or integration performed by this catalog.

## UI UX Pro Max

- Source: [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- Category: design-guidance; kind: Optional agent skill.
- Purpose: Design guidance and searchable resources for styles, palettes, typography and UX across platforms; includes design-system generation tooling.
- Use and caveats: Read as optional guidance. Skill installation/execution is separate and cannot override project instructions or approved designs.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `478738265751cf01352d1082c2e65be4467cd55c`.
- Adoption: reference-only; no installation or integration performed by this catalog.

## React Bits

- Source: [DavidHDev/react-bits](https://github.com/DavidHDev/react-bits); [official component demos](https://reactbits.dev/).
- Category: ui-components, animation; kind: Copyable React component and motion-effects reference.
- Purpose: Animated text, hover interactions, buttons, navigation, cards, backgrounds and other customizable React interface elements, with JavaScript/TypeScript and CSS/Tailwind variants.
- Use and caveats: Inspect each component's dependencies, bundle and rendering cost, accessibility, mobile behavior and reduced-motion support before adoption. The source uses an MIT + Commons Clause license: components may be used in applications, but cannot be resold or redistributed as standalone components; retain applicable notices. The optional shadcn registry/MCP integration needs separate configuration and approval.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `c19bf4af45a7217c0d1f77bcd183fb64f9594d64` and LICENSE.md blob `4069ce9d0ef1a712c93d6ce48ade5d5667e0f5ee`.
- Adoption: reference-only; no components installed, MCP configured, runtime testing or application integration performed.

## Motion Primitives

- Source: [ibelick/motion-primitives](https://github.com/ibelick/motion-primitives); [component demos and documentation](https://motion-primitives.com/docs).
- Category: ui-components, animation; kind: Copyable, customizable React motion components.
- Purpose: A collection of animated interface patterns and reusable components built with Motion and Tailwind CSS; useful for researching text effects, UI transitions and interactive controls.
- Use and caveats: Upstream describes the project as beta. Inspect each component's source, dependencies and compatibility before copying it into a project. Evaluate accessibility, reduced-motion behavior and mobile performance. MIT licensed; retain required copyright and license notice where applicable. Importing source or running its CLI is a separate integration step.
- Review: reviewed, 2026-10-30; evidence: upstream README blob `cbbeeee210f70418daf10ae495452b33ae08c044` and LICENCE.md blob `1a911b3bb726a0ceb00a6270853fdab52dff598d`.
- Adoption: reference-only; no component installation, runtime validation, new dependencies or integrations performed.
