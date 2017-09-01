# 0xNIL factory

Contracts for the NIL token and the related free distribution

More info at [0xNIL.org](http://0xNIL.org)

### Testing

Install dependencies, and `testrpc` and `truffle`:

```
npm install
npm install -g testrpc truffle

```

Run `testrpc` generating 20 accounts:
```
testrpc -a 20 -g 20000000000 -l 0x47E7C4
```

Run the tests:
```
truffle test

```
