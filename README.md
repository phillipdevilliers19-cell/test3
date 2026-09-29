# Vesco Intelligence (VI) Internal

## VI Scraper

The Add Application area now includes **VI Scraper**. It accepts:
- A web URL (best-effort browser scrape, with reader fallback for pages that block direct access)
- A PDF upload

The scraper extracts application text, maps it into the VI application fields, captures available webpage images, and renders useful PDF pages as application photos. The extracted record is shown for quick review/editing before it is added to the Library.

This version still uses browser localStorage for application data. A future shared database/storage layer can replace that without changing the application UI.


## v28 Users & Roles
- Local user profiles with roles and granular permissions
- Built-in roles: Super Admin, Admin, Engineer, Contributor, Sales, Viewer
- Custom roles can be created and permission sets edited
- User activation/deactivation and role assignment
- Admin backup includes users and roles
- Permissions gate major navigation and create/edit/delete/import/export actions
- This is a client-side role system until real authentication/backend is connected; it is not a security boundary.
