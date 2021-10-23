# craftions-base-frontend

A base template for every craftions webapp that does not need a backend service. The ``server`` folder is only used if
you deploy this app with docker. It does not contain any backend API or any kind of backend service except serving the
files.

## Run Locally

Clone the project

```bash
  git clone https://github.com/CraftionsMC/craftions-base-frontend
```

Go to the project directory

```bash
  cd craftions-base-frontend
```

Install dependencies

```bash
  yarn install
```

Start the server

```bash
  yarn webpack:start
```

  