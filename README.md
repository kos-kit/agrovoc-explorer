# Explorer demo using the [AGROVOC Multilingual Thesaurus](https://agrovoc.fao.org/browse/agrovoc/en/)

AGROVOC is a structured collection of concepts, terms, definitions and relationships related to food and agriculture, such as maize, hunger, aquaculture, value chains or forestry.

AGROVOC is a large SKOS dataset consisting of over 41,000 concepts and 1,151,000 terms (labels) in up to 42 languages.

We will use AGROVOC to demonstrate how to run the [KOS Kit Explorer](https://github.com/kos-kit/explorer) in a client-server configuration with datasets that are too large for static site generation and delivery to the browser.

## Prerequisites

- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/)

## One-time setup

### Download an AGROVOC Core Release

Place the `agrovoc_<timestamp>_core.nt` file in the `release` directory in this repository.

AGROVOC is licensed under the [Creative Commons Attribution 4.0 (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/).

## Running

    docker compose up

Then open your browser to [http://localhost:8080](http://localhost:8080).
