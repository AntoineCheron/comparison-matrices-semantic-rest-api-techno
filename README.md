# Comparison matrices of Semantic REST API Technologies - Methodology

The methodology and raw material used to design the comparison matrices and its criteria presented in *Comparison matrices of Semantic REST API Technologie*.

## Methodology description

The design of our comparison matrices follows a 5 steps sequential process: *(i)* **search** for candidate technologies, *(ii)* **select** candidate technologies, *(iii)* **read** carefully each candidate technology, *(iv)* **elaborate fine grain criteria** to characterize and differentiate technologies, *(v)* **verification** that the elaborated criteria highlighted the differences between technologies. Several steps of refinement were needed to avoid duplicating criteria or hiding important details, by looping on step *(iv)* and *(v)*.

The research of candidate technologies (step i) was done by:

1. Searching Google and Google Scholar for Semantic REST Technologies using compositions of keywords from the set: ["web", "semantic", "restful", "rest", "service", "API", "interface", "description", "documentation", "language", "modeling", "hypermedia", "document", "format", "RDF", "data-interchange", "linked data", "hateoas", "rest api", "framework"];
2. Searching Google Scholar for tools automating tasks from services description, using keywords: "matchmakers", "service composition", "service discovery", "rest service analysis", "automated mashups", we then selected other papers and technologies from their references and the papers that cite those we selected;
3. Searching the proceedings of ICWE and WS-REST. 

We selected 81 papers, standards, articles and web pages (step ii) from their abstract or introduction. We selected documents that were the specification of an interface definition language or model, a framework that supports HATEOAS features, an interchange format that supports RDF or HATEOAS features, a comparison between these technologies or a tool leveraging them. Frameworks to build Semantic Web Services were excluded because they are based on triples which are too far from the resource-oriented design of REST. We opened our research to technologies from the 1990s to today and retained technologies that are still available today.

As a next step, we read the specification of each chosen technology (step iii) and elaborate classification criteria (step iv). We included those of the [H Factor](http://amundsen.com/hypermedia/hfactor/) which *is a measurement of the level of hypermedia support and sophistication of a media-type*. Others were carefully designed to highlight differences between technologies in the area of Semantic REST, based on the core design of the technologies, the features they provide and the details of the WS3 maturity model. All the raw material to elaborate this classification is available in this repository.

As a final step (step v), we read the specifications again to verify results and validate that the selected criteria highlighted differences and commonalities well.

### Popularity criteria

We included a popularity criteria to provide a rough idea of the community support and the likelihood of the technology to last in time. The popularity score is between 0 and 2. It respects the following rules: **0 -** Not enough to reach 1; **1 -** More than 100 questions on stack overflow AND (2500+ NPM weekly downloads OR 100+ maven usages); **2 -** More than 400 questions on stack overflow AND (more than 500.000 total downloads OR more than 15.000 NPM weekly downloads OR more than 500 maven usages).

## Available resources

* [Papers used](./papers/)
* [Web pages used](./other-readings/web-pages.md)
* [Interface Description Languages Specifications](./other-readings/idl-specs.md)
* [Data Interchange Format Specifications](./other-readings/dif-specs.md)
* [Frameworks Documentation](./other-readings/frameworks-doc.md)
* [IDL Classification Matrix](./tables/IDL.png)
* [Data Interchange Format Classification Matrix](./tables/DIF.png)
* [Frameworks Matrix](./tables/frameworks.png)
