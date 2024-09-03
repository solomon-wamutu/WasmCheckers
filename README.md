## How to Build and Host Checkers.wasm

Build it using \`wat2wasm\`:

\`\`\`
/path/to/wabt/bin/wat2wasm checkers.wat -o checkers.wasm
\`\`\`

Host this file behind a simple Python web server:

\`\`\`
python3 -m http.server
\`\`\`
