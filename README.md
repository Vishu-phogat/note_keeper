Installation:


1. cd note_keeper
2. npm install
   
3. Tell Node to use the legacy OpenSSL provider

On Unix-like (Linux, macOS, Git bash, etc.):
export NODE_OPTIONS=--openssl-legacy-provider

On Windows command prompt:
set NODE_OPTIONS=--openssl-legacy-provider

On PowerShell:
$env:NODE_OPTIONS = "--openssl-legacy-provider"

4. npm start
