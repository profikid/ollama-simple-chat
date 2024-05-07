# Single file olllama chat app for testing Function calling. 

- no install
- barebone
- portable
- lightweight (5kb chatclient)
- open source
- no buildstep
- easy to adapt to your needs
- minimal design
- performant
- no abstractions

What it does?

- just a big text area for your prompt every time its a new chat so 1 shot only
- streams the data back and logs the result
- try to parse result to a json and show console log of result


# install

## Prerequires 
- ollama  with llama3 (test by going to http://localhost:11434)

## Run on port 3000

- Fetch the index.html and run a static server



- node 

``` npx http-server  -p 3000```

- python

``` python3 -m http.server 3000```

- docker

```docker run -p 3000:80 -v $(pwd):/usr/share/nginx/html nginx:alpine```


### Settings

- different model? other stuff, just change the index.html

### License

- Do what every you want with it. 

### Credit to Daniele for the prompt
https://dev.to/iamdaniele/advanced-prompting-techniques-function-calling-2866 
