Fullstack Engineer Assessment
Durasi: 1–2 Days
Goal: Evaluate practical fullstack skills in an existing product team.
Stack 
Backend: Go ( Gin ), MySQL, Redis
Frontend: React Native, TypeScript
Scenario
You are joining an existing team maintaining a Task Management application. Implement requested features without breaking existing functionality.
Task 1 - Backend ( 40% )
- Add filtering (status, keyword, assignee, page, limit, sort)
- Implement PUT /api/tasks/{id}
- Implement soft DELETE /api/tasks/{id}
- Return consistent error responses.
Task 2 – Redis (15%)
Cache GET /api/tasks for 60 seconds. Invalidate cache after create/update/delete. Cache key must include query parameters.
Task 3 – Frontend (25%)
- Search input
- Status filter
- Pagination
- Edit modal
- Loading state
Task 4 – Bug Fixes (10%)
- Duplicate title should return HTTP 409 instead of 500
- Refresh list after update
- Hide soft-deleted tasks
Task 5 – Testing (10%)
Backend: Update, Search, Cache invalidation.
Frontend: At least one component test for search or task list.
Deliverables
Git repository, README, DB migration, Unit tests.
Evaluation
Go 35%, SQL 10%, Redis 15%, Frontend 20%, Testing 10%, Code Quality 5%, Documentation 5%.
