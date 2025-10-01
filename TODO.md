# Chatterbox Lab Implementation Progress

## Completed Tasks
- [x] Update Message model with required attributes (body, username, created_at, updated_at)
- [x] Implement GET /messages route (return all messages ordered by created_at)
- [x] Implement POST /messages route (create new message)
- [x] Implement PATCH /messages/<int:id> route (update message body)
- [x] Implement DELETE /messages/<int:id> route (delete message)
- [x] Initialize database with flask db init
- [x] Generate migration with flask db revision --autogenerate
- [x] Run migration with flask db upgrade
- [x] Seed database with python seed.py
- [x] Run tests with pytest -x (all 8 tests passed)
- [x] Start Flask server on port 5555
- [x] Install React dependencies (npm install completed)
- [x] Start React development server (running on http://localhost:3000)
- [ ] Test routes from React frontend
