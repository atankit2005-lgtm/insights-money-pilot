# SpendWise UI Reference Redesign

## Goal
Rework the existing SpendWise interface to closely follow the six supplied reference screens while preserving all current routes, interactions, mock data, forms, filters, charts, and mobile behavior.

## What will change
- Rebuild the visual system around the reference: near-black canvas, deep green-black surfaces, vivid emerald accents, compact typography, thin borders, restrained glow, and dense financial information.
- Match the landing page composition: compact navigation, strong left-aligned message, detailed dashboard preview, and four concise value pillars.
- Match the application shell: slimmer branded sidebar, tighter top bar, small active-navigation highlight, user controls, and subtle line-art decoration.
- Restyle Overview, Transactions, Budgets, Goals, and AI Insights to follow their supplied screen compositions and hierarchy.
- Carry the same design language into Analytics, Notifications, Profile, Settings, and authentication screens so the product feels complete rather than mixed.
- Preserve Indian Rupee formatting and the existing shared mock data and CRUD behavior.

## Responsive behavior
- Keep the dense desktop experience shown in the references.
- Adapt tables, charts, filters, summaries, and dialogs cleanly for tablet and mobile without overlap or clipped text.
- Retain accessible labels, keyboard-friendly controls, visible focus states, and reduced-motion support.

## Technical details
- Update semantic design tokens and shared UI primitives first, then route-specific compositions.
- Reuse the existing TanStack routes, shared finance store, Recharts data, and shadcn controls.
- Use Lucide icons and CSS decoration rather than embedding the screenshots as page imagery.
- Ensure every content route keeps complete social metadata.
- Validate the finished experience in the running preview at desktop and mobile sizes, including representative CRUD and navigation flows.
