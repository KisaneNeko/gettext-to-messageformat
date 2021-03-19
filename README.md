# fork info

This was created because I needed to move JSON creation from the runtime to build process, to avoid
using Node.js functions in the react-native. Instead I created node script that creates json file,
and I modified `gettext-to-messageformat` to accept this JSON and only parse it to MessageFormat compatible object.

My API only exposes `parseJson` function.

Check original repo: https://github.com/messageformat/gettext-to-messageformat