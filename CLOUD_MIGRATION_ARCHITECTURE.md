# CRM Cloud Architecture

The production entrypoint authenticates with Supabase and embeds the preserved CRM UI from `legacy.html`.

CRM data is stored in `crm_profiles`, `crm_customers`, and `crm_properties` with RLS by `auth.uid()`.

The legacy UI remains preserved so the business UI can evolve without losing the original implementation.
