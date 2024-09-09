
# Crypto Currency

Una aplicacion creada con React.js para buscar el precio de cripto monedas utilizando una API gratuita para la obtencion de informacion


## Demo

https://crypto-currency-puce-omega.vercel.app/


## Run Locally

Clone the project

```bash
  git clone https://github.com/MiIeto/crypto-currency.git
```

Go to the project directory

```bash
  cd crypto-currency
```

Install dependencies

```bash
  pnpm install
```

Start the server

```bash
  pnpm run dev
  or
  pnpm dev
```


## API Reference

https://min-api.cryptocompare.com/

#### Get top 20 cripto currency

```https
  GET /data/top/mktcapfull?limit=20&tsym=USD
```

#### Get value of cripto currency in selected currency

```https
  GET /data/pricemultifull?fsyms=cryptocurrency&tsyms=currency
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `cryptocurrency`      | `string` | **Required**. Cripto currency selected |
| `currency`      | `string` | **Required**. Local currency selected |



## Tech Stack

React, Typescript, ZOD, Zustand


## Gratitudes

Muchas Gracias a **@codigoconjuan** por impartir el curso utilizado para crear este proyecto
