## Description

Fail to navigate to other route by using `useRouter().push` in nested route

## Setup

```bash
pnpm i
npm run dev
```

## Reproduce

1. go to the route `/about/child`
2. click the test button, which suppose to trigger navigation and goes to `/`
3. no navigation triggered, and console prints out following messages.
   ![](2022-09-21-12-28-12.png)

## Index

- the test button logic: [ChildView.vue](./src/views/AboutView/ChildView.vue)
- the router: [index.js](./src/router/index.js)
- online demo
