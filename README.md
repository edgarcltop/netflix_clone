# netlify-fauna-todo

Netlify Identity + FaunaDB app with most recent versions of FaunaDB client and React.


- Demo: https://cocky-almeida-4df361.netlify.com/



Manual deploy/Local development

1. Deploy to Netlify and run `netlify addons:create fauna`
1. look for the given server secret from the netlify addon, and copy it
1. run `export FAUNADB_SERVER_SECRET=your_secret_here`

Features of note:

- Netlify Identity Authentication
- `useFauna` React Hook
