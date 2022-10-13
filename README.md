# tebim_livereload

## How to use it?

1. Insert this to your html file
```javascript 
document.write('<script src="http://' + (location.host || 'localhost').split(':')[0] +
  ':35729/livereload.js?snipver=1"></' + 'script>');
```
2. Edit docker-compose.yml file, change `/your/watch/directory` to Your path (with source code), for example: `/Users/janek/Desktop/tebim/live_reload`.

3. Run command `docker-compose up` in terminal.
  
