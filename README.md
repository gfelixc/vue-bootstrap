Dev

```
docker run -i -t --rm -p 8080:8080 -v ${PWD}:/usr/src/app -w /usr/src/app node sh -c "npm install && npm run dev"
```