# Smoke / Sanity / Regression Checklists (Starter)

 Smoke (run on each new build)
- Login/logout as Admin succeeds
- Left nav loads modules (Admin, PIM, Leave, Time, Recruitment, Performance, Dashboard)
- Open PIM > Employee List without errors
- Open Leave > Apply and Leave List without errors
- View My Info page without errors

 Sanity (after module fixes)
- Admin > User Management: Add user, search user, toggle status
- PIM: Add employee, edit details, upload/delete attachment
- Leave: Apply leave (ESS), Approve/Reject (Admin)
- Time: Submit timesheet, Approve (if applicable)
- Recruitment: Add candidate, change status

 Regression (end of cycle)
- Re-run all High/Medium priority cases across modules
- Validate role-based access (Admin vs ESS)
- Input validation (required fields, boundary values, special chars)
- Sorting, filtering, pagination in lists
- Basic accessibility: keyboard navigation, form labels present
