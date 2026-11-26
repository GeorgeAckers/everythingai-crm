# EverythingAI — CRM

A private CRM for leads from the CRM Automation Diagnostic
(https://georgeackers.github.io/everythingai-crm-diagnostic/).

The page itself is public, but it holds no data. Leads live in a Supabase database. Row Level Security there
means the public key on this page and the diagnostic can only *add* leads. Only the signed-in admin can
read, update or delete them, and public sign-ups are turned off.

Sign in with your admin email and Supabase emails you a login link.
