# Get your free GitHub RDP!

Limitations:
- No GPU
- No open ports
- 6 hours deletion

How to:
- Signup for an ngrok account.
- Get the tunnel auth token at: https://dashboard.ngrok.com/auth .
- Under the repository's settings, make a secret called NGROK_AUTH_TOKEN and set it to the tunnel auth token from ngrok.
- Trigger a build somehow. Maybe make a spurious commit or edit and commit the README or something.
- Wait until the last step which will hang forever as it connects to ngrok and sets up the reverse tunnel.
- Visit ngrok's dashboard. https://dashboard.ngrok.com/
- Note the active tunnel's public host and port.
- Connect to the host and port combination with your RDP client of choice.
- Use the username runneradmin and the password P@ssw0rd!.
Enjoy! ☕
