# Chatterbox Lab TODO

- [x] Complete the Message model in `server/models.py` with body, username, created_at, updated_at columns and defaults
- [x] Run `flask db init` in server directory
- [x] Run `flask db revision --autogenerate -m'your message'` in server directory
- [x] Run `flask db upgrade` in server directory
- [x] Run `python seed.py` in server directory to seed database
- [x] Implement GET /messages route in `server/app.py`
- [x] Implement POST /messages route in `server/app.py`
- [x] Implement PATCH /messages/<int:id> route in `server/app.py`
- [x] Implement DELETE /messages/<int:id> route in `server/app.py`
- [x] Update fetch URLs in `client/src/components/App.js` from port 4000 to 5555
- [x] Update fetch URLs in `client/src/components/NewMessage.js` from port 4000 to 5555
- [x] Update fetch URLs in `client/src/components/Message.js` from port 4000 to 5555
- [x] Update fetch URLs in `client/src/components/EditMessage.js` from port 4000 to 5555
- [x] Run `pytest -x` in server directory to verify tests pass
