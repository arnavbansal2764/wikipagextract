# Setup Procedure

## Clone the repository or download the zip folder : 
``` bash 
git clone https://github.com/arnavbansal2764/wikipagextract.git
 ```

## Open the folder and install dependencies
``` bash
cd wikipagextract
npm install
```

## Replace the existing url in typescript file with your desired url
```bash
const wikipediaUrl = 'your_url';
fetchWebpage(wikipediaUrl).then(html => {
  const content = extractContent(html);
  saveContent(content, wikipediaUrl);
});
```

## Build the typescript file
```bash
tsc -b
```

## Run the javascript file
```bash
node index.js
```

## The code will run and create an output folder in the main directory which will have all the text urls and images.



