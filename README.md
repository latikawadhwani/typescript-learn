# Compile file using tsc
# generates transpiled main.js
tsc main.ts

# Run file with
node main

# Run this to have compiler watch the file for any changes, compiler will create the updated transpiled files whenever any change to ts file is saved
tsc main --watch