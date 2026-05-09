# SignalDesk frontend

Implementation pending.

## Planned routes (Next.js App Router)

Add `layout.tsx`, `page.tsx`, and downstream components under `app/` to activate each segment.

| Path | Planned directory |
|------|-------------------|
| `/` | `app/page.tsx` (not yet scaffolded — needs default layout + landing page) |
| `/login` | `app/login/` |
| `/register` | `app/register/` |
| `/dashboard` | `app/dashboard/` |
| `/datasets/new` | `app/datasets/new/` |
| `/datasets/[id]/mapping` | `app/datasets/[id]/mapping/` |
| `/datasets/[id]/processing` | `app/datasets/[id]/processing/` |
| `/datasets/[id]` | `app/datasets/[id]/` |
| `/themes/[id]` | `app/themes/[id]/` |
| `/briefs/[id]` | `app/briefs/[id]/` |

## Planned API client modules

Located under `lib/api/` (empty placeholders).
