# Invoice

This is an example Redwood app, implementing a very minimal todo application.
Features you can see in action here:

- Redwood Cells (see TodoListCell.js).
- Optimistic GraphQL response with Apollo (see AddTodo.js).
- SVG loader (see Check.js)
- StyledComponents usage (and stylistic approach)

## Getting Started

### Setup

We use Yarn as our package manager. To get the dependencies installed, just do
this in the root directory:

```terminal
yarn
```

Set up the database and generate the database client:

```terminal
yarn redwood db up
yarn redwood db generate
```

### Fire it up

```terminal
yarn redwood dev
```

Run `yarn redwood open` to open your browser on `http://localhost:8910`.

Browse to `http://localhost:8910` to see the web app. Lambda functions run on
`localhost:8911` but are proxied via `localhost:8910/api/functions/*`.
