# Twister Spinner

A full-screen spinner for the game Twister. Tap anywhere to spin, or turn on **Voice** and shout "Spin!" (any loud word works).

- **Voice:** listens for loud sounds and spins when it hears one. Use the **Sensitivity** slider so normal talking stays below the red line on the meter and a shout goes past it.
- **Read aloud:** reads each result out loud. The mic ignores the app's own voice.
- The screen stays on while the page is open, if the browser supports it.
- Space or Enter also spins.

It's one `index.html` with no dependencies. The mic only works over https or on localhost. To run it locally: `python3 -m http.server` and open http://localhost:8000.
