# Codespaces structure repair

This package restores the intended Next.js repository layout.

Expected source layout:
- `src/app`
- `src/components`
- `src/lib`
- `src/types`

The previous GitHub upload accidentally flattened these folders into the repository root.

The ESLint `react-hooks/set-state-in-effect` rule is temporarily disabled only while
prototype browser-storage hydration remains in use. It should be re-enabled after
the relevant screens are moved to Supabase/server-backed state.
