# ELEVATE-SDE-Task-4 – CredVault Full Stack

Final full-stack integration of the ELEVATE Task 2 frontend with the Task 3 backend.

## Technology
- Frontend: HTML, CSS, JavaScript (Task 2 UI)
- Backend: Node.js + Express
- Database: SQLite
- Authentication: JWT + bcryptjs

## Run locally
```bash
cd backend
npm install
npm start
```
Open http://localhost:5000

## Admin
Username: `admin`
Password: `admin`

## Integrated flow
1. Request Certificate → POST `/api/applications`
2. Track Application → GET `/api/applications/track/:applicationId`
3. Verify Certificate → GET `/api/certificates/verify/:certificateId`
4. Admin Login → POST `/api/admin/login`
5. Applications → GET `/api/admin/applications`
6. Approve → PATCH `/api/admin/applications/:applicationId/approve`
7. Reject → PATCH `/api/admin/applications/:applicationId/reject`
8. Certificates → GET `/api/admin/certificates`
9. Revoke → GET `/api/admin/certificates/:certificateId/revoke`

## Submission
Repository name: `ELEVATE-SDE-Task-4`

Add screenshots and the screen-recorded demo video link here before submission.
