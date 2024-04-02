# Fact Of The Day In Asciidoc
Here's a nice little fact of the day about ants and their contribution to the solving of real worlds problems written in [asciidoc](https://asciidoc.org/).

# Asciidoc
I am using [Asciidoctor.js](https://docs.asciidoctor.org/asciidoctor.js/latest/cli/install/) as the asciidoc processor for this project although there are other options you can choose from. 

- [Ascidoctor (Ruby)](https://docs.asciidoctor.org/asciidoctor/latest/)
- [AscidoctorJ (Java)](https://docs.asciidoctor.org/asciidoctorj/latest/)

## Usage
Install [Node.js](https://nodejs.org/en)

Install [Asciidoctor.js](https://docs.asciidoctor.org/asciidoctor.js/latest/cli/install/)
```
npm i -g asciidoctor
```

Convert the `.adoc` file to HTML
```
asciidoctor ant.adoc --out-file=index.html
```

<br>

Check out the [asciidoc site](https://asciidoc.org/) for the full documentation