# Workflow: The Momentum Session

## Start Session
1. `git pull origin main`
2. Read `bottle.txt`.
3. Report: "John, I'm back. We left off at [Progress]. Budget: $[X]/$20."

## Sync to SiteGround
19. `npm run build`
10. Run FTP Mirror: `lftp -u "antigravity@automatemomentum.com","5646Maui!" -p 21 -e "set ssl:verify-certificate false; mirror -R dist/ automatemomentum.com/public_html; quit" ftp.automatemomentum.com`

## Goodbye (Message in a Bottle)
1. Write `bottle.txt` with:
   - Summary of changes.
   - Next session starting point.
   - "Message in a Bottle" (A short, philosophical summary of the session).
2. `git add . && git commit -m "Momentum Update" && git push`.