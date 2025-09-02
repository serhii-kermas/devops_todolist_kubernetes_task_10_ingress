Open http://localhost in a browser.
Verify no 404 errors in the browser console:
Open DevTools → Console, reload the page, ensure there are no 404 network errors.
(Optional) Verify service wiring:
kubectl get svc -n todoapp and confirm todoapp-service on port 80.